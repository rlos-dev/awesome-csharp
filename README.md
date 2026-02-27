# Awesome C#

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome C# frameworks, libraries, tools, and resources.  
> Built for longevity and architectural rigor, focusing on modern, high-quality, and developer-friendly standards for enterprise software engineering.

---

## Contents

- [Language and Standards](#language-and-standards)
- [Development Environments](#development-environments)
- [Tools & Developer Experience (DX)](#tools--developer-experience-dx)
- [Architecture, Patterns & Distributed Systems](#architecture-patterns--distributed-systems)
- [Web, API & GraphQL](#web-api--graphql)
- [Data, ORM & Event Sourcing](#data-orm--event-sourcing)
- [Performance & Source Generators](#performance--source-generators)
- [Observability & Telemetry](#observability--telemetry)
- [Testing & Quality Assurance](#testing--quality-assurance)
- [Validation](#validation)
- [Background Jobs & Scheduling](#background-jobs--scheduling)
- [Security](#security)
- [Desktop & Cross-Platform](#desktop--cross-platform)
- [Game Development](#game-development)
- [AI and Machine Learning](#ai-and-machine-learning)
- [Best Practices](#best-practices)
- [Books and Tutorials](#books-and-tutorials)
- [Community](#community)
- [Miscellaneous](#miscellaneous)

---

## Language and Standards

- [C# Language Specification](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/language-specification/)
- [C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- [What's new in C#](https://learn.microsoft.com/en-us/dotnet/csharp/whats-new/)
- [C# Feature Proposals (Roslyn)](https://github.com/dotnet/csharplang)

---

## Development Environments

- [JetBrains Rider](https://www.jetbrains.com/rider/) – Fast, powerful, cross-platform .NET IDE.
- [Visual Studio](https://visualstudio.microsoft.com/) – The flagship IDE for Windows.
- [Visual Studio Code](https://code.visualstudio.com/) with the [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)

---

## Tools & Developer Experience (DX)

- [dotnet CLI](https://learn.microsoft.com/en-us/dotnet/core/tools/)
- [Husky.Net](https://alirezanet.github.io/Husky.Net/) – Git hooks made easy for .NET (pre-commit, pre-push, etc.).
- [SonarAnalyzer.CSharp](https://github.com/SonarSource/sonar-dotnet) – Static code analysis to detect bugs and code smells.
- [Cake](https://cakebuild.net/) – Build automation system.
- [LINQPad](https://www.linqpad.net/) – The ultimate .NET scratchpad and interactive querying tool.

---

## Architecture, Patterns & Distributed Systems

- [MediatR](https://github.com/jbogard/MediatR) – Simple, unambitious mediator implementation in .NET.
- [MassTransit](https://masstransit.io/) – The leading distributed application framework and message bus for .NET.
- [Polly](https://github.com/App-vNext/Polly) – Resilience and transient-fault-handling library (Retry, Circuit Breaker).
- [YARP (Yet Another Reverse Proxy)](https://microsoft.github.io/reverse-proxy/) – A highly customizable reverse proxy built on .NET.
- [Dapr (Distributed Application Runtime)](https://dapr.io/) – Portable, event-driven runtime for building distributed apps.
- [Orleans](https://dotnet.github.io/orleans/) – Cross-platform framework for building robust, scalable distributed applications using Virtual Actors.

---

## Web, API & GraphQL

- [ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/)
- [gRPC for .NET](https://grpc.io/docs/languages/csharp/) – High-performance Remote Procedure Call (RPC) framework.
- [HotChocolate](https://chillicream.com/docs/hotchocolate) – The ultimate GraphQL server for .NET.
- [Refit](https://github.com/reactiveui/refit) – The automatic type-safe REST library for .NET.
- [Blazor](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor)
- [SignalR](https://dotnet.microsoft.com/en-us/apps/aspnet/signalr)
- [OData](https://devblogs.microsoft.com/odata/) – Standard for creating and consuming RESTful APIs.

---

## Data, ORM & Event Sourcing

- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/) – Modern object-database mapper for .NET.
- [Dapper](https://github.com/DapperLib/Dapper) – High-performance Micro-ORM.
- [Marten](https://martendb.io/) – PostgreSQL as a Document Database and Event Store for .NET.

---

## Performance & Source Generators

- [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) – Powerful .NET library for benchmarking.
- [Riok.Mapperly](https://mapperly.riok.app/) – High-performance, source-generator based object mapper (Zero-reflection alternative to AutoMapper).
- [dotMemory](https://www.jetbrains.com/dotmemory/) & [dotTrace](https://www.jetbrains.com/profiler/) – Industry-standard memory and performance profiling tools.

---

## Observability & Telemetry

- [OpenTelemetry .NET](https://opentelemetry.io/docs/languages/net/) – The industry standard for distributed tracing, metrics, and logging.
- [Serilog](https://serilog.net/) – Simple .NET logging with fully-structured events.

---

## Testing & Quality Assurance

- [xUnit](https://xunit.net/) & [NUnit](https://nunit.org/) – The standard unit testing frameworks.
- [NSubstitute](https://nsubstitute.github.io/) – A friendly, modern substitute for .NET mocking libraries.
- [Testcontainers for .NET](https://dotnet.testcontainers.org/) – Throwaway instances of Docker containers for reliable integration testing.
- [Stryker.NET](https://stryker-mutator.io/docs/stryker-net/introduction/) – Mutation testing for .NET to truly validate test suite quality.
- [Playwright for .NET](https://playwright.dev/dotnet/) – Reliable end-to-end testing for modern web apps.
- [FluentAssertions](https://fluentassertions.com/) – Extensive set of extension methods that allow you to specify the expected outcome of tests naturally.
- [Bogus](https://github.com/bchavez/Bogus) – Simple and sane fake data generator.

---

## Validation

- [FluentValidation](https://docs.fluentvalidation.net/) – A popular .NET library for building strongly-typed validation rules.

---

## Background Jobs & Scheduling

- [Hangfire](https://www.hangfire.io/) – An easy way to perform background processing in .NET applications with a built-in dashboard.
- [Quartz.NET](https://www.quartz-scheduler.net/) – Enterprise-grade scheduling system for .NET.

---

## Security

- [OpenIddict](https://github.com/openiddict/openiddict-core) – Versatile OpenID Connect/OAuth 2.0 server framework (Modern alternative to IdentityServer).
- [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net)
- [AspNetCore.Authentication.JwtBearer](https://www.nuget.org/packages/Microsoft.AspNetCore.Authentication.JwtBearer/)

---

## Desktop & Cross-Platform

- [Avalonia UI](https://avaloniaui.net/) – The pixel-perfect, cross-platform UI framework for .NET.
- [.NET MAUI](https://learn.microsoft.com/en-us/dotnet/maui/) – Multi-platform App UI for creating native mobile and desktop apps.

---

## Game Development

- [Godot](https://godotengine.org/) – Open-source engine with first-class C# support.
- [Unity](https://unity.com/) – Popular game engine using C#.
- [MonoGame](https://www.monogame.net/) – Cross-platform game development.

---

## AI and Machine Learning

- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) – SDK to integrate Large Language Models (LLMs) with C# applications.
- [ML.NET](https://dotnet.microsoft.com/en-us/apps/machinelearning-ai/ml-dotnet) – Machine learning framework for .NET.
- [TorchSharp](https://github.com/dotnet/TorchSharp) – PyTorch bindings for .NET.

---

## Best Practices

- [Clean Architecture by Jason Taylor](https://github.com/jasontaylordev/CleanArchitecture)
- [C# Coding Guidelines (JetBrains)](https://github.com/JetBrains/Guidelines)
- [Framework Design Guidelines (Microsoft)](https://learn.microsoft.com/en-us/dotnet/standard/design-guidelines/)

---

## Books and Tutorials

- _C# 12 in a Nutshell_ – Joseph Albahari
- _C# in Depth_ – Jon Skeet
- _Software Architecture: The Hard Parts_ – Neal Ford, Mark Richards, Pramod Sadalage, Zhamak Dehghani
- [Microsoft Learn - C#](https://learn.microsoft.com/en-us/training/paths/csharp-first-steps/)

---

## Community

- [Reddit /r/dotnet](https://www.reddit.com/r/dotnet/)
- [Stack Overflow - C# tag](https://stackoverflow.com/questions/tagged/c%23)
- [Discord - .NET Foundation](https://discord.com/invite/dotnet)

---

## Miscellaneous

- [Sharplab.io](https://sharplab.io/) – .NET IL and JIT explorer.
- [Roslyn Compiler](https://github.com/dotnet/roslyn)
- [dotnet/interactive](https://github.com/dotnet/interactive) – Notebooks for .NET.

---

## Contributing

Contributions welcome! Please follow the [contribution guidelines](CONTRIBUTING.md) and make sure links are up-to-date, actively maintained, and adhere to high-quality engineering standards.

---

## License

[CC0-1.0](LICENSE)
