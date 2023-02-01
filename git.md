
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
