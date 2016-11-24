---
title: second
date: 2016-10-08 10:26:23
tags:
---
> 1.position:relative;相对定位    给父级加
相对定位作用：指定子集相对谁定位，相对于那个位置定				位
2.position:absolute;/*绝对位置  给子集加
		  设置位置：
		  left：
		  top:
		  right:
		  bottom:
 3. position:fixed;固定定位  相对于浏览器窗口定位
		   不需要设置相对位置
	  	 left：
		 top:
   	 	right:
	 	 bottom:
	如果固定到浏览器窗口   fixed
	如果是某一个模块中定位   absolute


如果父级绝对定位或固定地位，子级绝对定位的时候，不需要给父级加相对定位

如果父级浮动了，子集浮动的时候，不需要给父级加clearfix；
父级浮动相当于也是给子集清楚浮动