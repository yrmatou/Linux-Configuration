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

**1. [node安装](https://github.com/wangQiaoBrother/Linux-Configuration/issues/1)**  
**2. [nginx安装](https://github.com/wangQiaoBrother/Linux-Configuration/issues/2)**  
**3. [mysql安装](https://github.com/wangQiaoBrother/Linux-Configuration/issues/3)**   
**4. [redis安装](https://github.com/wangQiaoBrother/Linux-Configuration/issues/4)**  
**5.pm2安装**
```js
npm install pm2 -g 全局安装
pm2 start app.js 
```
[pm2详细使用教程](https://www.jianshu.com/p/5f808762a71a)  

**辛苦！辛苦！喝口水！哈哈哈**
<div align="left">
  <img src="https://user-images.githubusercontent.com/21699695/121778277-d6a57f00-cbc8-11eb-9b28-13462b3fde2f.png" alt="Editor" width="200">
</div>
