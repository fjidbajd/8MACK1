
# 一、项目介绍

## 核心

- Xray-core
- sing-box

## 协议

> 以下均使用TLS，支持多种协议组合

- VLESS(Reality、Vision(TCP)、WS、gRPC)
- VMess(TCP、WS、HTTPUpgrade)
- Trojan(TCP、gRPC)
- Hysteria2(sing-box)
- Tuic(sing-box)
- NaiveProxy(sing-box)

## 功能

- 支持不同核心之间的配置读取
- 支持个性化安装单个协议
- [支持无域名版本的VLESS Reality搭建](https://www.v2ray-agent.com/archives/1708584312877)
- [支持多种分流用于解锁（wireguard、IPv6、Socks5、DNS、VMess(ws)、SNI反向代理）](https://www.v2ray-agent.com/archives/ba-he-yi-jiao-ben-yu-ming-fen-liu-jiao-cheng)
- [支持批量添加CDN节点并配合ClashMeta自动优选](https://www.v2ray-agent.com/archives/1684858575649)
- 支持普通证书和通配符证书自动申请及更新
- [支持订阅以及多VPS组合订阅](https://www.v2ray-agent.com/archives/1681804748677)
- 支持批量新增端口[仅支持Xray-core]
- 支持核心的升级以及回退
- 支持自主更换伪装站点
- 支持BT下载管理以及域名黑名单管理

# 二、使用指南

- [八合一脚本从入门到精通](https://www.v2ray-agent.com/archives/1710141233)
- [脚本快速搭建教程](https://www.v2ray-agent.com/archives/1682491479771)
- [垃圾VPS大救星，hysteria2最新协议一键搭建](https://www.v2ray-agent.com/archives/1697162969693)
- [Tuic V5性能提升及使用方法](https://www.v2ray-agent.com/archives/1687167522196)
- [Cloudflare优选IP、自动选择最快节点教程](https://www.v2ray-agent.com/archives/1684858575649)
- [脚本使用注意事项](https://www.v2ray-agent.com/archives/1679931532764)
- [脚本异常处理](https://www.v2ray-agent.com/archives/1684115970026)

