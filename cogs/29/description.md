# 题目描述


<p>
<strong>【问题描述】 </strong> 
</p>
<p>
    A 国是一个新兴的国家，有 N 个城市，分别编号为 1,2.3…N 。政府想大搞公路建设，提供了优惠政策：对于每一个投资方案的预计总费用，政府负担 50% ，并且允许投资的公司对过往的汽车收取连续 5 年的养路费。世界各地的大公司纷纷投资，并提出了自己的建设方案，他们的投资方案包括这些内容：公路连接的两座城市的编号，预计的总费用（假设他们的预计总是准确的）。
</p>
<p>
    你作为 A 国公路规划局的总工程师，有权利决定每一个方案是否接受。但是政府给你的要求是：
</p>
<p>
（ 1 ）要保证各个城市之间都有公路直接或间接相连。
</p>
<p>
（ 2 ）因为是新兴国家，政府的经济实力还不强。政府希望负担最少的费用。
</p>
<p>
    因为大公司并不是同时提出方案，政府希望每接到一个方案，就可以知道当前需要负担的最小费用和接受的投资方案，以便随时开工。关于你给投资公司的回复可以等到开工以后再给。 注意： A 国一开始是没有公路的。我们设定 A 国的城市数目 N&lt;=500 ，投资的方案总数 M&lt;=2000 。
</p>
<p>
 
</p>
<p align="left">
【输入格式】
</p>
<p>
输入文件名： road.in
</p>
<p>
第 1 行有两个数字： N 、 M
</p>
<p>
第 2 行到第 M+1 行给出了各个投资方案，第 i 行的方案编号为 i-1
</p>
<p>
编号小的方案先接到，一个方案占一行，每行有 3 个数字，分别是连接的两个城市编号 a 、 b ，和投资的预计总费用 cost 。
</p>
<p>
【输出格式】
</p>
<p>
输出文件名： road.out
</p>
<p>
输出文件共有 M 行。
</p>
<p>
每一行的第一个数字是当前政府需要负担的最少费用（保留 1 位小数），后面是 X 个数字，表示当前政府接受的方案的编号， 不 要求从小到大排列。但如果此时接受的所有投资方案不能保证政府的第一条要求，那么这一行只有一个数字 0
</p>
<p>
【输入样例】
</p>
<p>
输入文件名： road.in
</p>
<p>
3 5<br/>
1 2 4<br/>
1 3 4<br/>
2 3 4<br/>
1 3 2<br/>
1 2 2
</p>
<p>
输出文件名： road.out
</p>
<p>
0<br/>
4.0 1 2 <br/>
4.0 1 2 <br/>
3.0 1 4 <br/>
2.0 4 5<br/>
 
</p>
<p>
注意：由于没有评测插件，不要求输出方案。
</p>
<p>
即样例输出：
</p>
<p>
0<br/>
4.0<br/>
4.0<br/>
3.0<br/>
2.0
</p>
