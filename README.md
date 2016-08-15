# Git的基本操作

## ps:操作这些一定在本地仓库打开Git命令行来进行操作。

分以下一些操作：

1、初始化本地仓库
```js
  $ git init
  
```
2、从服务器克隆代码到本地仓库

```js
  $ git clone htts://github.com/lxchenyong/jeff.git
```

3、文件有增、删及修改的操作后，首先添加到缓存
```js
   $ git add .  //指里面所有的文件都添加到缓存
   $ git add README.md  //指定文件添加到缓存
   $ git add README.md RText.md  //添加多个文件到缓存区，文件之间用空格隔开
```

4、删除缓存区的文件
```js
   $ git rm README.md
```

5、提交到本地仓库
```js
   $ git commit  -m "提交的注解"
```

6、提交到远程服务器
```js
  $ git push  htts://github.com/lxchenyong/jeff.git
```

7、更新最新远程服务器的代码到本地仓库
```js
   $ git pull
```