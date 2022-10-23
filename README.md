# Lerna 大仓项目开发流程

### 基础命令


#### lerna init 

初始化一个通过lerna来管理的大仓项目


#### lerna create

创建一个交予lerna大仓进行管理的package


#### lerna run xxx

执行这个命令会将所有的package对应的命令进行执行。lerna run tasks

例如: ```lerna run build```

这个命令执行后，lerna项目中对应的所有package都会执行对应的 build命令

```lerna run test``` 同理


#### lerna run xxx --scope=xxx

执行这个命令将会运行某个package的对应的命令

### 配合工具

#### nx

https://nx.dev/ 

nx是一个智能、快速和可扩展的构建系统，具有一流的 monorepo 支持和强大的集成，具体的使用不在这里做展开描述

NX 可以做分布式的缓存和本地的缓存两种形式来帮助lerna提升构建和测试的效率kexi
