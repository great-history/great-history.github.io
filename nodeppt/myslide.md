title: nodeppt - 这可能是迄今为止最好的网页版演示库
speaker: 三水清
url: https://github.com/ksky521/nodeppt
js:

    - https://echarts.cdn.apache.org/zh/asset/theme/infographic.js
    plugins:
        - echarts: {theme: infographic}
            - mermaid: {theme: forest}
            - katex

<slide class="bg-black-blue aligncenter" image="https://cn.bing.com/az/hprichbg/rb/RainierDawn_EN-AU3730494945_1920x1080.jpg .dark">

# 在Hexo-fluid主题中如何使用nodeppt{.text-landing.text-shadow}

这可能是迄今为止最好的网页版演示库 {.text-intro.animated.fadeInUp.delay-500}

[:fa-github: Github](https://github.com/ksky521/nodeppt){.button.ghost.animated.flipInX.delay-1200}

<slide :class="size-30 aligncenter">

### Install

---

在个人博客文件夹的根目录下打开Git Bash，输入命令

`npm install -g nodeppt` {.animated.fadeInUp}

<slide :class="size-40 aligncenter">

### Commands

---

在根目录下的public文件夹中新建一个名为nodeppt的子文件夹，然后对这个文件夹进行右键Git Bash（一定要在这个文件夹下进行）

```shell {.animated.fadeInUp}
 # create a new slide with an official template
$ nodeppt new slide.md

# create a new slide straight from a github template
$ nodeppt new slide.md -t username/repo

# start local sever show slide
$ nodeppt serve slide.md

# to build a slide
$ nodeppt build slide.md
```

每次修改完之后要重新build一下

