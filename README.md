**OpenMediaVault-Plugin-Developers插件安装，国内镜像**

omv-extras.org .deb releases

* Install from command line as root. If you are not root already, change to root first:
```console
 sudo su -
 wget -O - https://gitee.com/TitanRGB/packages/raw/master/install | bash
```

* If you don't want to use root, you must use sudo for the bash execution.  But if this is the first time you have run sudo, you will not see the sudo prompt for your password.  Use sudo for both commands:
```console
 sudo wget -O - https://gitee.com/TitanRGB/packages/raw/master/install | sudo bash
```

For issues with compose files, please start a thread on the forum - https://forum.openmediavault.org/
