# lxcapp

Scripts to maintain my personal secure system, based on  LXC/LXD containers. I isolate applications, and spwan for them personal firewall gateways. C

reates independent storages for containers, that makes possible, for example, to mount them from external media. Automatically installs GUI & sound components, so you can run X11 and PulseAudio apps. Based on Debian. For Debian 10 Buster, it can autoomatically mount local repo, and install packages from it,

lxcappcnt - Manages application containers. Reads config params from env vars and from centralized config file

lxcappcnt11 - lxcappcnt, based on Debian 11 Bullseye, on  not on Debian 10 (beta)
lxcpkg - Script to install software into coontainers, that are created by firest script (not ready for this monent).
lxcapp - Runs application, wait until it it's process is terminated, and performs delayed stop of container

