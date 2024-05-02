# cf-wkrs-pages-vless

在 CloudFlare Workers 或 Pages 部署 vless 节点，支持 Base64、Clash 及 Sing-box 配置文件订阅文件生成

## 使用方法

- 访问 https://a.sub.workers.dev/d342d11e-d424-4583-b36e-524ab1f0afa4 ，即可查看节点明文配置信息
- 访问 https://a.sub.workers.dev/d342d11e-d424-4583-b36e-524ab1f0afa4/base64 ，即可使用 Base64 通用客户端订阅
- 访问 https://a.sub.workers.dev/d342d11e-d424-4583-b36e-524ab1f0afa4/clash ，即可使用 Clash 节点订阅
- 访问 https://a.sub.workers.dev/d342d11e-d424-4583-b36e-524ab1f0afa4/sb ，即可使用 Sing-box 节点订阅

> 提示：`https://a.sub.workers.dev/` 为瞎编的 Workers 或 Pages 部署地址，请修改为自己实际部署的地址；`d342d11e-d424-4583-b36e-524ab1f0afa4` 为项目默认的 UUID，请在实际部署的时候在代码文件的第 6 行处，修改为自己生成的 UUID

## 部署教程

- Workers 教程地址：https://blog.misaka.rest/2023/07/29/cf-wkrs-vless/
- Pages 教程地址：https://blog.misaka.rest/2023/07/29/cf-pages-vless/

## 鸣谢项目

- zizifn：https://github.com/zizifn/edgetunnel
- 3Kmfi6HP：https://github.com/3Kmfi6HP/EDtunnel
- cmliu：https://github.com/cmliu/edgetunnel

## 注意事项

1. 由于 Workers 节点的 IP 变动频繁，因此请勿在此节点登录重要账号
2. 由于 pages.dev 域名默认启用了 HSTS，所以无法使用非 TLS 端口的节点
3. 请勿滥用！

## 赞助

爱发电：https://afdian.net/a/Misaka-blog

![afdian-MisakaNo の 小破站](https://user-images.githubusercontent.com/122191366/211533469-351009fb-9ae8-4601-992a-abbf54665b68.jpg)