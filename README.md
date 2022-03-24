# uuu-cli

`uuu-cli` is a scaffolding solution that includes project initialization, Git integration, ONE-click deployment of OSS and CDN.

[![CI](https://github.com/uuuhds/uuu-cli/actions/workflows/ci.yml/badge.svg)](https://github.com/uuuhds/uuu-cli/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/uuuhds/uuu-cli/branch/main/graph/badge.svg?token=2L02H8SW6Y)](https://codecov.io/gh/uuuhds/uuu-cli)

## Why?

In the process of our development, we often encounter some repetitive labor. Repeated labor is prone to errors and redundant workload. We use scaffolding to reduce the workload due to human reasons and allow more time for development. Do meaningful things.

## Installation
```bash
npm install -g uuu-cli
```

## Usage

```bash
➜ uuu

Usage: uuu <command> [options]

A scaffolding for an engineered solution

Options:
  -d, --debug          Whether to enable debugging mode (default: false)
  -l, --local <local>  Specify the local debug file path (default: "")
  -V, --version        output the version number
  -h, --help           display help for command

Commands:
  init [options]       Initialize a project
  help [command]       display help for command
```

