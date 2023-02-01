
**Run the following code in the command line**

### create a new repository

```
echo "# proj1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/JialiZhang1016/proj1.git
git push -u origin main
```


### push an existing repository

```
git remote add origin https://github.com/JialiZhang1016/proj1.git
git branch -M main
git push -u origin main
```

## status

```
git stutas
```

## add

```
git add
```


Git commit always ask me for username and password. The solution is to change the http to ssh. [https://zhuanlan.zhihu.com/p/358721423](https://zhuanlan.zhihu.com/p/358721423)


## Memory your username and password

```
git config --global credential.helper store
```

会在用户主目录下的.gitconfig文件中多加 helper = store

Linux 下查看

```
 vim ~/.gitconfig
```

内容如下：

```
[user]
        name = name
        email = name@qq.com
[credential]
        helper = store
```

然后在项目目录，执行git pull命令，会提示输入账号密码。这次输入账号密码之后，就会记住账号密码，并且会在当前用户根目录下生成一个.git-credentials文件，下一次就不用再输入账号密码了。
