## 响应式设计基础知识

#### 了解响应式布局的基础知识

[Conquering Responsive Layouts](https://courses.kevinpowell.co/conquering-responsive-layouts)通过这个网页学习，每日一个章节。

---

#### 移动优先与桌面优先的方法

在Web开发中，答案是”视情况而定“，大多数情况下，我们建议先使用移动设备。这意味着先构建移动布局，再根据内容需要使布局更加复杂，以适应更大的屏幕尺寸。

**移动优先的好处：** 

1、更好的移动体验。

2、更简单的代码。

3、更快的网站。

4、稍后添加更多内容会更容易。

[移动优先CSS的问题](https://www.youtube.com/watch?v=p3k_IrXLNRc)

---

#### 媒体查询和断点

> [MDN媒体查询](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)

**移动优先方法使用媒体查询和断点的快速指南：** 

1.**从小处着手：** 首先，确保您的网站在小屏幕上看起来不错。这是您的起点。如果您要构建移动优先，那么您首先要关注最小的尺寸。

2.**添加断点：** 现在，决定您希望您的网站何时更改其外观以适应更大的屏幕。

3.**编写媒体查询：** 下面是一个可以在 CSS 文件中使用的简单示例：

```css
/* This is how your website looks on mobile by default */
main {
  display: flex;
  flex-direction: column;
}

/* This changes the layout for screens wider than 48em */
@media (min-width: 48em) {
  main {
    flex-direction: row;
  }
}
```

在定义断点时使用相对单位（例如em和rem）

1、更好的适应。2、跨设备一致3、面向未来


