# 题目描述


<p>
【问题描述】
</p>
<p>
佳佳有一个 <em>n </em>行 <em>n </em>列的黑白棋盘，每个格子都有两面，一面白色，一面黑色。佳佳把棋盘平放在桌子上，因此每个格子恰好一面朝上，如下图所示：
</p>
<p>
 
</p>
<table cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
</tbody>
</table>
<p>
 
</p>
<p>
我们把每行从上到下编号为 1 ， 2 ， 3 ，……， <em>n </em>，各列从左到右编号为 1 ， 2 ， 3 ，……， <em>n </em>，则每个格子可以用棋盘坐标 ( <em>x </em>, <em>y </em>) 表示。在上图中，有 8 个格子黑色朝上，另外 17 个格子白色朝上。
</p>
<p>
如果两个同色格子有一条公共边，我们称这两个同色格子属于同一个连通块。上图共有 5 个黑色连通块和 3 个白色连通块。
</p>
<p>
佳佳可以每分钟将一个格子翻转（即白色变成黑色，黑色变成白色），然后计算当前有多少个黑色连通块和白色连通块，你能算得更快吗？
</p>
<p>
 
</p>
<p>
【 输入文件 】 dface.in
</p>
<p>
输入文件的第一行包含一个正整数 <em>n </em>，为格子的边长。以下 <em>n </em>行每行 <em>n </em>个整数，非 0 即 1 ，表示初始状态。 0 表示白色， 1 表示黑色。下一行包含一个整数 <em>m </em>，表示操作的数目。以下 <em>m </em>行每行两个整数 <em>x </em>, <em>y </em>(1 ≤ <em>x </em>, <em>y </em>≤ <em>n </em>) ，表示把坐标为 ( <em>x </em>, <em>y </em>) 的格子翻转。
</p>
<p>
 
</p>
<p>
【 输出文件 】 dface.out
</p>
<p>
输出文件包含 <em>m </em>行，每行对应一个操作。该行包括两个整数 <em>b </em>, <em>w </em>，表示黑色区域和白色区域数目。
</p>
<p>
 
</p>
<p>
【 约定 】
</p>
<p>
•  1 ≤ <em>n </em>≤ 200
</p>
<p>
•  1 ≤ <em>m </em>≤ 10,000
</p>
<p>
 
</p>
<p>
【 样例输入 】 dface.in
</p>
<p>
5<br/>
0 1 0 0 0<br/>
0 1 1 1 0<br/>
1 0 0 0 1<br/>
0 0 1 0 0<br/>
1 0 0 0 0<br/>
2<br/>
3 2<br/>
2 3<br/>
 
</p>
<p>
【 样例输出 】 dface.out
</p>
<p>
4 3<br/>
5 2<br/>
 
</p>
<p>
【 样例说明 】
</p>
<p>
翻转 (3, 2) 之后，棋盘变为：
</p>
<p>
 
</p>
<table cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
1
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p>
1
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
<td valign="top" width="21">
<p>
 
</p>
</td>
</tr>
</tbody>
</table>
<p>
有 4 个黑色区域和 3 个白色区域
</p>
<p>
翻转 (2, 3) 之后，棋盘变为：
</p>
<p>
 
</p>
<table cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
<tr>
<td valign="top" width="21">
<p align="center">
1
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
<td valign="top" width="21">
<p align="center">
 
</p>
</td>
</tr>
</tbody>
</table>
<p>
 
</p>
<p>
有 5 个黑色区域和 2 个白色区域
</p>
