# grid布局

grid布局三大概念:  

1. 网格容器  
2. 网格项目

```css
	body {
		display:grid; //生成一个块级网格
		display:inline-gride;  //生成一个行级网格
		display:subgrid; //从父节点获取行/列大小(父级是grid item)
	}
```

Grid Container的全部属性:

```css
body {
   display: grid;
   grid-template-columns  
   grid-template-rows
   grid-template-areas
   grid-template
   
   grid-column-gap
   grid-row-gap
   grid-gap
   
   justify-items: start / end / center / stretch(默认值);
   align-items: start / end / center / stretch(默认值);
   
   justify-content: start / end / center / stretch / space-around / space-between / space-evenly ; //(不是很懂)
   align-content: start / end / center / stretch / space-around / space-between / space-evenly ; //(不是很懂)
   
   grid-auto-columns
   grid-auto-rows
   grid-auto-flow
   grid
  }
```

Grid items的全部属性:

```css
	grid-column-start
	grid-column-end
	grid-row-start
	grid-row-end
	grid-column
	grid-row
	
	grid-area
	justify-self
	align-self
```