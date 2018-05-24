# grid布局

grid布局:  

1. 网格容器(Grid Container)  
2. 网格项(Grid Item)
3. 网格线(Grid Line)
4. 网格轨道(Grid Track)
5. 网格单元(Grid Cell)
6. 网格区(Grid Area)
7. repeat()简化

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
   display: grid / inline-grid / subgrid; (grid:生成块级网格,inline-grid:生成行内网格,subgrid:继承其父级网格容器的行列大小,如果网格容器本身是网格项)
   grid-template-columns: [line-name] track-size(轨道大小.表示方法:px,百分比,fr,auto) [line-name(网格线名字)]
   grid-template-rows: 同上
   grid-template-areas
  
   (网格单元间隔,注:间隔仅作用于网格单元之间,不作用于容器边缘)
   grid-column-gap: Npx
   grid-row-gap
   grid-gap
   
   (网格单元的对齐方式,总网格的区域等于网格容器)
   justify-items(垂直于列网格线对齐): start / end / center / stretch(填满,默认值);
   align-items(垂直于行网格线对齐): start / end / center / stretch(填满,默认值);
   
   (网格单元的对齐方式,总网格的区域小于网格容器)
   justify-content: start / end / center / stretch / space-around / space-between / space-evenly ; 
   align-content: start / end / center / stretch / space-around / space-between / space-evenly ; 
   
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
