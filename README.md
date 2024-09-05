# 宝塔Linux-LTS历史版本存档
本仓库所有版本的更新包通过 `download.bt.cn` 下载

<del>站点默认404＆502界面出现宝塔的ad（仅中国大陆机器显示，海外机器无影响，可自行修改网站目录内的404.html）</del>  国内版宝塔目前已移除该AD

BTPanel 9.0.0-LTS更新日志：[https://www.bt.cn/bbs/forum.php?mod=viewthread&tid=134609](https://www.bt.cn/bbs/forum.php?mod=viewthread&tid=134609)<br/>

注：正式版和LTS版本**不可混用**！！！

<!--
* 官方安装命令：(9.0.0公测版)[默认线路]
```
url=https://download.bt.cn/install/install_lts.sh;if [ -f /usr/bin/curl ];then curl -sSO $url;else wget -O install_lts.sh $url;fi;bash install_lts.sh ltsview ed8484bec
```
* 官方安装命令：(9.0.0公测版)[电信线路]
```
url=https://cmcc1-node.bt.cn/install/install_lts.sh;if [ -f /usr/bin/curl ];then curl -sSO $url;else wget -O install_lts.sh $url;fi;bash install_lts.sh ltsview ed8484bec
```
* 官方安装命令：(9.0.0公测版)[香港线路]
```
url=https://hk1-node.bt.cn/install/install_lts.sh;if [ -f /usr/bin/curl ];then curl -sSO $url;else wget -O install_lts.sh $url;fi;bash install_lts.sh ltsview ed8484bec
```
* 官方安装命令：(9.0.0公测版)[欧美线路]
```
url=https://cf1-node.aapanel.com/install/install_lts.sh;if [ -f /usr/bin/curl ];then curl -sSO $url;else wget -O install_lts.sh $url;fi;bash install_lts.sh ltsview ed8484bec
```
-->
* 官方安装命令：(9.0.0-LTS预览版)[万能安装脚本]
```
url=https://download.bt.cn/install/install_lts.sh;if [ -f /usr/bin/curl ];then curl -sSO $url;else wget -O install_lts.sh $url;fi;bash install_lts.sh ed8484bec
```
* 官方安装命令：(9.0.0-LTS预览版)[Debian安装脚本]
```
wget -O install.sh https://download.bt.cn/install/install_lts.sh && bash install.sh ed8484bec
```
* 官方安装命令：(9.0.0-LTS预览版)[Ubuntu/Deepin安装脚本]
```
wget -O install.sh https://download.bt.cn/install/install_lts.sh && sudo bash install.sh ed8484bec
```
* 官方安装命令：(9.0.0-LTS预览版)[CentOS/OpenCloud/AlibabaCloud安装脚本]
```
yum install -y wget && wget -O install.sh https://download.bt.cn/install/install_lts.sh && bash install.sh ed8484bec
```
