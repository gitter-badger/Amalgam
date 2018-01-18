# amctl

[![](https://img.shields.io/badge/Powered%20by-Canfly%20LLP-blue.svg?style=flat-square)](https://canfly.org)
[![](https://img.shields.io/badge/Project-Amalgam-blue.svg?style=flat-square)](http://amal.ga)

[Amalgam Repo](https://github.com/Canfly/Amalgam) • [Gitter](http://gitter.im/Canfly/Amalgam)


[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![GoDoc](https://godoc.org/github.com/ipfs/go-ipfs?status.svg)](https://godoc.org/github.com/ipfs/go-ipfs)
[![Build Status](https://travis-ci.org/ipfs/go-ipfs.svg?branch=master)](https://travis-ci.org/ipfs/go-ipfs)

[![Throughput Graph](https://graphs.waffle.io/ipfs/go-ipfs/throughput.svg)](https://waffle.io/ipfs/go-ipfs/metrics/throughput)

> Amalgam Command Line Tools

Amalgam is a Peer-To-Peer Social Network and Media Ecosystem. 

## Usage

```
  amctl - Global p2p merkle-dag filesystem.

  amctl [<flags>] <command> [<arg>] ...

SUBCOMMANDS
  BASIC COMMANDS
    init          Initialize local node
    add  <object> Add a object to Amalgam

  ADVANCED COMMANDS
    daemon        Start a daemon process
    name <name>   Resolve or publish any type of name from ANS

  NETWORK COMMANDS
    id            Show info about nodeof a connection
    diag          Print diagnostics

  TOOL COMMANDS
    config        Manage configuration
    version       Show amctl version information
    commands      List all available commands

  Use 'amctl help <command> ' to learn more about each command.

  Amalgam uses a system disk. By default, the repo is located  at ~/.am
  To change the repo location, set the $AMPATH environment variable:

  bash: export AMPATH=/path/to/repo
  fish: set -gx AMPATH "/path/to/repo"
```