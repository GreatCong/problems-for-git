#GitHub for windows无法启动问题解决

已经不知是第几次遇到这个GitHub for windows 客户端没法启动的问题了，每次都是要Google,在这里标记一下

###当你的系统是Windows XP时，进入用户目录下的：

```javascript
%userprofile%\Local Settings\Apps (例如：C:\Documents & Settings\Username\Local Settings\Apps)
```

###当你的系统是 Windows 7时，进入用户目录下的：

```javascript
%userprofile%\AppData\Local\Apps (例如：C:\users\Username\AppData\Local\Apps)
```

进入以上目录后，删除 2.0 这个文件夹,然后就OK了！

解决方法参考地址：http://superuser.com/questions/483515/github-for-windows-install-error
