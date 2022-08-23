# 自用的X86和RockChip固件


## 说明

- 编译固件结束后，自动发送WeTransfer下载地址到Bark。
- x86固件比较大，在make menuconfig->Target Image->GZip images中选择了“gzip”进行压缩。
- RockChip固件，在make menuconfig->Target Image->tar.gz进行压缩。
- 压缩后150兆左右，解压后大小3G左右。
- 注意需要用WinRAR解压，用7zip会解压失败。
- 感谢Lean提供的开源代码和p3terx大神的Action教程。

## 致谢

- [P3TERX's Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [shink/bark-action](https://github.com/shink/bark-action)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## License

[MIT](https://github.com/Nothend/OpenWRT/blob/main/LICENSE) © [**Nothend**]
