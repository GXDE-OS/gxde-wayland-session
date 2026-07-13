# GXDE Wayland Session
## Introduction | 介绍
This is `gxde-wayland-session`, a meta package that helps to install necessary component for GXDE Wayland session.

这是`gxde-wayland-session`，一个帮助安装GXDE Wayland会话必需组件的元包。

## Behavior | 行为
### Installation | 安装
The following packages will be installed or upgraded · 以下包会被安装/升级：
* `gxde-wlcom` (>=`1.4.1-gxde1`)
* `gxde-wlcom-client` (>=`1.4.1-gxde1`)
* `libdtk2widget6` (>=`6.0.3-4`)
* `libdtk2widget6-dev` (>=`6.0.3-4`)
* `layer-shell-qt`
* `gxde-file-manager-neo`
* `gxde-disk-mount-plugin-neo` (>=`6.2.0-gxde1`)
* `gxde-dock` (>=`6.0.0-1`)
* `gxde-dock-onboard-plugin` (>=`6.0.0-1`)
* `gxde-dock-weather` (>=`6.4.1`)
* `dde-grand-search` (>= 6.0.39gxde1)
* `dde-daemon` (>= 4.0.1)
* `gxde-sni-server` (>= 1.0.0-gxde1)

### Uninstallation | 卸载
The following packages will be removed · 以下包会被移除：
N/A

Note that although `deepin-mutter` is depreciated on GXDE, we are not uninstalling it. It seems that `deepin-mutter` uses same package name as mutter. We defininitely don't want to uninstall GNOME Mutter for users if they are actually using that, so you may want to remove it manually if using `deepin-mutter`...

需要注意的是尽管GXDE废弃了`deepin-mutter`，我们不会自动删除这个包。这是因为`deepin-mutter`似乎和Mutter用的同一个包名。我们可不想（在用户用的实际是GNOME Mutter的情况下）直接给人Mutter卸了，所以如果实际上你用的是`deepin-mutter`，一会你可能得自己卸载了...

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
