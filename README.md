# react-cli

初始化react项目的命令行工具

## 目录结构

```markdown
react-cli
├── LICENSE
├── README.md
├── bin
│   └── r-cli
├── package-lock.json
├── package.json
└── src
    ├── command
    ├── config
    ├── index.js
    └── utils
```

## 安装方式

```shell
npm i @chuugoku/react-cli -g
```

## 使用方法

```shell
react-cli init <projectName> -t -f
```

-t --typescript 使用typescript模板  

-f --force 强制覆盖已经存在的目录
