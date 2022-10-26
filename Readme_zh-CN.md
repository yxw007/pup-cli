<h1 align="center">Pup-cli</h1>

<p align="center">中文 | <a href="./README.md">简体英文</a></p>

<p style="text-indent:2em">
Pup-cli 是一个非常简单的脚手架工具，你可能会为有 vue-cli 为啥要用你这 pup-cli? 如果你以前是 webpack 的使用者，利用 vue-cli 生成的项目，你会看不到 webpack 的配置文件，因为 vue-cli 把 webpack 封装了一层，导致你摸不着头脑要怎么要配置，当然按照官网的文档你可以慢慢配好，但是这样会让人花费不少时间，所以我就想着用一个模板工程把一个相对完善的开发环境配好，然后利用 pup-cli 直接选择模板工程生成项目，然后就可以快速开发了。
</p>

## 内置模板工程

- [vue2.x-webpack4.x](https://github.com/yxw007/vue2.x-webpack.x)(已可用)
- [vue2.x-webpack5.x](https://github.com/yxw007/vue2.x-webpack.x)(已可用)
- [vue3.x-webpack5.x](https://github.com/yxw007/vue3.x-webpack5.x)(暂不可用)

## 快速开始

1. 全局安装：

```
npm install -g pup-cli
```

2. 创建项目

```
pup-cli create project_name_xxx
```

## 补充说明

- <p style="color:red;font-weight:bold">假如你有已经搭好的模板工程，可以利用 pup-cli add 将自己的模板工程添加到此脚手架模板配置表中，方便以后自己快速生成自己的模板工程项目)</p>

  > ![](https://cdn.jsdelivr.net/gh/yxw007/BlogPicBed@master//img/20221026115837.jpg)

- 命令表

  ```
  Usage: pup-cli <command> [options]

  Options:
    -V, --version   output the version number
    -h, --help      display help for command

  Commands:
    add             add a new template
    delete          delete a template
    list            list all the templates
    create          create a new project from a template
  ```

## 参考资料

- https://www.npmjs.com/package/inquirer#questions
- https://www.npmjs.com/package/download-git-repo

## 许可证

MIT © 2022 Potter
