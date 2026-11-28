# Loyalsoldier Rules (MRS)

## Build Info
- **Updated:** 2026-11-28 12:44 (UTC+8) / 2026-11-28 04:44 UTC
- **Mihomo Version:** `v1.19.34`
- **Total MRS Rules:** 23

## 独立发布页导航
- **Loyalsoldier/clash-rules (MRS)**（12 个 MRS）：[Release `clash-rules`](https://github.com/ix1911/clash-rules-mrs/releases/tag/clash-rules) · 分支目录 `clash-rules/`
- **Loyalsoldier/v2ray-rules-dat (MRS)**（10 个 MRS）：[Release `v2ray-rules-dat`](https://github.com/ix1911/clash-rules-mrs/releases/tag/v2ray-rules-dat) · 分支目录 `v2ray-rules-dat/`
- **Loyalsoldier/cn-blocked-domain (MRS)**（1 个 MRS）：[Release `cn-blocked-domain`](https://github.com/ix1911/clash-rules-mrs/releases/tag/cn-blocked-domain) · 分支目录 `cn-blocked-domain/`

## 订阅线路说明（按来源分目录 / 独立 Release）
以下按三个来源分别举例，将示例链接末尾的文件名替换为对应来源清单中的任意 `.mrs` 文件名即可使用：

### Loyalsoldier/clash-rules (MRS)（以 `direct.mrs` 为例）
- **GitHub Releases 直链（走代理首选，实时更新）：** https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/direct.mrs
- **GitHub Raw 直链（与孤儿分支强一致，实时更新）：** https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/direct.mrs
- **jsDelivr CDN 线路（直连友好，存在约 12 小时缓存）：** https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/direct.mrs

### Loyalsoldier/v2ray-rules-dat (MRS)（以 `direct-list.mrs` 为例）
- **GitHub Releases 直链（走代理首选，实时更新）：** https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/direct-list.mrs
- **GitHub Raw 直链（与孤儿分支强一致，实时更新）：** https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/direct-list.mrs
- **jsDelivr CDN 线路（直连友好，存在约 12 小时缓存）：** https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/direct-list.mrs

### Loyalsoldier/cn-blocked-domain (MRS)（以 `domains.mrs` 为例）
- **GitHub Releases 直链（走代理首选，实时更新）：** https://github.com/ix1911/clash-rules-mrs/releases/download/cn-blocked-domain/domains.mrs
- **GitHub Raw 直链（与孤儿分支强一致，实时更新）：** https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/cn-blocked-domain/domains.mrs
- **jsDelivr CDN 线路（直连友好，存在约 12 小时缓存）：** https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/cn-blocked-domain/domains.mrs

## 规则来源与文件清单

### 1. Loyalsoldier/clash-rules (MRS)
- **来源：** https://github.com/Loyalsoldier/clash-rules
- **独立发布页：** https://github.com/ix1911/clash-rules-mrs/releases/tag/clash-rules
- **说明：** 适用于 Clash Premium / Mihomo 内核及各 GUI 客户端（ClashX Pro、clash-party、clash-verge-rev、Clash for Windows、clashmi、Clash Meta for Android、OpenClash 等）的规则集（RULE-SET），上游每天北京时间 06:30 自动构建。

| MRS 文件 | 类型 | 条目数 | 大小 | 说明与原始文件 | 订阅地址 |
| :--- | :---: | ---: | ---: | :--- | :---: |
| `direct.mrs` | `domain` | 110,250 | 518.6 KB | 直连域名列表（[direct.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/direct.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/direct.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/direct.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/direct.mrs) |
| `proxy.mrs` | `domain` | 27,293 | 194.4 KB | 代理域名列表（[proxy.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/proxy.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/proxy.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/proxy.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/proxy.mrs) |
| `reject.mrs` | `domain` | 204,783 | 1.9 MB | 广告域名列表（[reject.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/reject.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/reject.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/reject.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/reject.mrs) |
| `private.mrs` | `domain` | 132 | 781 B | 私有网络专用域名列表（[private.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/private.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/private.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/private.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/private.mrs) |
| `apple.mrs` | `domain` | 165 | 1.6 KB | Apple 在中国大陆可直连的域名列表（[apple.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/apple.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/apple.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/apple.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/apple.mrs) |
| `icloud.mrs` | `domain` | 52 | 574 B | iCloud 域名列表（[icloud.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/icloud.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/icloud.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/icloud.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/icloud.mrs) |
| `google.mrs` | `domain` | 112 | 1.4 KB | [慎用] Google 在中国大陆可直连的域名列表（[google.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/google.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/google.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/google.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/google.mrs) |
| `gfw.mrs` | `domain` | 4,484 | 34.3 KB | GFWList 域名列表（[gfw.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/gfw.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/gfw.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/gfw.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/gfw.mrs) |
| `tld-not-cn.mrs` | `domain` | 829 | 4.4 KB | 非中国大陆使用的顶级域名列表（[tld-not-cn.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/tld-not-cn.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/tld-not-cn.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/tld-not-cn.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/tld-not-cn.mrs) |
| `telegramcidr.mrs` | `ipcidr` | 12 | 145 B | Telegram 使用的 IP 地址列表（[telegramcidr.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/telegramcidr.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/telegramcidr.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/telegramcidr.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/telegramcidr.mrs) |
| `lancidr.mrs` | `ipcidr` | 28 | 236 B | 局域网 IP 及保留 IP 地址列表（[lancidr.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/lancidr.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/lancidr.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/lancidr.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/lancidr.mrs) |
| `cncidr.mrs` | `ipcidr` | 9,735 | 37.2 KB | 中国大陆 IP 地址列表（[cncidr.txt](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/cncidr.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/clash-rules/cncidr.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/clash-rules/cncidr.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/clash-rules/cncidr.mrs) |

**其他原文件（非 MRS，请直接引用上游地址）：**
- **applications.txt**：https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/applications.txt  
  需要直连的常见软件列表（`classical` 进程规则，MRS 格式不支持，请直接引用上游原文件并设置 `behavior: classical`）

### 2. Loyalsoldier/v2ray-rules-dat (MRS)
- **来源：** https://github.com/Loyalsoldier/v2ray-rules-dat
- **独立发布页：** https://github.com/ix1911/clash-rules-mrs/releases/tag/v2ray-rules-dat
- **说明：** V2Ray 路由规则文件加强版，适用于 V2Ray、Xray-core、mihomo、hysteria、Trojan-Go、leaf 及各 GUI 版代理软件，上游每天北京时间 06:00 自动构建。转换为 MRS 时已自动将裸域名与 `domain:` 规范为 `+.` 后缀匹配、`full:` 转为精确匹配、自动完成 IDN Punycode 转码，并过滤 MRS 不支持的 `regexp:` / `keyword:` / `include:` 条目。

| MRS 文件 | 类型 | 条目数 | 大小 | 说明与原始文件 | 订阅地址 |
| :--- | :---: | ---: | ---: | :--- | :---: |
| `direct-list.mrs` | `domain` | 110,250 | 518.6 KB | 直连域名列表（[direct-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/direct-list.txt)） · 已过滤 8 条非 MRS 规则 | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/direct-list.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/direct-list.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/direct-list.mrs) |
| `proxy-list.mrs` | `domain` | 27,293 | 194.4 KB | 代理域名列表（[proxy-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/proxy-list.txt)） · 已过滤 151 条非 MRS 规则 | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/proxy-list.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/proxy-list.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/proxy-list.mrs) |
| `reject-list.mrs` | `domain` | 204,783 | 1.9 MB | 广告域名列表（[reject-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/reject-list.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/reject-list.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/reject-list.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/reject-list.mrs) |
| `china-list.mrs` | `domain` | 109,506 | 516.1 KB | @felixonmars/dnsmasq-china-list 中国大陆可直连域名列表（[china-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/china-list.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/china-list.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/china-list.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/china-list.mrs) |
| `apple-cn.mrs` | `domain` | 165 | 1.3 KB | Apple 在中国大陆可直连的域名列表（[apple-cn.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/apple-cn.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/apple-cn.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/apple-cn.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/apple-cn.mrs) |
| `google-cn.mrs` | `domain` | 112 | 1.2 KB | Google 在中国大陆可直连的域名列表（[google-cn.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/google-cn.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/google-cn.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/google-cn.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/google-cn.mrs) |
| `gfw.mrs` | `domain` | 4,484 | 34.3 KB | GFWList 域名列表（[gfw.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/gfw.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/gfw.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/gfw.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/gfw.mrs) |
| `win-spy.mrs` | `domain` | 347 | 2.7 KB | Windows 操作系统使用的隐私跟踪域名列表（[win-spy.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/win-spy.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/win-spy.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/win-spy.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/win-spy.mrs) |
| `win-update.mrs` | `domain` | 538 | 2.2 KB | Windows 操作系统使用的系统升级域名列表（[win-update.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/win-update.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/win-update.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/win-update.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/win-update.mrs) |
| `win-extra.mrs` | `domain` | 399 | 3.6 KB | Windows 操作系统使用的附加隐私跟踪域名列表（[win-extra.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/win-extra.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/v2ray-rules-dat/win-extra.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/v2ray-rules-dat/win-extra.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/v2ray-rules-dat/win-extra.mrs) |

**其他原文件（非 MRS，请直接引用上游地址）：**
- **geoip.dat**：https://github.com/Loyalsoldier/v2ray-rules-dat/releases/latest/download/geoip.dat  
  GeoIP 数据库原文件（二进制 `.dat`，直接引用上游地址即可）
- **geosite.dat**：https://github.com/Loyalsoldier/v2ray-rules-dat/releases/latest/download/geosite.dat  
  GeoSite 数据库原文件（二进制 `.dat`，直接引用上游地址即可）

### 3. Loyalsoldier/cn-blocked-domain (MRS)
- **来源：** https://github.com/Loyalsoldier/cn-blocked-domain
- **独立发布页：** https://github.com/ix1911/clash-rules-mrs/releases/tag/cn-blocked-domain
- **说明：** 通过 GreatFire Analyzer 的 JSON API（https://en.greatfire.org/api/tags?status=blocked）获取在中国大陆被屏蔽的域名和 IP 地址，并进行校验、去重与聚合。

| MRS 文件 | 类型 | 条目数 | 大小 | 说明与原始文件 | 订阅地址 |
| :--- | :---: | ---: | ---: | :--- | :---: |
| `domains.mrs` | `domain` | 35,391 | 222.1 KB | 中国大陆被屏蔽域名列表（[domains.txt](https://raw.githubusercontent.com/Loyalsoldier/cn-blocked-domain/release/domains.txt)） | [Releases](https://github.com/ix1911/clash-rules-mrs/releases/download/cn-blocked-domain/domains.mrs) · [Raw](https://raw.githubusercontent.com/ix1911/clash-rules-mrs/release/cn-blocked-domain/domains.mrs) · [CDN](https://cdn.jsdelivr.net/gh/ix1911/clash-rules-mrs@release/cn-blocked-domain/domains.mrs) |
| `ip.mrs` | `ipcidr` | 0 | - | 中国大陆被屏蔽 IP 地址列表（[ip.txt](https://raw.githubusercontent.com/Loyalsoldier/cn-blocked-domain/release/ip.txt)） | 当日上游无有效条目 |
| `deduplicated-domains.mrs` | `domain` | 0 | - | 因父域名已存在而被移除的子域名（[deduplicated-domains.txt](https://raw.githubusercontent.com/Loyalsoldier/cn-blocked-domain/release/deduplicated-domains.txt)） | 当日上游无有效条目 |
