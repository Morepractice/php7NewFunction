# php7NewFunction

* git命令

1. 将文件修改加到缓存区;

```git
git add filename
```

2. 将文件修改提交;

```git
git commit -m "提示"
```

3. 将提交文件退回操作;

```git
git reset --hard 版本id/HEAD^(一个^对应上一层，依此类推)
```

4. 查看版本号

```
git log(git reflog)
```

5. 将本地文件和远程github关联;

建立连接
```git
git remote add origin https://github.com/Morepractice/php7NewFunction.git
```

注：若origin已存在则需先使用命令移除
```git
git remote rm origin
```

6. 将本地代码上传至github

```git
git push -u origin master
```

注：若远程库不为空，需先同步

```git
git pull --rebase origin master
```

7. 将远端github代码赋值到本地

```git
git clone sshurl/httpurl
```
