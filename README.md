## Linux-Configuration
>新买linux基础搭建到运行记录过程慢慢完善
### 自述
本人长期从事前端开发并未涉及后端服务，所以想记录一下这次配置linux服务器过程，借鉴文档之处需要删除请联系我。
### 安装常用命令
* tar
* zip unzip

**1.tar 安装**  
>在 CentOS 中，以 root 用户在 shell 中执行下面的命令安装 tar。

```js
yum install tar
```
>下面的命令会在 Ubuntu 上安装 tar。“sudo” 命令确保 apt 命令是以 root 权限运行的。

```js
yum install tar
```
>下面的 apt 命令在 Debian 上安装 tar。

```js
apt-get install tar
```
**2.zip unzip 安装**  
> CentOS 中

```js
yum install -y unzip zip
```

### 安装常用软件
* node  
* nginx  
* mysql  
* redis  
* pm2  

**1. node安装**  

  首先 [打开官网](https://nodejs.org/en/download/)  
  <div align="left">
    <img src="https://user-images.githubusercontent.com/21699695/121794949-45252400-cc3f-11eb-9320-f758db0bd771.png" alt="Editor" width="600">
  </div>  

  ```js
  复制拿到链接，下载nodejs
  wget https://nodejs.org/dist/v10.15.3/node-v10.15.3-linux-x64.tar.xz（下载链接请到网站复制）
  
  解压 tar -xvf node-v10.15.3-linux-x64.tar.xz
  
  删除压缩包 rm -rf node-v10.15.3-linux-x64.tar.xz
  ```
