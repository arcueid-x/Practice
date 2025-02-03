> 这次练习将尝试移动端布局，学习移动端布局

## 移动端布局Notes

#### 实现响应式布局的三个要素：

1、viewport视口设置

2、@media媒体查询

3、不要写死的尺寸

* <font color=#600>多用百分比宽度来确定布局！</font>

* 多用rem，em来确定布局尺寸

* 多用vh，vw来确定布局尺寸

PPK大神的关于三个Viewport的理论

1、layout viewport

2、visual viewport

3、ideal viewport  理想视口，移动端响应式布局

```html
<meta name='viewport' content='width=device-width,initial-scale=1.0,maximun-scale=1.0,user-scalable=no'>
```

*width:* 设置layout width的宽度

*initial-scale：* 设置页面的初始缩放值

*user-scalable：* 是否允许用户进行缩放

---

#### @media的引入方式

> 制作响应式网页

*1、直接引入：* 

```css
@media screen and (max-width:960px){
    //写样式
    body{}
}
```

*2、外接式：* 

```css
<link rel='stylesheet' type='text/css' media='screen and (max-width:960px)' href='...'>
```

> 在外接CSS中写样式

---

#### media类型

> print，all，screen等等

---

#### 媒体特性介绍

*横屏显示：* 

```css
@media all and (orientation: landscape){
    body{}
}
```

*竖屏显示：* 

```css
@media all and (orientation: portrait){
    body{}
}
```

---

#### 常见media的宽度

*超小屏幕：* 手机 < 768px

*小屏幕：* 平板 > 768px

*中等屏幕：* 桌面显示器 > 992px

*大屏幕：* > 1200px

---

#### rem使用&&em使用

> 对比PC和m端的设计稿，看看有什么区别，通常都会使用flex布局。宽度尽量用百分比，间距，高度，字体大小 使用em

em：相对于当前元素字体大小的倍数

rem：相对于根元素字体大小的倍数

---


