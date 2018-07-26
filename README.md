# mydoc
学习笔记
1、安装node.js
验证命令: node -v

2、安装npm(NodeJS新版本已经集成，不需要单独安装)
验证命令: npm -v

3、配置npm的全局存放路径和cache路径
(a)在node安装目录下(如:D:\Program Files\nodejs\)新建目录 node_global 和 node_cache
(b)cmd中执行命令:
npm config set prefix "D:\Program Files\nodejs\node_global"
npm config set cache "D:\Program Files\nodejs\node_cache"
(c)环境变量配置
新增环境变量 NODE_PATH:    D:\Program Files\nodejs\node_global
path 环境变量后追加:              ;%NODE_PATH%

4、配置ntp的registry地址:
npm config set registry http://rnd-mirrors.huawei.com/npm-registry/

5、安装Typescript
npm install -g typescript typings
验证命令: tsc -v

6、安装Angular CLI
npm install -g @angular/cli
验证命令: ng -v
