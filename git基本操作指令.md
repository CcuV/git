# 使用git 版本控制总结
### git：术语和工作流程

![image-20230923173534088](C:\Users\wanha\AppData\Roaming\Typora\typora-user-images\image-20230923173534088.png)

### 下载： https://git-scm.com/downloads

确认git  version：`git --version`

```
git --version
git version 2.42.0.windows.2
```

建议：默认设置

###  git 命令

`git<verb><options><path>`

### git add 指令

![image-20230923174525191](C:\Users\wanha\AppData\Roaming\Typora\typora-user-images\image-20230923174525191.png)

`git add`：将新文件和修改过的文件放进当前目录

``` 
git add
```

git add -A: 对整个版本库中的所有更改（新增、添加和删除文件）进行阶段化处理

```
git add -A
```

`git add -u`：对已跟踪文件进行阶段性修改/删除

```
git add -u
```

### 提交更改 Commit Changes

![image-20230923175105866](C:\Users\wanha\AppData\Roaming\Typora\typora-user-images\image-20230923175105866.png)

`git commit -m<message>`

```
git commit -m "add new file or something u wannna update"
```

### 推送到远程仓库 git push

![image-20230923175300415](C:\Users\wanha\AppData\Roaming\Typora\typora-user-images\image-20230923175300415.png)

`git push`

```
git push
```

### 拉取更改 git pull

![image-20230923175451797](C:\Users\wanha\AppData\Roaming\Typora\typora-user-images\image-20230923175451797.png)