# Go Playground Client

This is a client of [Go Playground](https://play.golang.org).

## Use as CLI

### Install

```
$ go get github.com/tenntenn/goplayground/cmd/gp
```

### Usage

```
$ gp help
```

### Run

```
$ gp run main.go
```

```
$ gp run a.go b.go
```

```
$ find . -type f | xargs gp run
```

### Format

```
$ gp fomrat [-imports] main.go
```

```
$ gp format a.go b.go
```

```
$ find . -type f | xargs gp format
```

### Share

```
$ gp share main.go
```

```
$ gp share a.go b.go
```

```
$ find . -type f | xargs gp share
```

### Download

```
$ gp download https://play.golang.org/p/sTkdodLtokQ
```

```
$ gp dl https://play.golang.org/p/sTkdodLtokQ
```

```
$ gp dl -dldir=output https://play.golang.org/p/sTkdodLtokQ
```

## Use as a libary

See: https://godoc.org/github.com/tenntenn/goplayground
