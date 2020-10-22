> 一、字体样式属性
> > 1.font-family  
> > 2.unicode编码  
> > 3.font-style  
> > 4.font综合设置字体格式：{font：font-style font-weight font-size/line-height font-family}  
>
> 二、选择器  
> > 1.类选择器(多类名选择器)(.)  
> > 2.ID选择器(唯一)(#)
> > 3.通配符选择器(*)  
> > 4.伪类选择器(:)  
> >
> > > 1)链接伪类选择器(顺序尽量不能乱,l、v、h、a,love hate)  
> > >> :link  
> > >> :visited  
> > >> :hover  
> > >> :active(按下鼠标没松开时)  
> > >
> > > 2)结构伪类选择器  
> > >> :first-child  
> > >> :last-child  
> > >> :nth-child(n)(可选中所有奇数odd/2n+1或偶数even/2n)
> > >> :nth-last-child(n)  
> > >
> > > 3)目标伪类选择器  
> > >> :target(选取当前活动的目标元素)  
> > >
> > > 5.复合选择器  
> > >> 1)交集选择器  
> > >> 2)并集选择器  
> > >> 3)后代选择器  
> > >> 4)子元素选择器  
> > >> 5)属性选择器  
> > >> 6)伪元素选择器  
>
> 三、CSS外观属性  
> > 1.color(颜色)  
> > 2.line-height  
> > 3.text-align  
> > 4.text-indent(首行缩进):单位可百分比、em等  
> > 5.letter-spacing(字间距)  
> > 6.word-spacing(单词间距)  
> > 7.text-shadow:水平位置 垂直位置 模糊距离 阴影颜色(前俩参数必填)  
>
> 四、CSS样式表  
> > 1.行内样式表:(标签名: style="属性1：属性值1; 属性2:属性值2;..." )  
> > 2.外部样式表:link内添加:href="url" type="text/css" rel="stylesheet"  
> > 3.内嵌样式:style标签写到head标签内  
>
> 五、标签显示模式  
> > 1.块级元素:h1-h6、p、div、ul、ol、li等  
> > 2.行内元素:a、strong、b、em、i、del、s、ins、u、span  
> >> (行内元素设置的宽高无效;默认宽度为本身内容的宽度;水平方向的padding和margin可设置,垂直方向无效;只能容纳文本或其他行内元素)  
> >
> > 3.行内块元素:img、input、td等(可设置宽高,)  
> > 4.模式转换:display:inline/block/inline-block