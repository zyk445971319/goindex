# goindex
Google Drive Directory Index
原作者已经删库了 备份一下
## 功能：
部署在 CloudFlare Workers的小程序。  
可以将 Google Drive 文件以目录形式列出，并直连下载。  
流量走 CloudFlare ，网速由 CloudFlare 决定。

## Demo
[https://index.gd.workers.dev/](https://index.gd.workers.dev/)

## 安装运行
1、访问[https://install.gd.workers.dev/](https://install.gd.workers.dev/)
2、授权认证后，生成部署代码.
3、复制代码 到 CloudFlare 部署.
4、[获取授权链接](https://accounts.google.com/o/oauth2/auth?client_id=202264815644.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&response_type=code&access_type=offline&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fdrive&approval_prompt=auto)
