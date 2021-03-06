# gif切图片帧工具

- [工具地址](https://lingxiaoyi.github.io/umi-imgcrop)  

## 使用

- 下载项目代码

```bash
git clone https://github.com/lingxiaoyi/umi-imgcrop.git
```

- 进入目录安装依赖，国内用户推荐使用 cnpm 进行加速

```bash
npm i
```

或借助cnpm加速

- 启动本地服务器

```bash
npm start
```

## 使用教程

工具从上往下一共分为3个区域

### 画布区

将分解的图片和添加的文字显示在画布中

### 选择区

1. 上传图片 直接本电脑中选中文件上传
2. 填写链接输入框 填写一个线上的gif图片地址，如果图片解析不出来，解决方法是下载图片出来，再使用上方上传，原因是图片不支持跨域
3. 分段选项 将gif解析出来的图片分成几个区域显示，支持2 3 4
4. 帧间隔 预览或者生成的gif中每一帧图片的显示间隔时间，最小取值0.02，单位s
5. 图片大小 生成图片的大小，默认300px，单位px
6. 预览图片 仅供预览观看，默认宽300px，高自适应
7. 生成图片 可以下载图片使用

### 属性操作区

- 每一个方格对应画布中每一个区域的文字属性
- 最后一个方格可以控制操作全部文字  
**注: 文字位置不要偏离对应的那张图片中，要不然会出现图片消失或显示不完整**

### 属性详解

| 属性   | 说明               | 默认                            |
| ------ | ------------------ | ------------------------------- |
| 帧数   | 每一段区域图片数量 | 自动计算，也可点击下方+ -号设置 |
| 左边距 | 文字距离左边框距离 | 0                               |
| 上边距 | 文字距离上边框距离 | 0                               |

## 备注

- 本人是在谷歌浏览器调试开发的，没有考虑任何兼容问题，最好在谷歌浏览器使用
- 点击生成图片后，可以将生成图片下载出来，如需使用请注意版权问题，如出现版权纠纷，本库概不负责
- 如有其它问题请下方留言
  
## 特别感谢

- GIF图片分帧[buzzfeed/libgif-js](https://github.com/buzzfeed/libgif-js)
- canvas操作[fabric.js](http://fabricjs.com/docs/fabric.Canvas.html)
- 生成GIF图片[yahoo/gifshot](https://github.com/yahoo/gifshot)

>创作不易，如果对你有帮助，请移步[gitHub地址](https://github.com/lingxiaoyi/umi-imgcrop)给个星星 star✨✨ 谢谢
