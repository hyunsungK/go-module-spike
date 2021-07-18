
# [Golang Module](https://golang.org/doc/tutorial/create-module)


## Replacing module
```shell
# replace domain to local path
$ go mod edit -replace example.com/greetings=../greetings
```

## tidy
```shell
# 의존성 모듈의 동기화 명령
$ go mod tidy
```

## Up & Running
```shell
$ go run .
```