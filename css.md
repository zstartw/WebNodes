## 长度和百分比

- px （如font-size: 12px ）是像素的单位。
- em （如font-size: 2em ）是字体计算大小的单位。 例如，“2em”是当前字体大小的两倍。
- pt （如font-size: 12pt ）是点的单位，通常用于印刷媒体中的测量。
- % （如width: 80% ）是单位...等待它...百分比

## 颜色

以下指定完全打开为红色或红色的值都会产生相同的结果：
- red
- rgb(255,0,0)
- rgb(100%,0%,0%)
- #ff0000
- #f00

预定义的颜色名称包括aqua ， black ， blue ， fuchsia ， gray ， green ， lime ， maroon ， navy ， olive ， purple ， red ， silver ， teal ， white和yellow 。 transparent也是一个有效的值。

## 字体系列

有一些精选的“ 安全 ”字体（最常用的是Arial，Verdana和Times New Roman），但您可以指定多个字体，用逗号分隔 。 
这样做的目的是，如果用户没有指定的第一个字体，那么浏览器会遍历列表直到找到它所具有的字体。 这很有用，因为不同的计算机有时会安装不同的字体。 
因此， font-family: arial, helvetica, serif将首先查找Arial字体，如果浏览器找不到它，它将搜索Helvetica，然后搜索常见的衬线字体

## div class值可以有多个,优先级为后面覆盖前面的

```
<div class="sidebar-module sidebar-module-inset">
```
