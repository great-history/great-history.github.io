title: nodeppt markdown 演示
speaker: 三水清
url: https://github.com/ksky521/nodeppt
js:
    \- https://www.echartsjs.com/asset/theme/shine.js
prismTheme: solarizedlight
plugins:
    \- echarts
    \- mermaid
    \- katex

<slide class="bg-black-blue aligncenter" image="https://cn.bing.com/az/hprichbg/rb/RainierDawn_EN-AU3730494945_1920x1080.jpg .dark">

# ABA_TLG {.text-landing.text-shadow}

这可能是迄今为止最好的网页版演示库 {.text-intro.animated.fadeInUp.delay-500}

[:fa-github: Github](https://github.com/ksky521/nodeppt){.button.ghost.animated.flipInX.delay-1200}

<slide :class="size-30 aligncenter">

### Install

`npm install -g nodeppt` {.animated.fadeInUp}

<slide :class="size-40 aligncenter">

### Commands

---

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

<slide class="bg-gradient-r" :class=" size-40 aligncenter" image="https://cn.bing.com/az/hprichbg/rb/WinterLynx_ZH-CN7158207296_1920x1080.jpg .dark">