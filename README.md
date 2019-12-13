# dockerfile-golang-build

ON BUILD golang and tools

useful for CI

- golang ( official golang image golang:X.Y.Z => netmarkjp/golang-build:X.Y.Z )
- [vgo](https://github.com/golang/vgo) ( golang 1.10+ )
- [dep](github.com/golang/dep/cmd/dep)
- [goimports](golang.org/x/tools/cmd/goimports)
- [golint](github.com/golang/lint/golint)
- [gox](github.com/mitchellh/gox)
- [goxz](github.com/Songmu/goxz/cmd/goxz) ( golang 1.13+ )
- [goverage](github.com/haya14busa/goverage)
- [delve](github.com/go-delve/delve)
