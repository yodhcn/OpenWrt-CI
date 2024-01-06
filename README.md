# OpenWrt-CI

在 https://github.com/coolsnowwolf/lede 默认配置的基础上，做出了以下改动：

- `Extra packages --->`
  - `<*> ipv6helper`
- `LuCI --->`
  - `Applicants --->`
    - `<*> luci-app-acme`
    - `<*> luci-app-uhttpd`
- `Network --->`
  - `Firewall --->`
    - `-*- ip6tables`
      - `<*> ip6tables-extra`
      - `<*> ip6tables-mod-nat`
  - `<*> acme-dnsapi`
- 修改默认 ip (`192.168.1.1` -> `192.168.5.1`)
