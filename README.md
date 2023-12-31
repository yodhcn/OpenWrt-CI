# OpenWrt-CI

在 https://github.com/coolsnowwolf/lede 默认配置的基础上，做出了以下改动：

- `Extra packages --->`
  - `<*> ipv6helper`
- `LuCI --->`
  - `Collections --->`
    - `<*> luci-nginx`
    - `<*> luci-ssl-nginx`
  - `Applicants --->`
    - `<*> luci-app-acme`
    - `<*> luci-app-openclash`
- `Network --->`
  - `<*> acme-dnsapi`
- 修改默认 ip (`192.168.1.1` -> `192.168.5.1`)
