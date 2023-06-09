# Noob-Logger

[![Go Reference](https://pkg.go.dev/badge/github.com/dimasbagussusilo/nb-go-logger.svg)](https://pkg.go.dev/github.com/dimasbagussusilo/nb-go-logger)
![GitHub go.mod Go version (subdirectory of monorepo)](https://img.shields.io/github/go-mod/go-version/dimasbagussusilo/nb-go-logger?style=flat-square)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/dimasbagussusilo/nb-go-logger?style=flat-square)

Noob Logger is a boiler plate for logging. It has features, such:
- Read log config from ENV
- Logger naming for distinguish where the log came from

Noob Logger use [Logger v1.8.1](github.com/sirupsen/logrus) as logging backend. Thanks to [*godotenv*](github.com/joho/godotenv)**

## Contents

- [Noob-Logger](#Noob-Logger)
  - [Installation](#Installation)
  - [Quick Start & Usage](#Quick)

## Installation

To install this package, you need to install Go (**version 1.17+ is required**) & initiate your Go workspace first.

1. After you initiate your workspace then you can install this package with below command.

```shell
go get -u github.com/dimasbagussusilo/nb-go-logger
```

2. Import it in your code

```go
import "github.com/dimasbagussusilo/nb-go-logger"
```

## Quick Start & Usage

Logger will read following ENV:

| Key | Description | Value |
|----|----|----|
| LOG_LEVEL | Filtering log based on level | String. Values: `debug`, `error`, `info`, `warn` |
| LOG_FORMAT | Formatting log | String. Values: `console`, `json` |
| | | |

## Contributors ##

- Dimas Bagus Susilo <dimasbagussusilo@gmail.com>

## License

This project is licensed under the - see the [LICENSE.md](LICENSE.md) file for details