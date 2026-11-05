# 附录A：术语表

## 常用技术术语中英对照

### 基础概念

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 科学上网 | - | - | 绕过网络访问限制的技术统称 |
| 翻墙 | - | - | 科学上网的俗称 |
| 代理 | Proxy | - | 代理服务器，中转网络请求 |
| 虚拟私人网络 | Virtual Private Network | VPN | 加密的虚拟网络连接 |
| 防火墙 | Firewall | - | 网络安全防护系统 |
| 防火长城 | Great Firewall | GFW | 中国网络防火墙系统 |

### 网络协议

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 超文本传输协议 | Hypertext Transfer Protocol | HTTP | 网页传输协议 |
| 安全超文本传输协议 | HTTP Secure | HTTPS | 加密的HTTP协议 |
| 传输控制协议 | Transmission Control Protocol | TCP | 可靠的传输协议 |
| 用户数据报协议 | User Datagram Protocol | UDP | 快速但不可靠的传输协议 |
| 互联网协议 | Internet Protocol | IP | 网络层协议 |
| 域名系统 | Domain Name System | DNS | 域名解析系统 |
| 传输层安全 | Transport Layer Security | TLS | 加密传输协议 |
| 安全套接字层 | Secure Sockets Layer | SSL | TLS的前身 |

### 代理协议与相关机制

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 影梭 | Shadowsocks | SS | 轻量级代理协议 |
| 影梭R | ShadowsocksR | SSR | SS的增强版本 |
| - | VMess | - | V2Ray的原创协议 |
| - | VLESS | - | 轻量级的VMess |
| - | Trojan | - | 模仯HTTPS的协议 |
| - | REALITY | - | Xray生态中的传输安全机制，常与VLESS等代理协议组合使用 |
| - | Hysteria | - | 基于QUIC的高性能代理 |
| - | Hysteria 2 | - | Hysteria的第二代(2024+) |
| - | WireGuard | WG | 现代VPN协议 |
| 快速UDP互联网连接 | Quick UDP Internet Connections | QUIC | Google开发的协议 |
| - | SOCKS5 | - | 通用代理协议 |

### 加密技术

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 高级加密标准 | Advanced Encryption Standard | AES | 对称加密算法 |
| - | ChaCha20 | - | 流加密算法 |
| - | Poly1305 | - | 消息认证码 |
| 带关联数据的认证加密 | Authenticated Encryption with Associated Data | AEAD | 认证加密模式 |
| 伽罗瓦计数器模式 | Galois/Counter Mode | GCM | AEAD模式之一 |
| 椭圆曲线加密 | Elliptic Curve Cryptography | ECC | 非对称加密 |
| - | RSA | - | 非对称加密算法 |

### 客户端工具

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| - | Clash | - | 跨平台代理客户端 |
| - | Clash Verge | - | Clash现代化GUI客户端 |
| - | Clash Verge Rev | - | Clash Verge继续版本 |
| - | V2RayN | - | Windows V2Ray客户端 |
| - | ClashX | - | macOS Clash客户端 |
| - | Shadowrocket | - | iOS代理客户端（小火箭） |
| - | Surge | - | iOS/macOS高级网络工具 |
| - | Quantumult X | - | iOS代理客户端（圈X） |
| - | Qv2ray | - | 跨平台V2Ray客户端 |
| - | v2rayNG | - | Android V2Ray客户端 |
| - | NekoBox | - | Android多协议客户端 |

### 服务器相关

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 虚拟专用服务器 | Virtual Private Server | VPS | 虚拟服务器 |
| 基础设施即服务 | Infrastructure as a Service | IaaS | 云服务模式 |
| 安全外壳协议 | Secure Shell | SSH | 远程登录协议 |
| 中国电信CN2网络 | ChinaNet Next Carrier Network | CN2 | 电信优质网络 |
| CN2全球互联精品网 | CN2 Global Internet Access | CN2 GIA | CN2最高级别 |
| 国际私有租用线路 | International Private Leased Circuit | IPLC | 国际专线 |
| 国际以太网专线 | International Ethernet Private Line | IEPL | 以太网专线 |
| - | X-UI | - | 旧版Xray多用户面板；本书仅作迁移参考 |
| - | 3X-UI | - | 持续更新的Xray服务端管理面板，支持Reality与多用户管理 |
| - | mack-a | - | V2Ray/Xray一键脚本 |
| - | Xray-core | - | V2Ray分支,支持XTLS |

### 网络优化

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 瓶颈带宽和往返时间 | Bottleneck Bandwidth and Round-trip time | BBR | Google的TCP拥塞控制算法 |
| 多路复用 | Multiplexing | Mux | 复用单个连接 |
| 内容分发网络 | Content Delivery Network | CDN | 内容分发网络 |
| 最大传输单元 | Maximum Transmission Unit | MTU | 数据包最大尺寸 |
| 往返时间 | Round-Trip Time | RTT | 数据往返延迟 |
| 服务质量 | Quality of Service | QoS | 网络服务质量 |

### 配置相关

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| - | YAML | - | 配置文件格式 |
| - | JSON | - | 数据交换格式 |
| 通用资源标识符 | Uniform Resource Identifier | URI | 资源标识符 |
| 统一资源定位符 | Uniform Resource Locator | URL | 网址 |
| 服务器名称指示 | Server Name Indication | SNI | TLS扩展 |
| 无类别域间路由 | Classless Inter-Domain Routing | CIDR | IP地址表示法 |

### 安全与隐私

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 深度包检测 | Deep Packet Inspection | DPI | 流量深度分析 |
| 网络地址转换 | Network Address Translation | NAT | 地址转换技术 |
| 中间人攻击 | Man-in-the-Middle | MITM | 拦截通信攻击 |
| 分布式拒绝服务 | Distributed Denial of Service | DDoS | 分布式攻击 |
| 洋葱路由 | The Onion Router | Tor | 匿名网络 |
| DNS over HTTPS | DNS over HTTPS | DoH | 加密DNS查询 |
| DNS over TLS | DNS over TLS | DoT | TLS加密DNS |
| DNS over QUIC | DNS over QUIC | DoQ | QUIC加密DNS(新兴) |
| 网络实时通信 | Web Real-Time Communication | WebRTC | 浏览器实时通信 |
| 浏览器指纹 | Browser Fingerprinting | - | 通过浏览器特征追踪用户 |
| 增强追踪保护 | Enhanced Tracking Protection | ETP | Firefox隐私保护功能 |

### 其他术语

| 中文 | 英文 | 缩写 | 说明 |
|------|------|------|------|
| 机场 | Airport | - | 代理服务提供商俗称 |
| 节点 | Node | - | 代理服务器 |
| 订阅 | Subscription | - | 节点订阅链接 |
| 分流 | Routing/Split | - | 智能路由选择 |
| 直连 | Direct | - | 不通过代理 |
| 全局 | Global | - | 所有流量走代理 |
| 规则 | Rule | - | 分流规则 |
| 回落 | Fallback | - | 伪装机制，错误请求转发 |
| 流控 | Flow Control | - | VLESS流控（如xtls-rprx-vision） |
| 延迟 | Latency/Ping | - | 网络延迟 |
| 带宽 | Bandwidth | - | 网络传输速率 |
| 流量 | Traffic | - | 数据传输量 |
| 丢包 | Packet Loss | - | 数据包丢失 |
| 跳数 | Hops | - | 路由跳转次数 |

### 技术缩写速查

```
常用缩写快速查询：

网络基础：
IP, TCP, UDP, HTTP, HTTPS, DNS, TLS, SSL, NAT

代理协议:
SS, SSR, VMess, VLESS, Reality, Hysteria 2, SOCKS5, WireGuard (WG)

加密算法：
AES, ChaCha20, RSA, ECC, AEAD, GCM

服务器：
VPS, SSH, CN2, IPLC, IEPL, CDN

优化技术：
BBR, Mux, MTU, RTT, QoS

安全相关:
DPI, MITM, DDoS, DoH, DoT, DoQ, WebRTC, ETP

其他：
GFW, VPN, URL, URI, SNI, CIDR
```

---

**使用提示：**

1. 建议收藏本术语表，遇到不懂的术语时查阅
2. 英文缩写通常在技术文档中使用
3. 中文术语更常用于日常交流
4. 某些术语（如"机场"）为社区俗称，非正式术语
