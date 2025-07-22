---
title: 文章标题
date: 2023-01-01
author: 作者名
tags: 标签1, 标签2
---

# 中文内容

这里是文章的中文内容...

# English Content

This is the English content of the article...

# Markdown 语法指南

## 1. 超链接

- 普通链接：
  `[显示文本](https://example.com)`
  示例：[百度](https://www.baidu.com)

- 直接URL：
  `<https://example.com>`
  示例：<https://www.baidu.com>

- 引用式链接：
  ```
  [显示文本][id]
  
  [id]: https://example.com "可选标题"
  ```

## 2. 图片

- 基本语法：
  `![替代文本](图片URL "可选标题")`
  示例：![示例图片](https://example.com/image.jpg "图片标题")

- 引用式图片：
  ```
  ![替代文本][图片id]
  
  [图片id]: https://example.com/image.jpg "可选标题"
  ```

- 本地图片：
  `![本地图片](./images/local.jpg)`
  (请将图片放在/articles/images/目录下)

## 3. 音频

使用HTML5的`<audio>`标签来嵌入音频：

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  <source src="audio.ogg" type="audio/ogg">
  您的浏览器不支持音频元素
</audio>
```

属性说明：
- `controls`: 显示播放控件
- `autoplay`: 自动播放（注意：许多浏览器会阻止自动播放）
- `loop`: 循环播放
- `muted`: 静音

支持多种音频格式（MP3, OGG, WAV等），建议提供多个格式以确保兼容性。

本地音频文件应放在`/articles/audio/`目录下。

# 视频添加指南

## 本地视频
1. 将视频文件放入`articles/audio/`目录
2. 使用以下Markdown语法引用：
```markdown
<video controls>
  <source src="video/视频文件名.mp4" type="video/mp4">
  您的浏览器不支持视频标签
</video>
```

## 在线视频
1. 对于YouTube视频，使用以下格式：
```markdown
[![视频标题](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID)
```
2. 对于其他平台视频，直接嵌入iframe代码

## 视频最佳实践
- 视频时长建议控制在5分钟以内
- 分辨率不低于720p
- 文件大小不超过50MB
- 添加简短的视频描述

# 文章正文从这里开始...