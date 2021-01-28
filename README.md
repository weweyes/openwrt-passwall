# openwrt-passwall
使用方法1

添加 src-git passwall https://github.com/weweyes/openwrt-passwall 到 OpenWRT源码根目录feeds.conf.default文件

然后执行

./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a



使用方法2

把该源码手动下载或Git Clone下载放到OpenWRT源码的Package目录里面，然后编译。 
如果你使用的是Luci19或更高，请编译时选上"luci","luci-compat","luci-lib-ipkg"后编译

然后执行

./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
