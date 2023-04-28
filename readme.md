## vite-creater

这是一款可以自定义策略的vite自动化cil脚本程序，基于nodeJS

```shell
npm i vite-creater -g
```

```shell
C:\Users\Administrator>vcreater
Usage: vite-creater [options] [command]

vite-creater是一款用于快速创建vite项目的脚手架工具，目前仅支持vue项目的创建。

Options:
  -V, --version                 output the version number
  -h, --help                    display help for command

Commands:
  init [options] <projectName>  使用vite-creater创建项目
  help [command]                display help for command

C:\Users\Administrator>
```

当输出以上信息时，安装成功

### 快速开始

```shell
vcreater init yourProjectName
```

即可快速创建 vite 项目

### 自定义方案

vite-creater支持自定义方案，只需选择 `进入选配` 即可进入选装模式

此外，在选配模式中，vite-creater还支持自定义第三方包，并保存策略。

保存后，在下一次启动时即可看到自定义策略，选取即可快速按照策略启动创建。


