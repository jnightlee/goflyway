# goflyway, HTTP tunnel in Go

![](https://raw.githubusercontent.com/coyove/goflyway/gdev/.misc/logo.png)

goflyway is an end-to-end encrypted HTTP/SOCKS5 proxy client/server written in golang, featuring:

1. TCP tunneling
2. TCP tunneling over WebSocket
3. Multiplex connections
4. Man-in-the-middle
5. UDP over TCP (SOCKS5)
6. SS compatible ACL rules
7. Serve as an HTTP reverse proxy

For more info, please refer to the following links.

[中文](https://github.com/coyove/goflyway/wiki/%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B) / [English](https://github.com/coyove/goflyway/wiki/Getting-Started)

## Android Client

[shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/) is an Android client for shadowsocks. By replacing the native libss-local.so in /lib with goflyway's executable, we borrow its frontend to run our proxy on Android. Check this [wiki](https://github.com/coyove/goflyway/wiki/Android-%E5%AE%A2%E6%88%B7%E7%AB%AF) for details.