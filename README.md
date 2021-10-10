# xm

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

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### 01 初始化项目 托管到github上 步骤
  > 先在git上新建一个含README.md的仓库，修改分支名称master（为了和本地仓库一致--不修改默认会是main）；
  > 本地目录通过 git clone https://github.com/hub-lxy/xm-1010.git 克隆远程项目
  > 通过vue-cli脚手架初始化项目
  > 将项目拷贝到通过git管理的本地目录下
  > 再通过命令
      >> git add.
      >> git commit -m "提交信息"
      >> git remote set-url origin https://（远程git的token值）@github.com/（用户名）/（仓库名）.git
      >> git push -u origin master
