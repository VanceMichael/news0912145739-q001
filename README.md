# 冰雪活动服务

这是一个 Go 后端工程的起始目录，负责接收活动报名并维护场馆场次数据。运行参数从环境变量读取，默认使用本地 SQLite 文件。接口约定和测试数据放在 `docs` 与 `testdata` 目录，服务只提供 HTTP 接口。

## 本地运行

```bash
go test ./...
go run ./cmd/server
```

容器构建使用仓库内的 Dockerfile。
