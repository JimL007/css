# Flex布局

1. 三大核心概念:
	* flex容器
	* flex项
	* 排列方向(direction) / 主轴

```css
	body {
		display: -webkit-flex; //兼容webkit内核的浏览器
		display: flex;
	}
```

2. 容器属性:  
	1. flex-direction: row / row-reverse / column / column-reverse; // (默认row)  
	2. flex-wrap: nowrap / wrap / wrap-reverse; // (默认nowrap)  
	3. flex-flow: row nowrap; // (默认 row nowrap)  
	4. justify-content: flex-start / flex-end / center / space-between / space-around;  // *(默认 flex-start)
	5. align-items: flex-start / flex-end / center / baseline / stretch; // (默认stretch)  
	6. align-content: flex-start | flex-end | center | space-between | space-around | stretch;

3. 项目属性:
	1. order: integer; // 越小越靠前,默认0
	2. flex-grow: number; // 默认0,即如果存在剩余空间,也不放大  
	3. flex-shrink: number; // 默认1,即如果空间不足,自动缩小  
	4. flex-basis: length / auto; // 默认auto,
	5. flex: flex-grow  flex-shrink flex-basis;
	6. align-self: auto / flex-start / flex-end / center / baseline / stretch;  // 默认值为auto，表示继承父元素的align-items属性，如果没有父元素，则等同于stretch。  
	  
	
	
