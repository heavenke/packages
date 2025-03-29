# OpenWrt软件包源

## 说明

这是OpenWrt的"软件包"源,其中包含由社区维护的构建脚本,以及针对OpenWrt中所使用的应用程序、模块和库的配置选项与补丁.

预构建软件包的安装可直接通过你正在运行的OpenWrt系统中的opkg安装程序来处理,或者使用 [OpenWrt SDK](https://openwrt.org/docs/guide-developer/using_the_sdk) 来完成.

## 用法

此存储库旨在叠加在OpenWrt源码根目录之上.如果你尚未同步OpenWrt源码,请查看OpenWrt支持站点上的以下文档:[OpenWrt Buildroot – Installation](https://openwrt.org/docs/guide-developer/build-system/install-buildsystem) .

此软件包源默认是启用状态,要安装其所有的软件包定义,请运行:
```
./scripts/feeds update packages
./scripts/feeds install -a -p packages
```

## 许可证

查看 [LICENSE](LICENSE)
 
## 软件包指南

查看 [CONTRIBUTING.md](CONTRIBUTING.md) file.

