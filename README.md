# AI Dependency Advisor

![CI](https://github.com/Qyroxen/AI-Dependency-Advisor/actions/workflows/ci.yml/badge.svg)
![CodeQL](https://github.com/Qyroxen/AI-Dependency-Advisor/actions/workflows/codeql.yml/badge.svg)
![Go](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Stars](https://img.shields.io/github/stars/Qyroxen/AI-Dependency-Advisor?style=social)
![Issues](https://img.shields.io/github/issues/Qyroxen/AI-Dependency-Advisor)
![PRs](https://img.shields.io/github/issues-pr/Qyroxen/AI-Dependency-Advisor)

> A production-ready CLI tool built with Go

[![Star Badge](https://img.shields.io/github/stars/Qyroxen/AI-Dependency-Advisor?style=social)](https://github.com/Qyroxen/AI-Dependency-Advisor/stargazers)

## What is it?

AI Dependency Advisor is a production-ready CLI tool built with Go. It provides powerful functionality with a beautiful terminal interface.

## Features

- Fast and efficient (written in Go)
- Beautiful CLI with colored output
- Comprehensive documentation
- GitHub Actions CI/CD
- CodeQL security analysis
- Dependabot for dependency updates
- MIT Licensed
- Fully offline - zero cloud dependency

## Quick Start

```bash
# Install
git clone https://github.com/Qyroxen/AI-Dependency-Advisor.git
cd AI-Dependency-Advisor
go build -o aidependencyadvisor .

# Run
./aidependencyadvisor --help
```

## CLI Usage

```bash
# Basic usage
./aidependencyadvisor

# With flags
./aidependencyadvisor --verbose --output json

# Get help
./aidependencyadvisor --help
```

## Examples

```bash
# Example 1
./aidependencyadvisor example1

# Example 2
./aidependencyadvisor example2 --flag value
```

## Development

```bash
# Run tests
go test ./...

# Build
go build -o aidependencyadvisor .

# Lint
golangci-lint run

# Security scan
codeql analyze
```

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Security

For security vulnerabilities, please see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/Qyroxen/AI-Dependency-Advisor/stargazers">
    <img src="https://img.shields.io/github/stars/Qyroxen/AI-Dependency-Advisor?style=social" alt="Star this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Dependency-Advisor/forks">
    <img src="https://img.shields.io/github/forks/Qyroxen/AI-Dependency-Advisor?style=social" alt="Fork this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Dependency-Advisor/issues">
    <img src="https://img.shields.io/github/issues/Qyroxen/AI-Dependency-Advisor" alt="Issues">
  </a>
  <a href="https://github.com/Qyroxen/AI-Dependency-Advisor/pulls">
    <img src="https://img.shields.io/github/issues-pr/Qyroxen/AI-Dependency-Advisor" alt="Pull Requests">
  </a>
</p>
