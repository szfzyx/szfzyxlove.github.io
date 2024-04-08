---
title: Study
date: 
categories:
- c/cpp NOTES
top: true
---
	c语言里面表示n的多少次方应该使用cmath中的pow()函数，pow(x,y)中x代表底数，y代表指数；
1e-4代表万分之一的意思
	cpp里面的sort()函数，位于algorithm库里，直接sort(start,end)，这里面是左闭右开的，就
是说我们排序一个数组，参数是（起始地址，末尾地址+1）；对于int a[10]这样的数组，直接sort(a,a+10);
并且默认是升序排序，如果要降序，自己定义一个bool函数cmp，return前参 > 后参，到时候sort(start,end,cmp)就行；
