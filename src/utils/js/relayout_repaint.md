## 重排和重绘

### 重排

**重排**(Relayout/Reflow)就是根据渲染树中每个渲染对象的信息，计算出各自渲染对象的几何信息（DOM对象的位置和尺寸大小），并将其安置在界面中的正确位置。

引起重排的操作有：

- 页面首次渲染
- 浏览器窗口大小发生改变
- 元素尺寸或位置发生改变
- 元素内容变化（文字数量或图片大小等等）
- 元素字体大小变化
- 添加或删除可见的DOM元素
- 激活CSS伪类（例如:hover）
- 设置style属性
- 查询某些属性或调用某些方法。

### 重绘

**重绘**(Repaint)就是当页面中元素样式的改变并不影响它在文档流中的位置时，例如更改了字体颜色，浏览器会将新样式赋予给元素并重新绘制的过程。

### 参考

内容来源 https://juejin.im/post/5b543e26e51d4518f54404e4
