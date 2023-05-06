# cenos error:14090086:SSL routines

发现Linux系统有更新本地证书的命令，不同系统命令不同，CentOS操作如下 ：

安装ca证书工具
```
yum install ca-certificates -y
```
更新证书
```
update-ca-trust
```
问题解决。
