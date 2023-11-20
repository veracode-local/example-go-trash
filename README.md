# [:] Example Go project using Trash.

An example Go project using Trash package manager to demonstrate [SourceClear](https://www.sourceclear.com) scans.

## Install and activate SourceClear
Follow the instructions under the section "Setup and Configuration" in https://www.sourceclear.com/docs/command-line-interface/ to install and activate our SourceClear agent.

## Scan this project
There are 2 ways to scan this project.

### 1. Using url option
`SRCCLR_FORCE_GO_INSTALL=true srcclr scan --url https://github.com/srcclr/example-go-trash`

### 2. On local path
```
1. git clone https://github.com/srcclr/example-go-trash/ $GOPATH/src/github.com/srcclr/example-go-trash/
2. srcclr scan $GOPATH/src/github.com/srcclr/example-go-trash/
```
test 123
