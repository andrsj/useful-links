# Go Useful Links

## Getting Started & Learning

| Resource                                                                                | Description                                                           |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [Go Documentation](https://go.dev/doc/)                                                 | Official documentation hub — tutorials, references, and guides        |
| [Go by Example](https://gobyexample.com/)                                               | Hands-on introduction to Go with annotated code examples              |
| [Effective Go](https://go.dev/doc/effective_go)                                         | Official guide to writing clear, idiomatic Go code                    |
| [Go Tour (Ardanlabs)](https://tour.ardanlabs.com/tour/eng/list)                         | Interactive tour covering Go fundamentals with exercises              |
| [Practical Go Lessons](https://www.practical-go-lessons.com/)                           | Free online book with 41 chapters covering Go from basics to advanced |
| [Go Roadmap](https://roadmap.sh/golang)                                                 | Step-by-step learning path for Go developers                          |
| [YourBasic Go](https://yourbasic.org/golang/)                                           | Collection of concise Go tutorials and best practices                 |
| [100 Go Mistakes](https://100go.co/)                                                    | Common Go mistakes and how to avoid them (companion site to the book) |
| [Go Cheatsheet](https://devhints.io/go)                                                 | Quick reference cheatsheet for Go syntax and patterns                 |
| [Learning Go in 2024](https://www.bytesizego.com/blog/learning-golang-2024)             | Curated guide on how to learn Go effectively                          |
| [Go for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) | Side-by-side comparison of Go and Node.js patterns                    |
| [Go Proverbs](https://go-proverbs.github.io/)                                           | Rob Pike's Go proverbs — philosophy behind Go's design                |

## Official Go Blog

| Resource                                                                 | Description                                                                |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| [The Go Blog](https://go.dev/blog/)                                      | Official blog with release notes, technical articles, and language updates |
| [Allocation Optimizations](https://go.dev/blog/allocation-optimizations) | How the Go compiler optimizes memory allocations                           |
| [Golang Weekly](https://golangweekly.com/issues/latest)                  | Weekly newsletter with Go articles, tools, and news                        |

## Project Structure & Modules

| Resource                                                                            | Description                                            |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------ |
| [Go Module Layout](https://go.dev/doc/modules/layout)                               | Best practices for organizing Go projects and packages |
| [GOPATH in VS Code](https://github.com/golang/vscode-go/blob/master/docs/gopath.md) | How GOPATH works with the VS Code Go extension         |

## Performance & Internals

| Resource                                                                                                                                                        | Description                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| [Escape Analysis in Go](https://blog.devgenius.io/escape-analysis-in-go-understanding-memory-optimization-83d29f13fa1d)                                         | How Go decides stack vs heap allocation                                      |
| [No GC in Go: Benchmarks](https://blog.devgenius.io/no-garbage-collection-in-go-performance-benchmarks-eca6c2fb8307)                                            | Performance gains from reducing garbage collection pressure                  |
| [Profiling with pprof](https://blog.devgenius.io/profiling-in-go-finding-and-fixing-performance-bottlenecks-868e5c7e929b)                                       | Finding and fixing performance bottlenecks with Go profiler                  |
| [Profiling Go with pprof](https://dou.ua/forums/topic/54137/) 🇺🇦                                                                                                 | Investigating Go programs with pprof                                         |
| [Go PGO](https://theyahya.com/posts/go-pgo/)                                                                                                                    | Profile-Guided Optimization — how to speed up Go binaries with real profiles |
| [Go Internals Deep Dive](https://meetsoni15.medium.com/unveiling-golangs-hidden-internals-discover-the-hidden-mechanics-that-optimize-performance-8f946f784041) | Hidden mechanics that optimize Go performance under the hood                 |
| [1BRC in Go](https://r2p.dev/b/2024-03-18-1brc-go/)                                                                                                             | One Billion Row Challenge — optimizing Go for extreme data processing        |
| [Memory Allocation in Go](https://nghiant3223.github.io/2025/06/03/memory_allocation_in_go.html)                                                                | How Go manages memory allocation internally                                  |

## Concurrency & Synchronization

| Resource                                                                                        | Description                                                   |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| [Production Concurrency](https://storj.dev/blog/production-concurrency)                         | Real-world concurrency patterns from Storj production systems |
| [Synchronization Primitives](https://hackernoon.com/mastering-synchronization-primitives-in-go) | Mastering mutexes, channels, and sync primitives in Go        |
| [Go Scheduling (Part 1)](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part1.html)    | OS scheduler, Go scheduler, and goroutine mechanics explained |

## Testing

| Resource                                                                                                        | Description                                                               |
| --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| [Testing Best Practices](https://fossa.com/blog/golang-best-practices-testing-go/)                              | Comprehensive guide to testing patterns in Go                             |
| [f-tests vs Table-Driven](https://itnext.io/f-tests-as-a-replacement-for-table-driven-tests-in-go-8814a8b19e9e) | Alternative to table-driven tests using f-tests pattern                   |
| [Prefer Real Over Mocks](https://abseil.io/resources/swe-book/html/ch13.html)                                   | Why real components or fakes are better than mocks (from Google SWE book) |

## Interfaces & Types

| Resource                                                                              | Description                                                            |
| ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [Interfaces Deep Dive](https://tul.github.io/2018/07/23/go-interfaces-deep-dive.html) | How Go interfaces work internally — itables, type assertions, and more |

## Error Handling

| Resource                                                                                                   | Description                                                   |
| ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| [Secure Error Handling](https://blog.jetbrains.com/go/2026/03/02/secure-go-error-handling-best-practices/) | Best practices for secure Go error handling (JetBrains, 2026) |

## HTTP & Services

| Resource                                                                                                 | Description                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [HTTP Services After 13 Years](https://grafana.com/blog/how-i-write-http-services-in-go-after-13-years/) | Mat Ryer's updated patterns for writing Go HTTP services |

## Architecture & Patterns

| Resource                                                                                                                                       | Description                                                    |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| [Saga Pattern in Go](https://blog.devgenius.io/saga-pattern-in-go-building-resilient-distributed-transactions-with-orchestration-19d9746d8b85) | Building resilient distributed transactions with orchestration |
| [Design Patterns in Go](https://refactoring.guru/design-patterns/go)                                                                           | Classic design patterns with Go implementations and examples   |
| [Microservices Patterns](https://microservices.io/patterns/microservices.html)                                                                 | Pattern catalog for microservice architecture                  |
| [The Twelve-Factor App](https://12factor.net/)                                                                                                 | Methodology for building modern, scalable, cloud-native apps   |

## Go Runtime Source Code

| Resource                                                                                                 | Description                                                   |
| -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| [main goroutine](https://github.com/golang/go/blob/master/src/runtime/proc.go#L151)                      | Entry point of the Go runtime — where `main` goroutine starts |
| [Preemption (go1.26)](https://github.com/golang/go/blob/release-branch.go1.26/src/runtime/proc.go#L6628) | `forcePreemptNS` — time slice before a goroutine is preempted |
| [Preemption (go1.24)](https://github.com/golang/go/blob/go1.24.9/src/runtime/proc.go#L6305)              | Same preemption constant in Go 1.24 for comparison            |

## Tooling

| Resource                                                                 | Description                                                         |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| [golangci-lint](https://golangci-lint.run/docs/welcome/)                 | Aggregated Go linter — fast, configurable, supports 100+ linters    |
| [golangci-lint Config](https://github.com/maratori/golangci-lint-config) | Well-documented starting point for a detailed golangci-lint config  |
| [Compiler Explorer](https://godbolt.org/)                                | Online tool to see Go assembly output and compare compiler behavior |

## Style Guides

| Resource                                                        | Description                                                                         |
| --------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| [Google Go Style Guide](https://google.github.io/styleguide/go) | Google's official Go style guide — decisions, best practices, and review guidelines |
| [Uber Go Style Guide](https://github.com/uber-go/guide)         | Uber's Go coding conventions and patterns                                           |

## Dave Cheney

| Resource                                                                                                        | Description                                                |
| --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| [Practical Go (QCon China)](https://dave.cheney.net/practical-go/presentations/qcon-china.html)                 | Real-world advice on writing maintainable Go programs      |
| [Practical Go (GopherCon SG)](https://dave.cheney.net/practical-go/presentations/gophercon-singapore-2019.html) | Updated practical Go presentation from GopherCon Singapore |
| [Practical Go (GopherCon IL)](https://dave.cheney.net/practical-go/presentations/gophercon-israel.html)         | Practical Go presentation from GopherCon Israel            |
| [Prefer Table-Driven Tests](https://dave.cheney.net/2019/05/07/prefer-table-driven-tests)                       | Why table-driven tests are the Go way                      |
| [SOLID Go Design](https://dave.cheney.net/2016/08/20/solid-go-design)                                           | Applying SOLID principles to Go code                       |

## VictoriaMetrics Blog (Go Series)

| Resource                                                                                                        | Description                                             |
| --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| [All Go articles](https://victoriametrics.com/categories/go-@-victoriametrics/)                                 | Full list of Go deep-dive articles by VictoriaMetrics   |
| [gRPC Streaming & Interceptors](https://victoriametrics.com/blog/go-grpc-basic-streaming-interceptor/)          | gRPC basics, streaming patterns, and interceptor usage  |
| [K8s CPU & GOMAXPROCS](https://victoriametrics.com/blog/kubernetes-cpu-go-gomaxprocs/)                          | How Kubernetes CPU limits interact with Go's GOMAXPROCS |
| [Time: Monotonic & Wall Clock](https://victoriametrics.com/blog/go-time-monotonic-wall-clock/)                  | How Go handles two types of time and why it matters     |
| [sync.Map](https://victoriametrics.com/blog/go-sync-map/index.html)                                             | When and how to use Go's concurrent-safe map            |
| [Graceful Shutdown](https://victoriametrics.com/blog/go-graceful-shutdown/)                                     | Patterns for cleanly shutting down Go services          |
| [synctest](https://victoriametrics.com/blog/go-synctest/)                                                       | Testing concurrent Go code with the synctest package    |
| [Protobuf in Go](https://victoriametrics.com/blog/go-protobuf/)                                                 | Working with Protocol Buffers in Go                     |
| [HTTP/2 in Go](https://victoriametrics.com/blog/go-http2/)                                                      | How HTTP/2 works in Go's net/http package               |
| [sync.Cond](https://victoriametrics.com/blog/go-sync-cond/)                                                     | Using sync.Cond for goroutine coordination              |
| [net/rpc](https://victoriametrics.com/blog/go-net-rpc/)                                                         | Go's built-in RPC package — usage and internals         |
| [Finalizers & KeepAlive](https://victoriametrics.com/blog/go-runtime-finalizer-keepalive/)                      | runtime.SetFinalizer and runtime.KeepAlive explained    |
| [Go Maps Internals](https://victoriametrics.com/blog/go-map/)                                                   | How Go maps work under the hood                         |
| [sync.WaitGroup](https://victoriametrics.com/blog/go-sync-waitgroup/)                                           | Coordinating goroutines with WaitGroup                  |
| [sync.Once](https://victoriametrics.com/blog/go-sync-once/)                                                     | One-time initialization patterns with sync.Once         |
| [Weak Pointers](https://victoriametrics.com/blog/go-weak-pointer/)                                              | Go's weak pointer support and use cases                 |
| [io: Closer, Seeker, ReadFrom, WriteTo](https://victoriametrics.com/blog/go-io-closer-seeker-readfrom-writeto/) | Advanced io interfaces beyond Reader/Writer             |
| [io: Reader & Writer](https://victoriametrics.com/blog/go-io-reader-writer/)                                    | Fundamentals of Go's io.Reader and io.Writer            |
| [Arrays in Go](https://victoriametrics.com/blog/go-array/)                                                      | How Go arrays work and differ from slices               |
| [singleflight](https://victoriametrics.com/blog/go-singleflight/)                                               | Deduplicating concurrent calls with singleflight        |

## Three Dots Labs (Wild Workouts)

| Resource                                                                                                    | Description                                                 |
| ----------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [CQRS in Go](https://threedots.tech/post/basic-cqrs-in-go/)                                                 | Implementing Command-Query Responsibility Segregation in Go |
| [Clean Architecture](https://threedots.tech/post/introducing-clean-architecture/)                           | Practical clean architecture approach for Go applications   |
| [Recommended Libraries](https://threedots.tech/post/list-of-recommended-libraries/#ddd--clean-architecture) | Curated list of Go libraries for DDD and clean architecture |
| [Microservices Test Architecture](https://threedots.tech/post/microservices-test-architecture/)             | Testing strategies for Go microservices                     |
| [Database Integration Testing](https://threedots.tech/post/database-integration-testing/)                   | How to write reliable database integration tests in Go      |

## Ardanlabs

| Resource                                                                                     | Description                                         |
| -------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| [Ultimate Go Tour](https://tour.ardanlabs.com/tour/eng/list)                                 | Comprehensive interactive Go course by Bill Kennedy |
| [Go Scheduling (Part 1)](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part1.html) | Deep dive into OS and Go scheduler internals        |

## Game Development

| Resource                                        | Description                                                |
| ----------------------------------------------- | ---------------------------------------------------------- |
| [Ebitengine](https://www.quasilyte.dev/ebiten/) | 2D game engine for Go ([example](https://t.me/ntuzov/684)) |

## Books

| Resource                                                                                               | Description                                                         |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| Джон Боднер — Go: ідіоми та патерни проєктування                                                       | Переклад книги Learning Go українською                              |
| Jon Bodner — Learning Go                                                                               | Idiomatic Go patterns and best practices for experienced developers |
| [Efficient Go](https://www.amazon.com/Efficient-Go-Data-Driven-Performance-Optimization/dp/1098105710) | Data-driven approach to Go performance optimization                 |
| [Let's Go](https://lets-go.alexedwards.net/)                                                           | Building professional web apps in Go — step by step                 |
| [Go with the Domain](https://threedots.tech/go-with-the-domain/)                                       | DDD, CQRS, and clean architecture in Go (free online book)          |

## Web & General

| Resource                                             | Description                                                    |
| ---------------------------------------------------- | -------------------------------------------------------------- |
| [MDN Web Docs](https://developer.mozilla.org/en-US/) | Comprehensive web platform documentation (HTML, CSS, JS, HTTP) |

## Example Repositories

| Repository                                                 | Description                                                                       |
| ---------------------------------------------------------- | --------------------------------------------------------------------------------- |
| [Go source](https://go.googlesource.com/)                  | Official Go language repositories                                                 |
| [golangci-lint](https://github.com/golangci/golangci-lint) | Great PR descriptions by ldez — good example of project maintenance               |
| [Chezmoi](https://github.com/twpayne/chezmoi)              | Author actively follows Go blogs and incorporates new techniques into the project |
| [Goreleaser](https://github.com/goreleaser/goreleaser)     | Well-written tests                                                                |
| [Delve](https://github.com/go-delve/delve)                 | Low-level code — Go debugger                                                      |
| [Perkeep](https://github.com/perkeep/perkeep)              | Clean code organization. Author previously worked on Go's net/http                |
