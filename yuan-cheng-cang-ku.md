# 1.建立与GitHub的连接

### 1.1 创建SSH Key

```
$ ssh-keygen -t rsa -C "18090597801@163.com"
```

一路回车

### 1.2 在github上添加key值id\_rsa.pub

在用户主目录下的.ssh文件夹中

### 1.3 建立和github账户的连接

```
$ ssh git@github.com
```

# 2.推送本地仓库到github

第一步：在本地仓库下运行

```
$ git remote add origin git@github.com:IM-Chris-Li/learngit.git
```

第二步：本地库和云库间有差异

```
$ git pull origin master
```

第三步：

远程仓库为空时 -u

```
$ git push -u origin master
```

远程仓库不为空

```
$ git push origin master
```

# 3.从远程克隆到本地

```
$ git clone git@github.com:IM-Chris-Li/learngit.git
```



