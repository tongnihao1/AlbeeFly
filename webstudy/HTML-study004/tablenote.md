#1,表格由<table>标签来定义，每个表格都有若干行由<tr>标签定义，每行被分割为若干单元格由<td>标签定义。字母tr指表格数据（table data),及数据单元格的内容；
<table>
   <tr>
<td>单元格内文字内容</td>
...
</tr>
...
     </table>。
#2，表格标记：
1<table></table>--定义表格；
2<caption></caption>--定义表格标题；
3<tr></tr>--定义表格行；
4<td>定义表格单元</td>；
5<th>定义表格的表头</th>（具有加粗的作用的td）;
#3,表格的常用属性
1，表格的边框属性：border，默认值为0；
2，表格的边框色：bordercolor；
3，设置表格的宽度和高度:<table width=value,height=value></table>;
4，表格的背景颜色：background
5，cellpadding：设置单元格与单元格边框之间的空白间距，像素值（默认值：2像素）；
6，cellpadding：设置单元格“内容”与单元格边框之间的空白间距，像素值（默认值：1像素）；
7，行标记  tr  和属性：
7.1，行高度：height；
7.2，行的边框颜色：border color；
7.3，行的背景颜色：bgcolor;
7.4行的对齐方式：align
7.5,行的垂直对齐方式valign；（单元格td属性没有边框颜色）
8，高度：height，宽度：bordercolor;
9,背景颜色bgcolor,背景图片：background，
10，对齐方式:align,垂直对齐方式：valign，水平跨度：colspan,垂直跨度：rowspan（属性规定单元格可横跨列数，行数），表头标记：th与td类似；
#4，表格的结构标记：
<thead>...</thead>,<tbody>...</tbody>,<tfoot>...</tfoot>