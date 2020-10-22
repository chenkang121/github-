# github上图片加载不出的解决方法
修改host文件：<br>
打开路径 C:\Windows\System32\drivers\etc 下的 hosts 文件<br>
添加以下语句<br>
``` python
# GitHub Start 
192.30.253.112 Build software better, together 
192.30.253.119 gist.github.com
151.101.184.133 assets-cdn.github.com
151.101.184.133 raw.githubusercontent.com
151.101.184.133 gist.githubusercontent.com
151.101.184.133 cloud.githubusercontent.com
151.101.184.133 camo.githubusercontent.com
151.101.184.133 avatars0.githubusercontent.com
151.101.184.133 avatars1.githubusercontent.com
151.101.184.133 avatars2.githubusercontent.com
151.101.184.133 avatars3.githubusercontent.com
151.101.184.133 Build software better, together
151.101.184.133 avatars5.githubusercontent.com
151.101.184.133 avatars6.githubusercontent.com
151.101.184.133 avatars7.githubusercontent.com
151.101.184.133 Build software better, together
```
刷新页面就行<br>
如果没有权限则需要用**管理员身份**打开记事本，然后用记事本打开**host**文件更改即可。
