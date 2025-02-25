## 标签的含义

**main**

HTML <main>元素**呈现了文档的 [<body>](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/body) 或应用的主体部分。主体部分由与文档直接相关，或者扩展于文档的中心主题、应用的主要功能部分的内容组成。

> main一般不包含侧边栏，导航栏，版权信息，网站logo，搜索框

**section**

**HTML <section> 元素**表示 HTML 文档中一个通用独立章节，它没有更具体的语义元素来表示。一般来说会包含一个标题。

> section后面，应该跟着h1-h6，是一个通用的分结元素

---

**:root**

```css
:root{
    --green:#006600;
}
//之后就可以用var(--green)代替，#006600，使代码更加直观
```

---

### li前面的修饰符

*marker：* 

```css
li::marker{
    color:var(--green);//更改li前面的符号的颜色为绿色
}
ul{
    margin-left:0.5rem;//更改修饰符的位置
}
```

---

### letter-spacing(字符间距)

```css
p{
    letter-spacing:1px;//控制单个字母之间的空隙
}
```

---

### max-width

用于设置动态的宽度，并且设置一个最大的阈值。一般随着视口的变化而变化，但是需要提前设置一个相对的单位设置宽度，这样才会随着视口变化而变化，并且到达max-width停止。


