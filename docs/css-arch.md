# CSS 架构

## 类样式规范

```css
.foo {
  /* 定位 positioning */
  position: absolute;
  top: 0;
  right: 0;
  z-index: 1;

  /* 盒模型 box model */
  display: inline-block;
  float: left;
  width: 100px;
  height: 100px;

  /* 文字 typography */
  font: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 14px;
  color: #333;
  line-height: 1.5;

  /* 皮肤 visual | skin */
  background-color: #f5f5f5;
  border: 1px solid #e5e5e5;

  /* misc */
  opacity: 0.5;
}

.foo:hover {
}
```

## CSS Rules
