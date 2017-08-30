# apache-httpd

## 通过简单命令实现对 apache httpd 配置进行修改;
#### 主要功能修改 httpd.conf
命令:
```
1. 配置域名
httpdev --host www.xinwenchao.com
```
```
2. 配置 apache 环境变量, 让命令行支持 httpd 命令, 主要用于开启, 关闭, 重启 httpd 服务器
httpdev --env Apache安装路径
```
```
3. 添加一个虚拟路径
httpdev --add 文件夹路径 [别名]
```
```
4. 删除一个虚拟路径
httpdev --del 文件夹路径 [别名]
```
```
5. 开启 https
httpdev --https
```
```
6. 开启 https
httpdev --https
```