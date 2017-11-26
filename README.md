# go socks5 server

基于 go 于 socks5 协议的，简单穿墙服务实践

[wikipedia socks5 协议内容](https://zh.wikipedia.org/wiki/SOCKS)

### 功能点

- [x] 域名代理
- [ ] ipv4, ipv6代理
- [x] handshake 阶段
- [ ] auth 验证
- [x] request 阶段
- [x] 双关通信
- [ ] 双关通信，包引入加密算法


### 启动

```sh
go run main.go
```

### macOS `socks5` 代理

![pic](media/socks5_mac_set.jpeg)