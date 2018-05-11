craftsman
=========



[![Version](https://img.shields.io/npm/v/craftsman.svg)](https://npmjs.org/package/craftsman)
[![CircleCI](https://circleci.com/gh/MunNaaS/craftsman/tree/master.svg?style=shield)](https://circleci.com/gh/MunNaaS/craftsman/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/MunNaaS/craftsman?branch=master&svg=true)](https://ci.appveyor.com/project/MunNaaS/craftsman/branch/master)
[![Codecov](https://codecov.io/gh/MunNaaS/craftsman/branch/master/graph/badge.svg)](https://codecov.io/gh/MunNaaS/craftsman)
[![Downloads/week](https://img.shields.io/npm/dw/craftsman.svg)](https://npmjs.org/package/craftsman)
[![License](https://img.shields.io/npm/l/craftsman.svg)](https://github.com/MunNaaS/craftsman/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g craftsman
$ craftsman COMMAND
running command...
$ craftsman (-v|--version|version)
craftsman/0.0.0 linux-x64 node-v10.1.0
$ craftsman --help [COMMAND]
USAGE
  $ craftsman COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`craftsman hello [FILE]`](#craftsman-hello-file)
* [`craftsman help [COMMAND]`](#craftsman-help-command)

## `craftsman hello [FILE]`

describe the command here

```
USAGE
  $ craftsman hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ craftsman hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/MunNaaS/craftsman/blob/v0.0.0/src/commands/hello.ts)_

## `craftsman help [COMMAND]`

display help for craftsman

```
USAGE
  $ craftsman help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v1.2.10/src/commands/help.ts)_
<!-- commandsstop -->
