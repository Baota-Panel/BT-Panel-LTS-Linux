# 宝塔Linux-LTS历史版本存档
由于宝塔官方的历史版本下载链接已不在官网显示,有些站长又想用旧版本的宝塔，故搜集了所有官方历史版本<br/>
本仓库所有版本的更新包通过 download.bt.cn 下载，绝对安全

正式版的升级包会不定时会同步一次（如无更新则不做任何同步）

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