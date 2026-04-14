# Useful IT Links

- [Useful IT Links](#useful-it-links)
  - [Software Engineering \& Architecture](#software-engineering--architecture)
  - [API Design \& Protocols](#api-design--protocols)
  - [Real-Time Communication](#real-time-communication)
  - [Web Development](#web-development)
  - [Databases](#databases)
  - [Distributed Systems](#distributed-systems)
  - [DevOps \& Docker](#devops--docker)
  - [Security](#security)
  - [Code Review \& Engineering Culture](#code-review--engineering-culture)
  - [SRE \& System Design](#sre--system-design)
  - [Linux \& OS](#linux--os)
  - [Low-Level \& CS Fundamentals](#low-level--cs-fundamentals)
  - [Networking](#networking)
  - [Tools \& Search](#tools--search)
  - [Books](#books)
  - [Awesome Lists](#awesome-lists)


## Software Engineering & Architecture

| Resource                                                                                                                                                                    | Author          | Description                                                                 |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- | --------------------------------------------------------------------------- |
| [Refactoring Guru](https://refactoring.guru/)                                                                                                                               |                 | Design patterns, refactoring techniques, and SOLID principles with examples |
| [The Twelve-Factor App](https://12factor.net/)                                                                                                                              | Heroku          | Methodology for building scalable, maintainable cloud-native applications   |
| [Clean Architecture (DDD, Hexagonal, Onion, CQRS)](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/) |                 | How DDD, hexagonal, onion, and clean architecture fit together              |
| [Clean Architecture in Go](https://threedots.tech/post/introducing-clean-architecture/)                                                                                     | Three Dots Labs | Practical clean architecture approach for Go applications                   |
| [Microservices Patterns](https://microservices.io/patterns/microservices.html)                                                                                              |                 | Catalog of microservice architecture patterns                               |
| [Monorepo Tools](https://monorepo.tools/)                                                                                                                                   | monorepo.tools  | Comparison of monorepo build tools (Nx, Turborepo, Bazel, etc.)             |
| [Making Software](https://www.makingsoftware.com/)                                                                                                                          | makingsoftware  | Reference manual for people who design and build software                   |

## API Design & Protocols

| Resource                                                                                 | Author         | Description                                                               |
| ---------------------------------------------------------------------------------------- | -------------- | ------------------------------------------------------------------------- |
| [Zalando RESTful API Guidelines](https://opensource.zalando.com/restful-api-guidelines/) | Zalando        | Comprehensive REST API design guidelines                                  |
| [Complete REST Overview](https://dou.ua/forums/topic/50364/) 🇺🇦                           | DOU (platform) | Tips, nuances, and examples of REST API design                            |
| [ConnectRPC](https://connectrpc.com/)                                                    | Buf            | Simple, HTTP-based RPC framework compatible with gRPC                     |
| [OAuth 2.0 Simplified](https://aaronparecki.com/oauth-2-simplified/)                     |                | Clear walkthrough of OAuth 2.0 flows and best practices                   |
| [Aaron Parecki](https://aaronparecki.com/)                                               |                | Director of Identity Standards at Okta — OAuth and IndieWeb expert        |
| [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)                   | Community      | Specification for structured, human- and machine-readable commit messages |

## Real-Time Communication

| Resource                                                                                                                 | Author | Description                                                           |
| ------------------------------------------------------------------------------------------------------------------------ | ------ | --------------------------------------------------------------------- |
| [WebSocket Alternatives](https://ably.com/topic/websocket-alternatives)                                                  | Ably   | Comparison of real-time transport protocols (SSE, WebTransport, etc.) |
| [Server-Sent Events (SSE)](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events/Using_server-sent_events) | MDN    | Guide to receiving real-time events from a server via EventSource API |
| [WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket)                                              | MDN    | API for bidirectional real-time connections                           |
| [WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)                                                | MDN    | Peer-to-peer audio, video, and data exchange in the browser           |
| [WebTransport API](https://developer.mozilla.org/en-US/docs/Web/API/WebTransport)                                        | MDN    | HTTP/3-based API with reliable and unreliable bidirectional transport |
| MQTT                                                                                                                     |        | Lightweight publish-subscribe messaging protocol (link TBD)           |

## Web Development

| Resource                                             | Author           | Description                                                     |
| ---------------------------------------------------- | ---------------- | --------------------------------------------------------------- |
| [MDN Web Docs](https://developer.mozilla.org/en-US/) | Mozilla          | Comprehensive reference for HTML, CSS, JavaScript, and web APIs |
| [JSON Graph Editor](https://jsonviewer.tools/editor) | jsonviewer.tools | Online tool to convert JSON to graph diagrams                   |

## Databases

| Resource                                                                                                         | Author    | Description                                                           |
| ---------------------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------- |
| [MongoDB Use Cases](https://www.mongodb.com/solutions/use-cases)                                                 | MongoDB   | Real-world scenarios where MongoDB fits best                          |
| [Why Use MongoDB](https://www.mongodb.com/resources/products/fundamentals/why-use-mongodb)                       | MongoDB   | Overview of MongoDB benefits and architecture                         |
| [Redis Use Cases by Data Structure](https://scalegrid.io/blog/top-redis-use-cases-by-core-data-structure-types/) | ScaleGrid | How to leverage Redis strings, hashes, sets, sorted sets, and streams |
| [Redis for Developers](https://redis.io/blog/5-industry-use-cases-for-redis-developers/)                         | Redis     | Industry use cases for Redis — caching, sessions, queues, and more    |
| [Build Your Own Database](https://www.nan.fyi/database)                                                          | nan.fyi   | Interactive tutorial building a database from scratch                 |

## Distributed Systems

| Resource                                                                                          | Author    | Description                                                           |
| ------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------- |
| [PACELC Theorem](https://ru.wikipedia.org/wiki/%D0%A2%D0%B5%D0%BE%D1%80%D0%B5%D0%BC%D0%B0_PACELC) | Wikipedia | Extension of CAP theorem — trade-offs between latency and consistency |

## DevOps & Docker

| Resource                                                                                           | Author           | Description                                                                                    |
| -------------------------------------------------------------------------------------------------- | ---------------- | ---------------------------------------------------------------------------------------------- |
| [Docker Compose Cheat Sheet](https://devopscycle.com/blog/the-ultimate-docker-compose-cheat-sheet) | DevOpsCycle      | Quick reference for docker-compose syntax and features                                         |
| [Linode Guides](https://www.linode.com/docs/guides/)                                               | Linode           | Tutorials on Linux, cloud infrastructure, and DevOps                                           |
| [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)              | Kelsey Hightower | Bootstrap a Kubernetes cluster from scratch — no scripts, no tools, learn the internals        |
| [DevOps Exercises](https://github.com/bregman-arie/devops-exercises)                               |                  | Linux, Jenkins, AWS, SRE, Prometheus, Docker, Python, Ansible, Git, Kubernetes — interview Q&A |

## Security

| Resource                                                                              | Author  | Description                                                               |
| ------------------------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------- |
| [OWASP Cheat Sheets](https://cheatsheetseries.owasp.org/index.html)                   | OWASP   | Security cheat sheets for authentication, input validation, XSS, and more |
| [Intro to Cybersecurity](https://github.com/sarin00/Course1-Intro-to-Cybersecruity) 🇺🇦 | sarin00 | Cybersecurity fundamentals course                                         |

## Code Review & Engineering Culture

| Resource                                                                                            | Author | Description                                                                                      |
| --------------------------------------------------------------------------------------------------- | ------ | ------------------------------------------------------------------------------------------------ |
| [Human Code Reviews](https://mtlynch.io/human-code-reviews-1/)                                      |        | How to do code reviews that are effective and humane                                             |
| [Uber Engineering Blog](https://www.uber.com/en-US/blog/engineering/)                               | Uber   | Technical blog covering Uber's engineering challenges and solutions                              |
| [Software Engineering at Google](https://abseil.io/resources/swe-book/html/toc.html)                | Google | Free digital copy of "Software Engineering at Google" book                                       |
| [Google Code Review: Reviewer Guide](https://google.github.io/eng-practices/review/reviewer/)       | Google | Google's guide for reviewers — what to look for, how to navigate CLs, speed                      |
| [Google Code Review: Developer Guide](https://google.github.io/eng-practices/review/developer/)     | Google | Google's guide for CL authors — writing good descriptions, small CLs, handling reviewer comments |
| [VictoriaMetrics Story](https://underdogfounders.substack.com/p/victoriametrics-ukrainian-database) |        | Interview with co-founder of VictoriaMetrics — Ukrainian database company                        |

## SRE & System Design

| Resource                                                                  | Author     | Description                                                                    |
| ------------------------------------------------------------------------- | ---------- | ------------------------------------------------------------------------------ |
| [Google SRE Books](https://sre.google/books/)                             | Google     | Free online SRE books from Google — SRE, Workbook, and Building Secure Systems |
| [System Design Course](https://books.dwf.dev/docs/system-design/c0)       | dwf.dev    | Free system design fundamentals course                                         |
| [System Design Primer](https://github.com/karanpratapsingh/system-design) |            | Comprehensive system design notes and resources                                |
| [System Design 101](https://github.com/ByteByteGoHq/system-design-101)    | ByteByteGo | Visual explanations of system design concepts and architectures                |

## Linux & OS

| Resource                                                                    | Author       | Description                                                |
| --------------------------------------------------------------------------- | ------------ | ---------------------------------------------------------- |
| [Linux Path](https://www.linux-path.com/en)                                 | linux-path   | Interactive Linux learning platform                        |
| [Linux Voyage](https://linuxvoyage.github.io/)                              | Linux Voyage | Guided journey through Linux fundamentals                  |
| [Linux Journey (LabEx)](https://labex.io/linuxjourney)                      | LabEx        | Hands-on Linux tutorials from basics to advanced           |
| [Linux Syscall Table](https://syscalls.mebeim.net/?table=x86/64/x64/latest) | mebeim       | Complete x86_64 Linux kernel syscall reference table       |
| [Nand to Tetris](https://books.dwf.dev/docs/nand-to-tetris/introduction)    |              | Build a computer from logic gates to a high-level language |

## Low-Level & CS Fundamentals

| Resource                                                                                                                                         | Author         | Description                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- | --------------------------------------------------------------------- |
| [What Every Programmer Should Know About Memory](https://lrita.github.io/images/posts/memory/What-Every-Programmer-Should-Know-About-Memory.pdf) |                | Classic paper on memory architecture and optimization (PDF)           |
| [CS Cheatsheets Collection](https://github.com/Learn-Together-Pro/ComputerScience/blob/master/cs/cheatsheets.md)                                 | Learn Together | Curated collection of computer science cheat sheets                   |
| [Compiler Explorer](https://godbolt.org/)                                                                                                        |                | See assembly output from C, C++, Rust, Go, and other compilers online |

## Networking

| Resource                                                          | Author   | Description                                                           |
| ----------------------------------------------------------------- | -------- | --------------------------------------------------------------------- |
| [Networking for Beginners](https://linkmeup.gitbook.io/sdsm) `RU` | linkmeup | Comprehensive networking course covering protocols, routing, and more |

## Tools & Search

| Resource                                      | Author        | Description                                        |
| --------------------------------------------- | ------------- | -------------------------------------------------- |
| [Sourcegraph](https://sourcegraph.com/search) | Sourcegraph   | Code search across public and private repositories |
| [MicroGPT](https://ko-microgpt.vercel.app/)   | ko            | Interactive app for understanding how LLMs work    |
| [Font Download](https://font.download/)       | font.download | Free font library for design and development       |

## Books

| Resource                                                                                                                                         | Author | Description                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------ | ------------------------------------------------------------------------------ |
| [Operating System Concepts (10th ed.)](https://www.wiley.com/en-us/Operating+System+Concepts%2C+10th+Edition-p-9781119320913)                    |        | Classic "Dinosaur Book" — OS fundamentals, processes, memory, and file systems |
| [System Design Interview](https://www.amazon.com/System-Design-Interview-Insiders-Guide/dp/1736049119)                                           |        | Guide to system design interviews                                              |
| [Designing Data-Intensive Applications](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/) |        | Deep dive into distributed systems and data storage                            |
| [Google SRE Books](https://sre.google/books/)                                                                                                    | Google | Free SRE books from Google                                                     |

## Awesome Lists

| Resource                                                                             | Stars | Description                                                        |
| ------------------------------------------------------------------------------------ | ----- | ------------------------------------------------------------------ |
| [Awesome](https://github.com/sindresorhus/awesome)                                   | 350k+ | Meta-list of awesome lists for all topics                          |
| [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)       | 283k+ | Self-hosted software alternatives                                  |
| [Awesome Python](https://github.com/vinta/awesome-python)                            | 289k+ | Curated list of Python frameworks, libraries, and tools            |
| [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) | 72k+  | ML frameworks, libraries, and software                             |
| [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript)                  | 34k+  | JavaScript libraries, resources, and tools                         |
| [Awesome React](https://github.com/enaqx/awesome-react)                              | 72k+  | React ecosystem resources and libraries                            |
| [Awesome Vue](https://github.com/vuejs/awesome-vue)                                  | 73k+  | Vue.js components, libraries, and resources                        |
| [Awesome Security](https://github.com/sbilly/awesome-security)                       | 14k+  | Security tools, resources, and references                          |
| [Awesome Big Data](https://github.com/oxnr/awesome-bigdata)                          | 14k+  | Big data frameworks, tools, and resources                          |
| [Awesome Android](https://github.com/JStumpp/awesome-android)                        | 12k+  | Android libraries, tools, and resources                            |
| [Awesome iOS](https://github.com/vsouza/awesome-ios)                                 | 51k+  | iOS frameworks, libraries, and tools                               |
| [Awesome Design](https://github.com/gztchan/awesome-design)                          | 16k+  | Design tools, resources, and inspiration                           |
| [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)               | 33k+  | Curated list of awesome lists                                      |
| [Awesome Linux Software](https://github.com/luong-komorebi/Awesome-Linux-Software)   |       | Collection of Linux applications and tools                         |
| [Awesome Linux](https://awesomelinux.com/)                                           |       | Linux resources, tutorials, and news                               |
| [Awesome DevOps](https://github.com/wmariuss/awesome-devops)                         |       | DevOps tools, resources, and best practices                        |
| [Awesome DevOps (alt)](https://github.com/awesome-soft/awesome-devops)               |       | Another curated DevOps resources list                              |
| [Awesome Web Development](https://github.com/nepaul/awesome-web-development)         |       | Web development resources and tools                                |
| [Professional Programming](https://github.com/charlax/professional-programming)      | 50k+  | Curated reading list of essential SWE essays, books, and resources |
