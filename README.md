# OpenWrt

---

### Basic Information

- **LAN Address**: [10.0.0.1](http://10.0.0.1/)
- **Target Platform**: `x86/64`
- **Firmware Version**: `OpenWrt SNAPSHOT`
- **Username**: `root`
- **Password**: `NONE`

### Firmware Download

- [Releases](https://github.com/apoiston/builder/releases)

### Package Download

- [base](https://initbase.pages.dev/)

- [luci](https://initluci.pages.dev/)

- [packages](https://initpackages.pages.dev/)

- [kmods](https://initkmods.pages.dev/)

- [system](https://initsystem.pages.dev/)

- [extra](https://initextra.pages.dev/)

### Common Commands

```shell
# kernel build information
cat /proc/version
```

```shell
# flash firmware (save configuration over reflash)
sysupgrade /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz
```

```shell
# flash firmware (do not save configuration over reflash)
sysupgrade -n /tmp/openwrt-x86-64-generic-erofs-combined-efi.img.gz
```

### Credits

- [OpenWrt](https://github.com/openwrt/openwrt)

- [OpenWrt LuCI](https://github.com/openwrt/luci)

- [OpenWrt Packages](https://github.com/openwrt/packages)

- [OpenWrt Nikki](https://github.com/nikkinikki-org/OpenWrt-nikki)

- [MetaCubeX Mihomo](https://github.com/MetaCubeX/mihomo)
