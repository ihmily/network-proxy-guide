# 附录D：参考文献与核对方法

本附录优先列出标准制定机构、项目维护者和官方法规数据库的原始资料。**列出入口不代表书中所有示例已按最新版本重新验证**；涉及具体字段、安装命令、项目维护状态或法律条文时，应在相关章节直接标注所依据的版本与核对日期。

## D.1 网络与安全标准

| 文档 | 主题 | 原文 |
|------|------|------|
| RFC 1035 | DNS实现与规范 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc1035) |
| RFC 1928 | SOCKS5 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc1928) |
| RFC 6455 | WebSocket | [RFC Editor](https://www.rfc-editor.org/rfc/rfc6455) |
| RFC 8446 | TLS 1.3 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc8446) |
| RFC 8484 | DNS over HTTPS | [RFC Editor](https://www.rfc-editor.org/rfc/rfc8484) |
| RFC 9000 | QUIC传输 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc9000) |
| RFC 9110 | HTTP语义 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc9110) |
| RFC 9112 | HTTP/1.1 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc9112) |
| RFC 9113 | HTTP/2 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc9113) |
| RFC 9114 | HTTP/3 | [RFC Editor](https://www.rfc-editor.org/rfc/rfc9114) |
| RFC 9250 | DNS over QUIC | [RFC Editor](https://www.rfc-editor.org/rfc/rfc9250) |

同一主题可能有早期RFC、更新与勘误。查阅时以RFC Editor页面中的状态和更新关系为准，不单凭本书列出的编号判断某份文档是否仍为现行依据。

## D.2 软件项目原始资料

| 项目 | 原始资料入口 | 阅读时要核对 |
|------|--------------|--------------|
| Xray-core | [项目仓库](https://github.com/XTLS/Xray-core)、[安装器仓库](https://github.com/XTLS/Xray-install) | 核心版本、配置格式、安装器提交 |
| V2Fly | [项目仓库](https://github.com/v2fly/v2ray-core) | 与Xray的实现差异 |
| mihomo | [项目仓库](https://github.com/MetaCubeX/mihomo) | 规则、DNS和接口字段 |
| Shadowsocks Rust | [项目仓库](https://github.com/shadowsocks/shadowsocks-rust) | 协议实现及密钥格式 |
| Hysteria | [项目仓库](https://github.com/apernet/hysteria) | 主要版本与对应配置 |
| WireGuard | [官方网站](https://www.wireguard.com/) | 系统平台与路由示例 |

项目仓库与其镜像、分支和衍生客户端并非同一份文档。引用软件行为时，最好同时记录项目名称、文档页、软件版本或提交号，以及访问日期。客户端检索入口见[附录C 资源索引](附录C-资源索引.md)。

## D.3 安全与隐私资料

| 来源 | 用途 |
|------|------|
| [NIST密码学标准与指南](https://csrc.nist.gov/projects/cryptographic-standards-and-guidelines) | 核对密码学标准的现行版本与状态 |
| [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) | 查找应用与部署安全检查项 |
| [Mozilla TLS配置指南](https://ssl-config.mozilla.org/) | 对照具体服务器版本检查TLS配置 |
| [EFF Cover Your Tracks](https://coveryourtracks.eff.org/) | 了解浏览器可观察的跟踪信号；测试结果不构成匿名保证 |

这些资料的适用范围各不相同。规范、检查清单和在线测试工具不能替代对实际部署的安全评估。

## D.4 法规与政策来源

| 来源 | 检索用途 |
|------|----------|
| [司法部国家行政法规库](https://xzfg.moj.gov.cn/) | 查询中国大陆行政法规的现行文本与修订信息 |
| [国家法律法规数据库](https://flk.npc.gov.cn/) | 查询中国大陆法律及相关规范性文件 |

不同国家和地区应使用当地官方数据库。引用法律时写明完整名称、发布机关、修订或生效日期、具体条款和访问日期；不能仅用“1996年发布”等历史信息替代现行文本。第21章给出[合规核对框架](../第七部分-最佳实践篇/第21章-合规使用建议.md)。

## D.5 本书的引用规则

1. **稳定原理**：优先引用RFC或标准制定机构资料；如果标准被更新，说明所用版本。
2. **软件行为**：在命令或配置附近标注项目、版本和对应官方文档，避免把不同核心的字段混用。
3. **时效性判断**：对维护状态、价格、下载位置和平台支持注明核对日期，不使用无期限的“最新”“最佳”结论。
4. **法律与政策**：直接指向官方现行文本，区分条文、解释和实际场景判断；不以缺乏来源的个案比例概括执法实践。
5. **二手资料**：保留作者、完整标题、发表年份和可访问链接；信息不全时暂不列为可靠依据。

可复制的记录格式：

```text
作者或机构：《文档完整标题》，版本/修订日期，具体章节或条款，官方URL；访问日期：YYYY-MM-DD。
适用范围与本书引用位置：
```

本附录于2026年11月重整书目结构。外部页面、软件版本与法规仍须在使用时逐项复核。
