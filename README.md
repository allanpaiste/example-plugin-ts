@oclif/example-plugin-ts
========================

example dxcli plugin in typescript

[![Version](https://img.shields.io/npm/v/@oclif/example-plugin-ts.svg)](https://npmjs.org/package/@oclif/example-plugin-ts)
[![CircleCI](https://circleci.com/gh/oclif/example-plugin-ts/tree/master.svg?style=svg)](https://circleci.com/gh/oclif/example-plugin-ts/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/example-plugin-ts?branch=master&svg=true)](https://ci.appveyor.com/project/heroku/example-plugin-ts/branch/master)
[![Codecov](https://codecov.io/gh/oclif/example-plugin-ts/branch/master/graph/badge.svg)](https://codecov.io/gh/oclif/example-plugin-ts)
[![Greenkeeper](https://badges.greenkeeper.io/oclif/example-plugin-ts.svg)](https://greenkeeper.io/)
[![Known Vulnerabilities](https://snyk.io/test/npm/@oclif/example-plugin-ts/badge.svg)](https://snyk.io/test/npm/@oclif/example-plugin-ts)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/example-plugin-ts.svg)](https://npmjs.org/package/@oclif/example-plugin-ts)
[![License](https://img.shields.io/npm/l/@oclif/example-plugin-ts.svg)](https://github.com/oclif/example-plugin-ts/blob/master/package.json)

<!-- install -->
# Installing @oclif/example-plugin-ts

with yarn:
```
$ yarn global add @oclif/example-plugin-ts
```

or with npm:
```
$ npm install -g @oclif/example-plugin-ts
```
<!-- installstop -->
<!-- usage -->
# Usage

```sh-session
$ @oclif/example-plugin-ts COMMAND
running command...
$ @oclif/example-plugin-ts (-v|--version|version)
@oclif/example-plugin-ts/1.1.0 (linux-x64) node-v9.5.0
$ @oclif/example-plugin-ts --help [COMMAND]
USAGE
  $ @oclif/example-plugin-ts COMMAND [OPTIONS]
...
```
<!-- usagestop -->
<!-- commands -->
# Commands

* [@oclif/example-plugin-ts hello [FILE] [OPTIONS]](#hello)
## hello [FILE] [OPTIONS]

```
USAGE
  $ @oclif/example-plugin-ts hello [FILE] [OPTIONS]

ARGUMENTS
  FILE  file to output

OPTIONS
  -f, --force
  -n, --name=name  name to print

DESCRIPTION
  Describe the command here
  ...
  Extra documentation goes here


EXAMPLES
  $ example-plugin-ts hello
  hello world from hello!

  $ example-plugin-ts hello --name myname
  hello myname from hello!

  $ example-plugin-ts hello file outputs "hello world!" to file
  $ example-plugin-ts hello --force
  $ example-plugin-ts hello --help
```

_See code: [@oclif/example-plugin-ts](https://github.com/oclif/example-plugin-ts/blob/v1.1.0/src/commands/hello.ts)_
<!-- commandsstop -->
