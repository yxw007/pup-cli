<h1 align="center">Pup-cli</h1>

<p align="center">English | <a href="./Readme_zh-CN.md">简体中文</a></p>

<p style="text-indent:2em">
Pup-cli is a very simple scaffolding tool that you may have for vue-CLI why use this pup-CLI of yours? If you are a webpack user before, using vue-CLI generated projects, you will not see the webpack configuration file, because vue-CLI encapsulated webpack layer, so you are confused about how to configure, of course, according to the official website you can slowly configure, but it will take a lot of time.So I thought to use a template project to set up a relatively complete development environment, and then use puP-CLI directly select template project to generate projects, and then can quickly develop.
</p>

## Built-in template

- [vue2.x-webpack4.x](https://github.com/yxw007/vue2.x-webpack.x)(Available)
- [vue2.x-webpack5.x](https://github.com/yxw007/vue2.x-webpack.x)(Available)
- [vue3.x-webpack5.x](https://github.com/yxw007/vue3.x-webpack5.x)(Not available)

## Quick start

1. global installation:

```
npm install -g pup-cli
```

2. create project

```
pup-cli create project_name_xxx
```

## More Instructions

- <p style="color:red;font-weight:bold">If you have a template project already built, you can use pup-cli add to add your template project to this scaffold template configuration table, so that you can quickly generate your own template project items.</p>

  > ![](https://cdn.jsdelivr.net/gh/yxw007/BlogPicBed@master/img/20211210234210.png)

- command list

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

## Reference

- https://www.npmjs.com/package/inquirer#questions
- https://www.npmjs.com/package/download-git-repo

## License

MIT © 2022 Potter
