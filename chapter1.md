# 1.Git简介

Git是分布式版本控制系统

# 2.Git使用方法

### 2.1 创建版本库

第一步：在本地创建版本库目录

第二步：在该目录下使用命令

```
$ git init
```

### 2.2 文件放入git仓库

第一步：

```bash
$ git add readme.txt
```

第二步：

```
$ git commit -m "write remark"
```

### 2.3 查看仓库当前状态

```
$ git status
```

### 2.4 查看修改内容

若用git status发现文件被修改，则可用以下命令查看修改的内容

```
$ git diff readme.txt
```

> git diff 比较的是工作区与暂存区的区别
>
> git diff --cached 比较的是暂存区与仓库分支的区别

### 2.5 查看提交日志

查看提交历史，方便版本退回

```
$ git log
```

2.6 版本退回

```
$ git reset --hard HEAD^
```

```
$ git reset --hard commit_id
```



