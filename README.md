# OpenWrt-CI

在 https://github.com/coolsnowwolf/lede 默认配置的基础上，做出了以下改动：

- 开启 ipv6 (`Extra packages --->`)
  - `<*> ipv6helper`
- 额外的 LuCI 应用 (`LuCI --> Applicants --->`)
  - `<*> luci-app-dockerman`
  - `<*> luci-app-openclash`
  - `<*> luci-app-uhttpd`
- 额外的软件包 (`Utilities --->`)
  - `<*> docker-compose`
- 修改默认 ip (`192.168.1.1` -> `192.168.5.1`)
