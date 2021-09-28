# exert-anyproxy

## 简单地启用代理

```bash
# 全局安装 anyproxy 代理服务器
npm i -g anyproxy

# 指定端口启动代理
anyproxy --port 8001
# 启动代理后设置系统代理到 anyproxy
# 此时会在 8002 启动一个 web 的管理网站
# web 管理站可以下载到 CA 证书
# 将证书安装为 受信任的根授权机构
# windows 下双击证书安装
```

## 使用 node 代码启动代理

参考项目里面的 js 代码
