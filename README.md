本项目记录搭建kubernetes环境的全部步骤，在搭建过程中能够对kubernetes有更深入的理解，同时方便以后搭建kubernetes环境的参考。


[一、环境准备]


环境配置与资源下载：

物理机系统：Ubuntu Server 16.04.4 amd64，从此下载地址选择距离自己最近镜像进行下载即可：https://www.ubuntu.com/download/alternative-downloads#alternate-ubuntu-server-installer

VirtualBox：virtualbox-5.2_5.2.12-122591~Ubuntu~xenial_amd64.deb，下载地址：https://download.virtualbox.org/virtualbox/5.2.12/virtualbox-5.2_5.2.12-122591~Ubuntu~xenial_amd64.deb

服务器系统：Ubuntu Server 18.04 amd64，下载地址：http://releases.ubuntu.com/18.04/ubuntu-18.04-live-server-amd64.iso

Docker版本：docker-ce_18.03.1~ce-0~ubuntu_amd64.deb，下载地址：
https://download.docker.com/linux/ubuntu/dists/xenial/pool/stable/amd64/docker-ce_18.03.1~ce-0~ubuntu_amd64.deb

Kubernetes：kubernetes-1.11，下载地址：https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.11.md

