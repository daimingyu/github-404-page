## github_404_page

![Alt text](https://raw.githubusercontent.com/daimingyu/photos/master/g_404.gif)

## 一、前言

效果预览 : [Github-404](https://github.com/vajoy/master/index.html)<br>
参考文章一 : [Kong Cheng - 仿github404页面特效](https://segmentfault.com/a/1190000010288250)<br>
参考文章二 : [VaJoy Larn - 扒皮GitHub 404的图片层次轴动特效](https://www.cnblogs.com/vajoy/p/3901526.html)

## 二、文件夹

* /js：一个plaxify.js库文件。
* /photos：资源图片
* /index.html : 入口文件

## 三、重要代码

plaxify.js是整个页面的核心,它封装了移动功能,函数使用说明如下：
```
window.plaxify(HTMLDomElement, {
    xRange: Number,
    yRange: Number,
    invert: Boolenn
})
param HTMLDomElement : dom元素
param xRange : x轴移动的最大范围
param yRange : y轴移动的最大范围
param invert : 是否与鼠标移动方向相反
```
