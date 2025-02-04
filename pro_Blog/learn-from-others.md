## Notes

> 关于var()

在根上进行赋值，类似于C语言的宏定义

```css
:root{
    :root{
    --yellow: hsl(47, 88%, 63%);
    --white: hsl(0, 0%, 100%);
    --grey: hsl(0, 0%, 50%);
    --black: hsl(0, 0%, 7%);}
}
```

之后就可以通过var()的形式，用变量名代替值

```css
var(--yellow)--> hsl(47, 88%, 63%)
var(--white)--> hsl(0, 0%, 100%)
```
