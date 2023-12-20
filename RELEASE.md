# Release

https://www.youtube.com/watch?v=4C3CsGxSsw0

## Create `main.go` file

```go
// main.go
package main

func main() {
    println("Ba dum, tss!")
}
```

## Initialize module
```bash
go mod init live-server
```

## Initialize `goreleaser`

```bash
goreleaser init
```

## Export `Git token`

```bash
export GITHUB_TOKEN=ghp_3iruw82kenoi23o2kjr2uh3kdjh
```

## Local release (local-only)

```bash
goreleaser release --snapshot --clean

Or
goreleaser release --snapshot --rm-dist
```

## Check folder `dist`

## Create tag `0.0.1` and release

```bash
git tag -a 0.0.1
goreleaser --rm-dist
```


