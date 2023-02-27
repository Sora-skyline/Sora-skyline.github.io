
```shell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
# 下载linux内核更新包
wsl --set-default-version 2
```

## [Arch镜像](https://github.com/yuk7/ArchWSL/releases/tag/22.10.16.0)

1. 先下载.appx 和 .cer 文件，然后安装证书
2. 下载[Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=zh-cn&gl=cn&rtc=1)

## 配置Windows Terminal

1.  [添加Windows Terminal到鼠标右键菜单](https://zhuanlan.zhihu.com/p/91259377)
