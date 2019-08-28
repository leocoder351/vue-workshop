# vue-workshop

Vue高阶练习

## 准备

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/) version 6+

## 步骤

1. clone本项目
``` bash
git clone https://github.com/yyx990803/vue-advanced-workshop.git
```

2. 安装依赖
``` bash
cd vue-workshop
npm install
```

## 使用

### 切换工作分支和答案分支

本项目包含2个分支：`master` 分支是工作分支，用来练习，`solution`分支包含每个练习的完整答案

切换`solution`分支请使用以下命令：

``` bash
git checkout solution
```

返回`master`分支：

``` bash
git checkout master
```

### 保存

当想要切换到solution分支时，不要忘记提交commit：
``` bash
git add -A
git commit -m 'working on exercise 1.1'
git checkout solution
```

### 自动化测试

每个练习都配套了自动化测试用例，运行测试用例（e.g. 1.1），请执行：
``` bash
npm test -- -t 1.1
```

同时也可以自动监听文件改变并运行测试用例：
``` bash
npm run watch
```
