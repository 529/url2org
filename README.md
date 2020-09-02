# url2org

### What can be done
```
# from
https://www.yahoo.co.jp

# to
[[https://www.yahoo.co.jp][Yahoo! JAPAN]]
```

### memo
```
$ brew install go
$ go version
go version go1.15 darwin/amd64

$ go get golang.org/x/net/html
$ go run src/title.go https://www.yahoo.co.jp
[[https://www.yahoo.co.jp][Yahoo! JAPAN]]

$ go build ../src/title.go
$ ./title https://www.yahoo.co.jp
[[https://www.yahoo.co.jp][Yahoo! JAPAN]]
```
