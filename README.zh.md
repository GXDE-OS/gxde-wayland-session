![HEADER](./docs/img/HEADER.png)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!--
  <a href="https://gitee.com/GXDE-OS">
    <img src="./docs/img/distro_icon.png" alt="Logo" width="80" height="80">
  </a>
  -->

  <h3 align="center">GXDE Wayland会话</h3>

  <p align="center">
    用于一键安装GXDE Wayland特定会话组件的元包
    <br />
    <a href="https://gitee.com/GXDE-OS"><strong>探索GXDE-OS »</strong></a>
    <br />
    <br />
    <a href="./debian/control">Wayland组件最低要求</a>
    &middot;
    <a href="https://gitee.com/GXDE-OS/gxde-wlcom/issues">报告问题</a>
    &middot;
    <a href="https://gitee.com/GXDE-OS/gxde-wlcom/issues">请求功能</a>
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## 关于项目
这是`gxde-wayland-session`，一个帮助升级GXDE组件到Wayland会话要求的最低版本的元包。


<!-- GETTING STARTED -->
## 开始上手
本元包不含任何源码，只规定组件版本。如果有GXDE源，安装本元包即可更新组件。

### 前提条件
系统里要有GXDE源，对于`GXDE OS 25.4.1`以及之前的版本，您需要加入内测源。

我们不兼容`GXDE OS 15.x`。

### 安装
在源内安装`gxde-wayland-session`即可。

或者如果您想要手动生成本包：
```bash
$ chmod a+x ./build-deb
$ ./build-deb -d
```

生成的`.deb`包应位于项目根目录的上级目录。

您可以使用以下指令清理中间产物：
```bash
$ ./build-deb -c
```

注意：生成的`.deb`包也会被清除。


<!-- LICENSE -->
## 许可证
本仓库以[GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](./LICENSE)发行。这只是一个元包罢了，所有其他组件请参考它们自己的仓库以获取许可信息。


<!-- CONTACT -->
## 联系
如果有问题或者建议请提Issue。请不要在这个仓库提Issue，请前往[GXDE Wayland合成器](https://gitee.com/GXDE-OS/gxde-wlcom/issues)的仓库。我知道这很奇怪，但是由于早期开发时一切适配工作中出现的问题经常伴随着WM的问题，大家习惯了去GXWM那边提Issue，现在这已经是我们的一种习惯了，那边有MAINTAINER定期巡视Issue。



<!-- ACKNOWLEDGMENTS -->
## 感谢
感谢以下仓库提供参考：
* **BEST README Template**: https://github.com/othneildrew/Best-README-Template
