![HEADER](./docs/img/HEADER.png)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!--
  <a href="https://gitee.com/GXDE-OS">
    <img src="./docs/img/distro_icon.png" alt="Logo" width="80" height="80">
  </a>
  -->

  <h3 align="center">GXDE Wayland Session</h3>

  <p align="center">
    A meta package that helps you upgrrade GXDE components to minimum required version.
    <br />
    <a href="https://www.gxde.top/en/"><strong>Explore GXDE-OS »</strong></a>
    <br />
    <br />
    <a href="./debian/control">GXDE Wayland Component's Min. Requirement</a>
    &middot;
    <a href="https://gitee.com/GXDE-OS/gxde-wlcom/issues">Report Bug</a>
    &middot;
    <a href="https://gitee.com/GXDE-OS/gxde-wlcom/issues">Request Feature</a>
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About the Project
This is `gxde-wayland-session`, a meta package that helps to upgrrade GXDE components to minimum required version.


<!-- GETTING STARTED -->
## Getting Started
This package does NOT contain any source code but it defines components' minimum version required. If you have GXDE APT source installed, then installing this paackage shall help you upgrrade GXDE components to minimum required version.

### Prerequisite
You should have GXDE APT source installed in your system.

For any versions before `GXDE OS 25.4.1` (INCLUDED), you need to join the internal testing group.

This package is NOT compactiable with `GXDE OS 15.x`.

### Installing
Just simply install `gxde-wayland-session` from GXDE APT source.

Or, if you prefer to generate this meta package locally:
```bash
$ chmod a+x ./build-deb
$ ./build-deb -d
```

The artifact could be found on the parent folder of project root.

You may do a clean-up after you finished: 
```bash
$ ./build-deb -c
```

Note that it ALSO clears those artifacts mentioned earlier.


<!-- LICENSE -->
## License
This repository is licensed under [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](./LICENSE). This is just a meta package. For all the components, please refer to their own licenses, which could be found in their own repositories.


<!-- CONTACT -->
## Contact
Please fire up an Issue if you have any question or want to request a feature. Please do NOT fire up an Issue here. Instead, please go to [GXDE Wayland Compositor](https://gitee.com/GXDE-OS/gxde-wlcom/issues)'s repository.

I know that this sounds strange, but in the early development stages all kinds of bugs of the components are together w/ WM issues, so everyone get used to fire up an issue there for any bugs under Wayland. We also have maintainer there that checks issues regularly.



<!-- ACKNOWLEDGMENTS -->
## Acknowledgements
Thanks for those repositor(ies) for providing reference: 
* **BEST README Template**: https://github.com/othneildrew/Best-README-Template
