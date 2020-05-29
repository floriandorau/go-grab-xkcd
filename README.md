# go-grab-xkcd

Simple Go command line app for fetching [XKCD](https://xkcd.com/) comics.

This repo is based on the tutorial [Diving into Go by building a CLI application](https://eryb.space/2020/05/27/diving-into-go-by-building-a-cli-application.html)

## Run it

You can run it with

```bash
go run main.go -n 323 -o json
```

## Build & run it

In order to build an executable and run it you can do thhe following

```bash
go build .
./go-grab-xkcd -n 323 -s -o json
```

To see all commands you can run `go-grab-xkcd --help`
