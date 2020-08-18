## V2Ray 基于 Nginx 的 vmess+ws+tls安装教程

1. 创建实例
2. 安装bbr plus加速
3. 一键安装脚本：
```wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/Junting98/V2Ray_ws-tls_bash_onekey/master/install.sh" && chmod +x install.sh && bash install.sh
```
4. 配置v2ray

### 源码地址
https://github.com/wulabing/V2Ray_ws-tls_bash_onekey

#### 相关目录
伪装的 Web 目录：/home/wwwroot/3DCEList


V2ray 服务端配置：/etc/v2ray/config.json


Nginx 目录： /etc/nginx


证书文件: /data/v2ray.key 和 /data/v2ray.crt





步骤 先安装 四合一脚本（11）， 然后 安装bbr plus内核（2）， 再 安装11， 再13。


