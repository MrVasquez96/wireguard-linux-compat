Forked from https://github.com/dustin-richards-was-here/wireguard-linux-compat with updates for kernel 5.10.120-tegra, 5.10.216-tegra and 5.15.148-tegra to build Wireguard on an Nvidia Jetson Orin board where the Wireguard module is disabled.

Notes: 
- Make sure to use the correct branch for your kernel version.
- Building on a Jetson which was flashed using an Ubuntu 24 host might introduce new errors. try using the [Ubuntu 24](https://github.com/MrVasquez96/wireguard-linux-compat/tree/5.15.148-tegra(ubuntu24)) branch if the [default](https://github.com/MrVasquez96/wireguard-linux-compat/tree/5.15.148-tegra) one fails. 

This fork was also inspired by this post on Serverfault: https://serverfault.com/questions/1157392/installing-wireguard-on-nvidia-tegra-boards

# WireGuard for Linux 3.10 - 5.5

WireGuard was merged into the Linux kernel for 5.6. This repository contains a backport of WireGuard for kernels 3.10 to 5.5, as an out of tree module.

**More information may be found at [WireGuard.com](https://www.wireguard.com/).**

## License

This project is released under the [GPLv2](COPYING).
