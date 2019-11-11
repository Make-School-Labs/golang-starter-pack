# Golang Starter Pack

[![Go Report Card](https://goreportcard.com/badge/github.com/make-school-labs/golang-starter-pack)](https://goreportcard.com/report/github.com/make-school-labs/golang-starter-pack)
[![Build Status](https://travis-ci.org/make-school-labs/golang-starter-pack.svg?branch=master)](https://travis-ci.org/make-school-labs/golang-starter-pack)

Golang/Echo codebase containing real world examples that adhere to the [RealWorld](https://github.com/gothinkster/realworld) spec and API.

This codebase was created to demonstrate a fully fledged full-stack application built with **Golang, Echo, and Gorm**.

## Features

- CRUD operations
- Authentication
- Routing
- Pagination
- ...and more!

## Requirements

- Golang v1.11+: [Installation Guide](https://golang.org/doc/install)
- `dep`: [Installation Guide](https://golang.github.io/dep/docs/installation.html)

## Getting Started

### Clone the Repository

Clone this repository:

```bash
$ git clone https://github.com/make-school-labs/golang-starter-pack.git ~/go/src/PROJECT_NAME_HERE

$ cd ~/go/src/PROJECT_NAME_HERE
```

### Install Dependencies

```bash
$ export GO111MODULE=on;

$ go mod download
```

### Run

```bash
$ go run main.go
```

### Build

```bash
$ go build
```

### Tests

```bash
$ go test ./...
```

## Credits

Based on [`xesina/golang-echo-realworld-example-app`](https://github.com/xesina/golang-echo-realworld-example-app) on GitHub.
