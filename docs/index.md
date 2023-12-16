# dns01d

---

> Cloud provider ACME DNS-01 validation without exposing DNS API tokens

## What is dns01d?

**dns01d** is a middleware service that enables ACME DNS-01 validation with cloud DNS providers without exposing sensitive API tokens. Each **dns01d** client can be limited in what individual or groups of records they are allowed to change.

**dns01d** comes in two flavors:

| **dns01d**<br>_(Core)_ | **dns01d-cf**<br>_(CloudFlare Worker)_ |
| :---: | :---: |
| Self-hosted multi-cloud daemon | Lightweight CloudFlare Worker for only domains on CloudFlare |
| [GitHub Repository](https://github.com/dns01d/dns01d) - Docs (Coming Soon) | [GitHub Repository](https://github.com/dns01d/dns01d-cf) - Docs (Coming Soon) |

More coming soon...

## License

[MIT License](./license)
