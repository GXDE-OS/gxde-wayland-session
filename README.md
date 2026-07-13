# GXDE Wayland Session
## Introduction | 介绍
This is `gxde-wayland-session`, a meta package that helps to install necessary component for GXDE Wayland session.

这是`gxde-wayland-session`，一个帮助安装GXDE Wayland会话必需组件的元包。

## Behavior | 行为
### Installation | 安装
The following packages will be installed or upgraded · 以下包会被安装/升级：
* `gxde-wlcom` (至少更新至`1.4.1-gxde1`)
* gxde-wlcom-client (至少更新至`1.4.1-gxde1`)

### Uninstallation | 卸载
The following packages will be removed · 以下包会被移除：
N/A

## Building | 构建
For building please run · 对于构建请执行：
```bash
$ chmod a+x ./build-deb
$ ./build-deb -d
```

The artifacts may be found on the parent folder of the project root.

构建产物可以在项目根目录的上级目录找到。

After building you may run this command to cleanup · 构建完成后可以执行以下命令执行清理：
```bash
$ ./build-deb -c
```

Please note that the artifacts will also be cleaned.

请注意构建产物会被一并清除。
