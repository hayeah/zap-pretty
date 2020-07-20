# zap-pretty

Forked from github.com/maoueh/zap-pretty

To pretty print lotus JSON logs.

## Install

```sh
$ go get -u github.com/hayeah/zap-pretty
```

## Usage

Can pipe from stdout,

```sh
cat json.log | zap-pretty
```

Or format a file

```sh
zap-pretty json.log
```
