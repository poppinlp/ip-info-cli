# ip-info-cli

[![Build Status](https://travis-ci.org/poppinlp/ip-info-cli.png?branch=master)](https://travis-ci.org/poppinlp/ip-info-cli)
[![Dependency Status](https://david-dm.org/poppinlp/ip-info-cli.svg)](https://david-dm.org/poppinlp/ip-info-cli)
[![devDependency Status](https://david-dm.org/poppinlp/ip-info-cli/dev-status.svg)](https://david-dm.org/poppinlp/ip-infp-cli#info=devDependencies)

Get IP information include country, province, city and operator.

## Getting Started

Install with this command:

```shell
npm i ip-info-cli -g
```

Or maybe you like yarn:

```shell
yarn global add ip-info-cli
```

## How to use

This package is a CLI for [ip-info](https://github.com/poppinlp/ip-info).

So you could use all [config](https://github.com/poppinlp/ip-info#config) in that package and have fun!

## Samples

### Basic

```shell
ip-info --ip xxx.xxx.xxx.xxx
```

### More config

```shell
ip-info --input /path/to/input.yml --output /path/to/output.yml --format yml --inverval 500
```

## Test

```shell
npm test
```

## History

- 0.0.1
    - init
