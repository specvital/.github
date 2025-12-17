<p align="center">
  <img src="https://raw.githubusercontent.com/specvital/.github/main/public/banner.png" alt="Specvital" />
</p>

<p align="center">
  <strong>CI 실행 없이, 소스코드만으로 테스트 인벤토리를 자동 생성하는 플랫폼</strong>
</p>

<p align="center">
  정적 분석 기반 · 다중 언어 지원 · GitHub URL 입력만으로 시작
</p>

<p align="center">
  <a href="https://github.com/specvital/.github/blob/main/profile/README.md">English</a>
</p>

---

## 생태계

| 리포지토리                                              | 설명                                                    | 기술 스택         |
| ------------------------------------------------------- | ------------------------------------------------------- | ----------------- |
| **[core](https://github.com/specvital/core)**           | Tree-sitter 기반 테스트 파서 엔진 (Go 라이브러리 + CLI) | Go, Tree-sitter   |
| **[web](https://github.com/specvital/web)**             | 웹 대시보드 및 REST API                                 | Go (Chi), Next.js |
| **[collector](https://github.com/specvital/collector)** | 백그라운드 분석 워커 서비스                             | Go, asynq         |
| **[infra](https://github.com/specvital/infra)**         | 로컬 개발 인프라 및 DB 스키마 관리                      | Docker, Atlas     |

## 지원 프레임워크 (20+)

| 언어                      | 프레임워크                                   |
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
