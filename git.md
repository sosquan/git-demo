## git 常用命令

```git
git config --global user.name 用户名
git config --global user.email 邮箱
git init 
git status
git add 文件名
git commit -m '日志信息' 文件名
git reflog 
git reset --hard 版本号
```

---
### 3.1 设置用户签名
---

```
git config --global user.name 用户名
git config --global user.email 邮箱
```

> 说明：与将来登录github的账号没有关系，签名的作用是区分不同操作者身份。必须设置用户签名，否则无法提交。

---
### 3.2 初始化本地库
---

```git init```

### 3.3 查看本地库状态

```git status```

### 3.4 将文件添加到暂存区

```git add 文件名```

### 3.5 提交本地库

```git commit -m '日志信息' 文件名```

### 3.6 查询版本信息

```git reflog```

### 3.7 版本穿梭

```git reset --hard 版本号```



## 4、什么是分支

> 在版本控制过程中，同时推进多个任务（开发，应用，测试等），为每个任务，我们可以创建每个任务的单独分支，开发自己的分支，不会影响主线分支的运行。分支底层就是指针的应用。

### 4.1 查看分支

```git branch -v```

### 4.2 创建分支

```git branch 分支名```

### 4.3 切换分支

```git checkout 分支名```

### 4.4 合并分支（把指定分支合并到当前分支上）

```git merge 分支名```

### 4.5 冲突合并

> 产生冲突的原因：合并分支时，两个分支在同一个文件的同一个位置有两套完全不同的修改。git无法替我们决定选择哪个，必须认为决定新代码内容。

> 冲突解决需要修改文件内容并重新进行添加暂存区和提交动作，并且被合并分支的内容不会发生改变。


## 5.GitHub操作
GitHub网址：[github](www.github.com)
PS:全球最大同行交友网站，技术宅男的天堂，新世界的大门，你还在等什么？

|账号|姓名|邮箱|
|:---:|:---:|:---:|
|atguiguyueyue|岳不群|atguiguyueyue@aliyun.com|
|atguiguhuchong |令狐冲|atguiguhuchong@qq.com|
|atguigububai|东方不败|atguigububai@163.com|

### 5.1 创建远程库别名

```git remote -v```             
> 查看当前远程库

```git remote 别名 远程库地址```
> 创建远程库

```git push 别名 分支名```











