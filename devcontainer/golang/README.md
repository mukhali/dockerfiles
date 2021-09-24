# webvpn
A WebVPN for access to internal resource.

export GOPROXY=https://goproxy.io

```
go env -w GO111MODULE=on
go env -w GOPROXY=https://goproxy.cn,direct

go env -w GOPROXY=https://goproxy.io,direct

GOPROXY="https://proxy.golang.org,direct"
```
go mod download

go get -u -v github.com/fsnotify/fsnotify v1.4.9

go build main.go


# go mod 

```
go mod init  # 初始化go.mod
go mod tidy  # 更新依赖文件
go mod download  # 下载依赖文件
go mod vendor  # 将依赖转移至本地的vendor文件
go mod edit  # 手动修改依赖文件
go mod graph  # 打印依赖图
go mod verify  # 校验依赖
```

