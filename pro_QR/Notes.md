## 边框相关属性

> border-radius，outline

*border-radius：* radius指的是圆的半径

```css
border-radius:10px;//圆的半径为10px
border-radius:10%;//圆的半径为父元素
border-radius:10px 20px 30px 40px;//左上，右上，左下，右下
//也可以逐个角单独设置
```

*也可以绘制椭圆：* 

```css
border-top-left-radius:100px 50px;表示长半轴，短半轴//同时也是先横向，再竖向
...//其他角度
//因此，我有设想如果处理长方形可以使用这个方法
```

> 也可以用border-radius总的来写椭圆（顺序为：左上  左下/右上  右下）

---

*outline的属性：* 

```css
outline-width:20px;
outline-color:blue;
outline-style:solid;
outline-offset:10px;//偏移，向里，向外偏移
```

> outline贴着border，且不参与盒子大小计算，不占位，

*复合属性：* 

```css
outline:20px blue solid;//不挑顺序
outline-offset:10px;//单独写
```

---


