# project-one

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# git笔记
## git基础命令
    * 初始化git init
    * 查看状态git status
    * 添加到暂存区git add +添加的目录或文件
    * 分支git commit -m "备注"
    * 查看修改状态git log或git reflog
        整洁一点：git log --pretty=oneline
        退出按q键
## 分支管理
    1. 查看分支：git branch
	    *当前分支
    2. 创建并自动切换到创建的分支上：git checkout -b 分支名
    3. 删除本地分支：git branch -d 分支名（当前分支不能删除）

    /回退/
    1. 放弃工作区的修改：git checkout -- 要放弃修改的文件
    2. 放弃暂存区的修改：git reset HEAD 要回退的文件
    3. 回退分支版本：git reset --hard +commit_id

