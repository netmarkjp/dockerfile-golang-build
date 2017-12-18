# dockerfile-golang-build

ON BUILD golang and tools

useful for CI

- golang ( official golang image golang:X.Y.Z => netmarkjp/golang-build:X.Y.Z )
- [dep](github.com/golang/dep/cmd/dep)
- [goimports](golang.org/x/tools/cmd/goimports)
- [golint](github.com/golang/lint/golint)
- [gox](github.com/mitchellh/gox)
