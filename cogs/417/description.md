# 题目描述


<p>
<strong>试题描述 </strong> 
</p>
<p>
对于一棵树，我们可以将某条链和与该链相连的边抽出来，看上去就象成一个毛毛蛇，点数越多，毛毛蛇就越大。例如下图左边的树（图 1 ）抽出一部分就变成了右边的一个毛毛蛇了（图 2 ）。
</p>
<p align="center">
<img alt="" src="/images/worm.jpg" height="178" width="286"/> 
</p>
<p>
<strong>输入数据 </strong> 
</p>
<p>
在文本文件 worma.in 中第一行两个整数 N ， M ，分别表示树中结点个数和树的边数。
</p>
<p>
接下来 M 行，每行两个整数 a, b 表示点 a 和点 b 有边连接（ a, b ≤ N ）。你可以假定没有一对相同的 (a, b) 会出现一次以上。
</p>
<p>
<strong>输出数据 </strong> 
</p>
<p>
在文本文件 worma.out 中写入一个整数 , 表示最大的毛毛蛇的大小。
</p>
<p>
<strong>样例输入 </strong> 
</p>
<p>
13 12<br/>
1 2<br/>
1 5<br/>
1 6<br/>
3 2<br/>
4 2<br/>
5 7<br/>
5 8<br/>
7 9<br/>
7 10<br/>
7 11<br/>
8 12<br/>
8 13
</p>
<p>
<strong>样例输出 </strong> 
</p>
<p>
11
</p>
<p>
<strong>测试数据范围 </strong> 
</p>
<p>
40% 的数据， N ≤ 50000
</p>
<p>
100% 的数据， N ≤ 300000
</p>
