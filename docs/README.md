# Cloudflare Argo Tunnel搭建文档

Argo Tunnel是什么?(以下简称argo)

[官方文档](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps)

> Cloudflare Tunnel 为您提供了一种安全的方式，可以在没有公共可路由 IP 地址的情况下将资源连接到 Cloudflare。使用 Tunnel，您不会将流量发送到外部 IP ー相反，您的基础结构(cloud喇叭式)中的一个轻量级守护进程会创建到 Cloudflare 边缘的仅出站连接。Cloudflare Tunnel 可以安全地将 HTTP web 服务器、 SSH 服务器、远程桌面和其他协议连接到 Cloudflare。通过这种方式，你的起源可以服务通过 Cloudflare 的交通，而不会受到攻击，绕过 Cloudflare

简单来说就是argo为你创建了一个隧道,你可以直接通过内网来访问Cloudflare的CDN,并将服务运行到internet,除此之外还有别的协议

这是所有支持的协议

![image-20211208160724838](http://img.goojoe.cc/2021/12/08/kHn23eqo.png)



## 作用方向

- Minecraft服务器(还在研究)

- web服务

- SSH服务
- 其他

[开始搭建>>](1cloudflare/account)
