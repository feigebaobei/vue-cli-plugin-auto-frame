## overview
这是`@vue/cli`插件的框架。

## 目录结构
```
├── README.md
├── generator.js  # generator（可选）
					修改指定文件/创建指定文件（夹）
├── index.js      # service 插件
					修改webpack配置
					创建/修改vue-cli-service命令
├── package.json
├── prompts.js    # prompt 文件（可选）
└── ui.js         # Vue UI 集成（可选）
```

## install
```
// 从本地安装
npm i -D 绝对路径
// 从远程安装
npm i -D vue-cli-plugin-auto-frame
```
## usage
```
vue invoke vue-cli-plugin-auto-frame
```

## expection
1. 向工程化/规范化努力。
2. 按选择结果安装插件。
3. 预置基本页面结构。支持命令行。
4. 支持vue ui。
