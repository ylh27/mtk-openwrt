# mtk-openwrt

## ```mtk-autobuild.yml```

Automatically builds OpenWrt for MediaTek Wi-Fi 7 devices with patches applied from MediaTek's OpenWrt feeds. Documentation can be found on the [MediaTek feeds](https://git01.mediatek.com/plugins/gitiles/openwrt/feeds/mtk-openwrt-feeds/+/refs/heads/master/autobuild/unified/). The GitHub workflow in this repo is set up to build automatically 3 times a week for the Filogic 880 target. A different target can be specified for manual workflow runs.

On every workflow run, the patched source is pushed onto a branch, which makes inspecting the MediaTek patches easier.
