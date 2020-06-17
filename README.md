## Trojan一键安装代码，集成BBR 4in1 脚本。
## Trojan：v1.16.0
Dependencies
CMake >= 3.7.2
Boost >= 1.66.0
OpenSSL >= 1.1.0
libmysqlclient
## 支持centos7+/debian9+/ubuntu16.04+
## 安装命令：
`wget --no-check-certificate -O trojan.sh https://github.com/troray/trojan/raw/master/trojan.sh && chmod +x trojan.sh && ./trojan.sh`

## 安装结束后，查看密码 等输入：
`cat /usr/src/trojan/server.conf`

### 内置静态网页，安装后输入：'https://你的域名' 查看是否正确。web页面为静态导航站，如要修改，直接编辑index.html源代码即可。

#### 新手请看：
#### 如果你的服务器没有wget命令，建议以下常用安装一下：
#### Ubuntu/Debian:
`apt-get update -y && apt-get -y install wget curl vim`

#### Centos:
`yum update -y && yum install -y install wget curl vim`
