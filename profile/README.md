<p align="center">
  <img src="https://raw.githubusercontent.com/specvital/.github/main/public/banner.png" alt="Specvital" />
</p>

<p align="center">
  <strong>Auto-generate test inventory from source code, without CI execution</strong>
</p>

<p align="center">
  Static analysis based · Multi-language support · Start with just a GitHub URL
</p>

<p align="center">
  <a href="https://github.com/specvital/.github/blob/main/profile/README.ko.md">한국어</a>
</p>

---

## Ecosystem

| Repository                                              | Description                                             | Stack             |
| ------------------------------------------------------- | ------------------------------------------------------- | ----------------- |
| **[core](https://github.com/specvital/core)**           | Tree-sitter based test parser engine (Go library + CLI) | Go, Tree-sitter   |
| **[web](https://github.com/specvital/web)**             | Web dashboard and REST API                              | Go (Chi), Next.js |
| **[collector](https://github.com/specvital/collector)** | Background analysis worker service                      | Go, asynq         |
| **[infra](https://github.com/specvital/infra)**         | Local dev infrastructure and DB schema management       | Docker, Atlas     |

## Supported Frameworks (20+)

| Language                  | Frameworks                                   |
| ------------------------- | -------------------------------------------- |
| **JavaScript/TypeScript** | Jest · Vitest · Playwright · Cypress · Mocha |
| **Go**                    | Go testing                                   |
| **Python**                | pytest · unittest                            |
| **Java/Kotlin**           | JUnit 5 · TestNG · Kotest                    |
| **C#/.NET**               | xUnit · NUnit · MSTest                       |
| **Ruby**                  | RSpec · Minitest                             |
| **Rust**                  | Cargo test                                   |
| **C++**                   | Google Test                                  |
| **PHP**                   | PHPUnit                                      |
| **Swift**                 | XCTest                                       |
