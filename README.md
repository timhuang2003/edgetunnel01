# Edge Tunnel

这是一种基于CF Pages的免费代理方案, 不依赖外部订阅转换, 精简配置, 适合新手使用

**欢迎各位大佬指正代码中存在的问题！** 

[![Stargazers over time](https://starchart.cc/ImLTHQ/edgetunnel.svg?variant=adaptive)](https://starchart.cc/ImLTHQ/edgetunnel)

如果觉得本项目对您有帮助, 请点个 Star 支持一下！

## 使用方法

请确保您已注册 GitHub 和 Cloudflare账号

1. **Fork 本项目** 
2. **创建 Pages**
5. **添加环境变量**
6. **保存并部署**
8. **生效后导入订阅**

<details>
<summary><code><strong>「 建议做的 」</strong></code></summary>

**设置 GitHub Action 同步上游仓库**
1. 来到您 Fork 的仓库
2. 在 `Actions` 选项卡中, 点击 `Enable workflow`, 选择 `上游同步`
3. 启用此 Workflow 可以使您的仓库与作者的更新保持同步
</details>

## 变量说明

| 变量名 | 示例值 | 备注 |
| - | - | - |
| `SUB_PATH` | `sub` | 订阅地址:`地址/订阅路径`,  订阅路径换成`UUID`同样有效 | 
| `TXT_URL` | `https://raw.domain.com/AutoTest.txt` | 优选 IP, 格式`地址:端口#节点名称`端口不填默认 443, 节点名称不填使用默认名称 |
| `PROXY_IP` | `ts.hpc.tw:443` | 反代服务器 IP 地址和端口, 端口不填默认443 |
| `SOCKS5` | `账号:密码@地址:端口` | SOCKS5 代理 |
| `SOCKS5_GLOBAL` | `true` | 全局 SOCKS5 代理 |

<details>
<summary><code><strong>「 第三方 ProxyIP 」</strong></code></summary>

有能力请自建

- `ts.hpc.tw`
- `ProxyIP.US.CMLiussss.net`
- `ProxyIP.SG.CMLiussss.net`
- `ProxyIP.JP.CMLiussss.net`
- `ProxyIP.HK.CMLiussss.net`
- `ProxyIP.KR.CMLiussss.net`
- `ProxyIP.DE.tp2024.CMLiussss.net`
- `ProxyIP.Aliyun.CMLiussss.net`
- `ProxyIP.Oracle.CMLiussss.net`
- `ProxyIP.DigitalOcean.CMLiussss.net`
- `ProxyIP.Vultr.CMLiussss.net`
- `ProxyIP.Multacom.CMLiussss.net`
</details>

## 已适配客户端

- v2ray
- clash

## 免责声明

本免责声明适用于 GitHub 上的 "edgetunnel" 项目 (以下简称"本项目"), 项目链接为`https://github.com/ImLTHQ/edgetunnel`

**用途**

- 本项目仅供教育、研究和安全测试目的而设计和开发
- 旨在为安全研究人员、学术界人士及技术爱好者提供一个探索和实践网络通信技术的工具

**合法性**

- 在下载和使用本项目代码时, 必须遵守使用者所适用的法律和规定使用者有责任确保其行为符合所在地区的法律框架、规章制度及其他相关规定

**免责**

- 作为本项目的 **二次开发作者** (以下简称“作者”), 我 **ImLTHQ** 强调本项目仅应用于合法、道德和教育目的
- 作者不认可、不支持亦不鼓励任何形式的非法使用如果发现本项目被用于任何非法或不道德的活动, 作者将对此强烈谴责
- 作者对任何人或组织利用本项目代码从事的任何非法活动不承担责任使用本项目代码所产生的任何后果, 均由使用者自行承担
- 作者不对使用本项目代码可能引起的任何直接或间接损害负责
- 为避免任何意外后果或法律风险, 使用者应在使用本项目代码后的 24 小时内删除代码

通过使用本项目代码, 使用者即表示理解并同意本免责声明的所有条款如使用者不同意这些条款, 应立即停止使用本项目

作者保留随时更新本免责声明的权利, 且不另行通知最新版本的免责声明将发布在本项目的 GitHub 页面上

## 感谢

- [cmliu](https://github.com/cmliu) 参考代码和ProxyIP提供者
- [XIU2](https://github.com/XIU2) CF测速
- [zizifn](https://github.com/zizifn) 原作者
