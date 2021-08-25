# GeoIP2 · CN · CHNRoutes
### 小巧、准确、实用的 中国大陆 IPv4 + IPv6 GeoIP2 数据库
### 简介
由于 MaxMind 将部分 IP 错误归类为中国大陆，导致根据 GeoIP 分流出现问题。
且现有 IP 库大都不包含 IPv6 地址信息，此项目应运而生并保持每天更新。

### 下载
| 📦 项目 | 📃 文件 | :octocat: GitHub RAW | 🚀 CDN 加速 | 🔧 适用范围
|  :--:  |  :--:  |     :--:     |     :--:    | ---- |
| IP-CIDR 列表 | CN-ip-cidr.txt | [点击下载](https://github.com/jxcn/GeoIP2-CN/raw/release//CN-ip-cidr.txt) | [加速下载](https://cdn.jsdelivr.net/gh/jxcn/GeoIP2-CN@release/CN-ip-cidr.txt) | iptables, ipset, squid, gost, 3proxy, etc. | 
| GeoIP2 数据库 | Country.mmdb | [点击下载](https://github.com/jxcn/GeoIP2-CN/raw/release//Country.mmdb) | [加速下载](https://cdn.jsdelivr.net/gh/jxcn/GeoIP2-CN@release/Country.mmdb) | Surge, Shadowrocket, QuantumultX, Clash IP-CDR|
| IP sets | chnroute.ipset | [点击下载](https://github.com/jxcn/GeoIP2-CN/raw/release//chnroute.ipset) | [加速下载](https://cdn.jsdelivr.net/gh/jxcn/GeoIP2-CN@release/chnroute.ipset) | ipset restore < chnroute.ipset |

### 版权
本项目 Fork 自 [JMVoid/ipip2mmdb](https://github.com/JMVoid/ipip2mmdb)，并加以修改和调整。

项目中使用的 IP 数据源自 [17mon/china_ip_list](https://github.com/17mon/china_ip_list) (IPv4) 和 [gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip) (IPv6)。

GeoIP® 商标版权归 [MaxMind](https://www.maxmind.com/) 公司所有。

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
