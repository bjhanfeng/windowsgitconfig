windowsgitconfig
================

1:安装msysgit到$gitinstallpath
2:修改$gitinstallpath\etc\profile
	在# Set up USER's home directory前一行添加HOME='/d/linuxhome/' /d/linuxhome为你设定的home目录。
	在最后一行添加cd ~
3:打开git bash 运行git clone git://github.com/bjhanfeng/windowsgitconfig.git .rc
4:cd .rc && install.sh
注意：每次git fetch后需要重新install.sh
5:.ssh/ 下放至私钥