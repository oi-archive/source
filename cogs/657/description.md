# 题目描述


<h2>
问题描述
</h2>
<p>
给出一个 n*m 的棋盘 (n 、 m≤80,n*m ≤ 80) ，要在棋盘上放 pn(pn≤ 20) 个棋子， 使得任意两个棋子不相邻。每次试验随机分配一种方案，求首次放置即出现合法方案的概率，答案用既约分数表示（格式是分母在前）。
</p>
<p>
<br/>
</p>
<h2>
输入输出
</h2>
<h4>
输入文件： examtwo.in
</h4>
<p>
输入文件只有一行，有三个数 n 、 m ，pn
</p>
<p>
n,m表示方格棋盘大小,pn表示要放的棋子数量
</p>
<h4>
输出文件： examtwo.out
</h4>
<p>
输出文件也只有一行，即一个用/表示的既约分数。
</p>
<h4>
输入输出示例：
</h4>
<p>
examtwo.in
</p>
<p>
2 2 2
</p>
<p>
examtwo.out
</p>
<p>
3/1
</p>
<p>
样例解释:
</p>
<p>
方案总数为6
</p>
<p>
<br/>
</p>
<table class="ke-zeroborder" border="0" height="88" width="601">
<tbody>
<tr>
<th scope="col">
<table border="1" height="44" width="48">
<tbody>
<tr>
<th scope="col">
<strong>*</strong> 
</th>
<th scope="col">
<strong>*</strong> 
</th>
</tr>
<tr>
<td>
 
</td>
<td>
 
</td>
</tr>
</tbody>
</table>
</th>
<th scope="col">
<table border="1" height="44" width="48">
<tbody>
<tr>
<th scope="col">
<div align="center">
<strong>*</strong> 
</div>
</th>
<th scope="col">
<div align="center">
<strong> </strong> 
</div>
</th>
</tr>
<tr>
<td>
<div align="center">
<strong>*</strong> 
</div>
</td>
<td>
<div align="center">
<strong> </strong> 
</div>
</td>
</tr>
</tbody>
</table>
</th>
<th scope="col">
<table border="1" height="44" width="48">
<tbody>
<tr>
<th scope="col">
<strong>*</strong> 
</th>
<th scope="col">
 
</th>
</tr>
<tr>
<td>
 
</td>
<td>
<div align="center">
<strong>*</strong> 
</div>
</td>
</tr>
</tbody>
</table>
</th>
<th scope="col">
<table border="1" height="44" width="48">
<tbody>
<tr>
<th scope="col">
 
</th>
<th scope="col">
<strong>*</strong> 
</th>
</tr>
<tr>
<td>
<div align="center">
<strong>*</strong> 
</div>
</td>
<td>
 
</td>
</tr>
</tbody>
</table>
</th>
<th scope="col">
<table border="1" height="44" width="48">
<tbody>
<tr>
<th scope="col">
 
</th>
<th scope="col">
<strong>*</strong> 
</th>
</tr>
<tr>
<td>
 
</td>
<td>
<div align="center">
<strong>*</strong> 
</div>
</td>
</tr>
</tbody>
</table>
</th>
<th scope="col">
<table border="1" height="44" width="48">
<tbody>
<tr>
<th scope="col">
 
</th>
<th scope="col">
 
</th>
</tr>
<tr>
<td>
<div align="center">
<strong>*</strong> 
</div>
</td>
<td>
<div align="center">
<strong>*</strong> 
</div>
</td>
</tr>
</tbody>
</table>
</th>
</tr>
</tbody>
</table>
<p>
只有2个方案是合法
</p>
<p>
<br/>
</p>
