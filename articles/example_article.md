---
title: 完整多媒体内容展示
date: 2023-11-15
author: 示例作者
tags: [多媒体, 示例, 教程]
---

# 完整多媒体内容展示

## 1. 图片展示

### Twitch图标
![Twitch图标](./images/1.png "Twitch平台图标")

*图片属性：*
- 类型：PNG
- 尺寸：146x123像素
- 用途：社交媒体标识

## 2. 视频展示

### 卡牌翻转动画
<video controls width="100%">
  <source src="video/1.mp4" type="video/mp4">
  您的浏览器不支持视频标签
</video>

*视频属性：*
- 时长：15秒
- 分辨率：720p
- 文件大小：3.2MB
- 用途：UI动画效果

## 3. 音频展示

### 尴尬惊吓音效
<audio controls>
  <source src="audio/1.mp3" type="audio/mpeg">
  您的浏览器不支持音频元素
</audio>

*音频属性：*
- 时长：2秒
- 格式：MP3
- 采样率：44.1kHz
- 用途：音效

## 4. 多媒体组合示例

```html
<div class="media-container">
  <img src="./images/twitch_icon_146123.png" alt="Twitch图标">
  <video controls>
    <source src="video/卡牌翻转模板_爱给网_aigei_com.mp4" type="video/mp4">
  </video>
  <audio controls>
    <source src="audio/尴尬惊吓_爱给网_aigei_com.mp3" type="audio/mpeg">
  </audio>
</div>
```

# 使用指南

1. 所有媒体文件应放在对应的`images`、`video`和`audio`目录中
2. 使用相对路径引用文件
3. 为每个媒体元素添加描述性文本和属性说明