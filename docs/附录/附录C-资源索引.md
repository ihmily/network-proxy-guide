# 附录C：资源索引

本附录提供项目与标准文档的检索入口，**不是对某个版本、服务商或付费方案的实时推荐**。项目所有者、下载位置、维护状态和价格可能变化；使用前应从项目自己的发布页核对版本、平台支持、签名或校验值，并记录核对日期。旧教程中的名称相似应用和镜像站点不能直接视为同一项目。

## C.1 协议、核心与安装文档

| 项目 | 检索入口 | 核对重点 |
|------|----------|----------|
| Xray-core | [项目仓库](https://github.com/XTLS/Xray-core)、[安装脚本仓库](https://github.com/XTLS/Xray-install) | 核心与安装器分别核对；配置格式和版本要匹配 |
| mack-a v2ray-agent | [项目仓库](https://github.com/mack-a/v2ray-agent) | 交互式部署Xray，核对脚本与支持系统 |
| 233boy Xray | [项目仓库](https://github.com/233boy/Xray) | 区分当前Xray脚本和旧V2Ray脚本 |
| V2Fly / V2Ray | [项目仓库](https://github.com/v2fly/v2ray-core) | 不把Xray配置直接当作V2Fly配置 |
| Trojan-Go | [项目仓库](https://github.com/p4gefau1t/trojan-go) | 从发布页获取程序，区分其他Trojan实现 |
| mihomo | [项目仓库](https://github.com/MetaCubeX/mihomo) | 核心版本、规则和DNS字段 |
| Shadowsocks Rust | [项目仓库](https://github.com/shadowsocks/shadowsocks-rust) | 密码格式、服务端与客户端版本 |
| Hysteria | [项目仓库](https://github.com/apernet/hysteria) | 区分主要版本及其配置语法 |
| WireGuard | [官方网站](https://www.wireguard.com/)、[快速入门](https://www.wireguard.com/quickstart/) | 系统支持、密钥和路由配置 |
| WireGuard installer | [脚本仓库](https://github.com/angristan/wireguard-install) | 使用前核对脚本、监听端口和客户端配置 |

这些入口只用于定位项目，不表示已验证当前发布版或适合具体环境。第4章讨论协议与实现的区别，第11章说明安装脚本的审查流程。

## C.2 客户端与界面

| 项目 | 检索入口 | 使用前检查 |
|------|----------|------------|
| Clash Verge Rev | [项目仓库](https://github.com/clash-verge-rev/clash-verge-rev) | 发布者、目标系统、所用核心与更新说明 |
| v2rayN | [项目仓库](https://github.com/2dust/v2rayN) | 平台和所选核心的版本关系 |
| v2rayNG | [项目仓库](https://github.com/2dust/v2rayNG) | 应用发布者、安装来源与权限 |
| Shadowrocket | [应用商店页面](https://apps.apple.com/app/id932747118) | 开发者、地区可用性、价格与配置格式 |

### 服务器面板与订阅前台

| 项目 | 项目地址 | 定位与使用前检查 |
|------|----------|------------------|
| 3X-UI | [MHSanaei/3x-ui](https://github.com/MHSanaei/3x-ui) | 面板版本、安装脚本、管理入口与备份 |
| Xboard | [cedar2025/Xboard](https://github.com/cedar2025/Xboard) | 订阅与订单前台；核对支付模块和节点后端 |
| Remnawave | [remnawave/panel](https://github.com/remnawave/panel) | 用户与节点管理；核对商城集成方式 |
| Remnashop | [snoups/remnashop](https://github.com/snoups/remnashop) | Remnawave生态的Telegram销售机器人；核对支付与接口实现 |
| Marzban | [Gozargah/Marzban](https://github.com/Gozargah/Marzban) | Xray用户与节点管理；核对部署和备份 |
| Hiddify Panel | [hiddify/Hiddify-Manager](https://github.com/hiddify/Hiddify-Manager) | 多协议用户管理；核对所用版本与部署架构 |
| V2Board | [v2board/v2board](https://github.com/v2board/v2board) | 最近代码推送在2024年；新部署先评估替代方案 |
| X-UI（vaxilu版本） | [vaxilu/x-ui](https://github.com/vaxilu/x-ui) | 最近代码推送在2024年；仅作旧环境迁移参考 |

完整的客户端选择与导入流程见[第5章 客户端工具使用指南](../第二部分-主流协议与工具篇/第05章-客户端工具使用指南.md)；面板对比与3X-UI安装、使用命令见[第13章 多用户管理方案](../第四部分-服务器搭建篇/第13章-多用户管理方案.md)。旧V2-UI教程所用仓库链接已失效，不再列为安装入口。已归档或长期未维护的项目可用于核对旧配置，但新安装前应优先确认仍受维护的实现。

## C.3 网络与安全标准

| 文档 | 用途 |
|------|------|
| [RFC 1928：SOCKS5](https://www.rfc-editor.org/rfc/rfc1928) | 理解SOCKS5代理 |
| [RFC 8446：TLS 1.3](https://www.rfc-editor.org/rfc/rfc8446) | 理解TLS版本与握手 |
| [RFC 9000：QUIC](https://www.rfc-editor.org/rfc/rfc9000) | 理解QUIC传输 |
| [NIST密码学标准与指南](https://csrc.nist.gov/projects/cryptographic-standards-and-guidelines) | 查阅安全标准与修订状态 |

技术资料和学术来源的书目信息见[附录D 参考文献](附录D-参考文献.md)。标准本身不能证明某个客户端实现安全，实际部署仍需核对软件文档与配置。

## C.4 下载与核对步骤

1. 从项目主页进入发布页，确认域名、仓库所有者和发布者；不要只依赖搜索结果或第三方下载站。
2. 选择与系统架构匹配的版本，阅读发布说明与已知问题。
3. 若发布者提供签名、校验值或软件包仓库验证流程，按其官方说明核对；记录实际下载文件和版本。
4. 在测试环境导入最小配置，检查权限、网络监听、DNS与回退路径，再考虑在常用设备或服务器部署。
5. 对付费软件、VPS或订阅服务，另行核对当前价格、条款、退款与数据政策。

## C.5 核对记录模板

```text
项目与用途：
项目主页和发布页：
核对日期：
目标系统与架构：
下载版本、文件名与签名/校验结果：
所参考文档的版本或提交：
维护状态和已知问题：
配置测试与回退结果：
```

本附录于2026年11月整理为资源索引。外部项目持续变化，上述入口应在每次实际使用时重新核对。
