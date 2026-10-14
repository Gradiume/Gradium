<div align="center">
  <h1>Gradium</h1>
  <p><em>A fork of the Gradle build tool</em></p>
</div>

> **Gradium is an independent fork of [Gradle](https://github.com/gradle/gradle), licensed under the Apache License 2.0. Not affiliated with or endorsed by Gradle Inc.**

## About

Gradium is a highly scalable build automation tool designed to handle everything from large, multi-project enterprise builds to quick development tasks across various languages. Its modular, performance-oriented architecture integrates with development environments, making it a solution for building, testing, and deploying applications on **Java**, **Kotlin**, **Scala**, **Android**, **Groovy**, **C++**, and **Swift**.

This fork tracks upstream Gradle and layers on top of it the changes documented in the [`NOTICE`](NOTICE) file and in the commit history.

---

## Getting Started

- **Installation**: build from source with `./gradlew :distributions-full:binZip`, or use the wrapper (`./gradlew`) directly.
- **Requirements**: JDK 17+ for running the build; see [`CONTRIBUTING.md`](CONTRIBUTING.md) for details.
- **Samples**: sample projects for Java, Kotlin, Scala, Android, Groovy, C++, and Swift live under [`subprojects/docs/src/samples`](subprojects/docs/src/samples).

---

## Building Gradium from Source

```bash
git clone https://github.com/Gradiume/Gradium.git
cd Gradium
./gradlew :distributions-full:binZip
```

The resulting distribution zip is under [`packaging/distributions-full/build/distributions/`](distributions).

---

## IDE & CI Integration

Gradium, like upstream Gradle, works with common IDEs and CI systems. Because it keeps upstream's plugin API, existing Gradle plugins and IDE integrations continue to resolve against the internal `org.gradle.*` packages.

---

## Documentation

Upstream Gradle's user manual applies to Gradium for the parts of the build tool that have not been rebranded yet. See .

Once Gradium diverges further, its own docs will live in this repository under [`subprojects/docs/`](docs).

---

## Contributing

- See [`CONTRIBUTING.md`](CONTRIBUTING.md).
- See [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) if present, otherwise upstream Gradle's Code of Conduct applies for the inherited parts.
- Open issues and PRs at [Issues](https://github.com/Gradiume/Gradium/issues).

---

## License

Licensed under the Apache License, Version 2.0. See [`LICENSE`](LICENSE) and [`NOTICE`](NOTICE).

Third-party attributions bundled with the full distribution are preserved at [`packaging/distributions-full/src/toplevel/NOTICE`](NOTICE).
