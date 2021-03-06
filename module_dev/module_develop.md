# 搭建模块化开发

 模块化开发以及不是什么先进的东西了，利用VUE和REACT 不仅能够实现模块化开发，而且还有MVVM的开发模式，那为什么还要自己搭建模块化开发的脚手架呢，主要目的有两个：

1. 应对轻量的活动页面，并不是所有的页面都是需要大量数据驱动的不是吗？
2. 期望能够兼容到IE8，VUE和React 想要做到IE8兼容可以通过很多补丁来实现，网上有一些经验，但是也有人碰到很多坑，有很多不确定的因素。

基于上面两个因素的考虑为了能够提升开发效率，期望通过，模块化开发+组件库的方式提升开发效率。

### 期望实现的功能

#### CSS：

* 支持css预处理（sass/less/stylus至少一种）
* 支持自动添加浏览器前缀

**JS：**

* 支持引入esm/cjs 格式的js库
* js入口文件支持多个（最好文件名能灵活改动）
* 支持使用requirejs组件
* 支持sourcemap
* 兼容ie8

**IMAGE：**

* 支持压缩

**其他资源：**

* 其他资源（音频，外部插件css，图片等）支持复制到打包目录

**目录**

* 支持子项目
* 支持资源路径加版本号

**发布：**

* 支持命令方式发布
* 支持线上构建

**缓存：**

* 支持资源文件自动添中加版本号

**调试：**

* 支持本地调试

 





