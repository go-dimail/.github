<p align="center">
  <img src="https://raw.githubusercontent.com/go-dimail/brand/main/social.png" alt="go-dimail" width="720">
</p>

<p align="center">
  A pure-Go (CGO-free) client for the <strong>Dimail API</strong> — the mail-hosting
  management API of the French government's <em>La Suite numérique</em> platform —
  generated from the API's OpenAPI document.
</p>

<p align="center">
  <a href="https://go-dimail.github.io/">Website</a> ·
  <a href="https://go-dimail.github.io/docs/">Documentation</a> ·
  <a href="https://github.com/go-ruby-dimail">Ruby face (go-ruby-dimail)</a>
</p>

---

### Repositories

| Repo | What it is |
| --- | --- |
| [**dimail**](https://github.com/go-dimail/dimail) | The typed Go client: 96 models, 91 methods, generated from `openapi.json`. Basic→bearer auth, typed `APIError`, 100% coverage, 6 arches. |

### Principles

- **Generated from source.** The OpenAPI document and the generator both live in
  the tree; `go generate ./...` refreshes the client and CI fails on drift.
- **CGO-free.** Builds and tests identically on amd64, arm64, riscv64, loong64,
  ppc64le and s390x.
- **BSD-3-Clause.** Independent client; not affiliated with or endorsed by DINUM.
