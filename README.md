# Go Jack, the HandeyBot

Command line based SLackbot written in Go

## Install

```shell
$ go get -u github.com/ryanhatfield/handeybot
$ go install github.com/ryanhatfield/handeybot
```

## Usage

```shell
# set token from https://api.slack.com/web and send quote
$ handeybot -token "xxxx-xxxxxxxxx-xxxx"

# get token from 'SLACK_TOKEN' environment variable and send quote to #general
$ handeybot -channel "#general"
```
