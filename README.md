# sandbox-go

## 準備

```
$ brew install goenv
$ goenv install 1.10.1
$ goenv global 1.10.1
$ brew install dep
$ mkdir sandbox-go
$ echo 'export GOPATH=$(pwd)' > .envrc
$ direnv allow
$ cd sandbox-go
$ mkdir -p src/sandbox
$ dep init
```

## 実行

```
$ cd src/sandbox
$ go run sandbox.go
```

## テスト

```
$ cd src/sandbox
$ go test
```
