# 题目描述


<div>
<div>
USACO/stall4(译by Felicia Crazy)
<div>
<div>
<hr/>
</div>
</div>
<p>
描述
</p>
<p>
<br/>
</p>
<p>
农夫约翰上个星期刚刚建好了他的新牛棚，他使用了最新的挤奶技术。不幸的是，由于工程问题，每个牛栏都不一样。第一个星期，农夫约翰随便地让奶牛们进入牛栏，但是问题很快地显露出来：每头奶牛都只愿意在她们喜欢的那些牛栏中产奶。上个星期，农夫约翰刚刚收集到了奶牛们的爱好的信息（每头奶牛喜欢在哪些牛栏产奶）。一个牛栏只能容纳一头奶牛，当然，一头奶牛只能在一个牛栏中产奶。
</p>
<p>
给出奶牛们的爱好的信息，计算最大分配方案。
</p>
<p>
<br/>
</p>
<p>
格式
</p>
<p>
PROGRAM NAME: stall4
</p>
<p>
INPUT FORMAT:
</p>
<p>
(file stall4.in)
</p>
<p>
</p><table border="1">
<tbody>
<tr>
<td>
<div>
第一行
</div>
</td>
<td>
两个整数，N (0 &lt;= N &lt;= 200)和M (0 &lt;= M &lt;= 200)。N是农夫约翰的奶牛数量，M是新牛棚的牛栏数量。
</td>
</tr>
<tr>
<td>
<div>
第二行到第N+1行
</div>
</td>
<td>
<p>
一共N行，每行对应一只奶牛。第一个数字(Si)是这头奶牛愿意在其中产奶的牛栏的数目(0 &lt;= Si&lt;= M)。后面的Si个数表示这些牛栏的编号。牛栏的编号限定在区间(1..M)中，在同一行，一个牛栏不会被列出两次。
</p>
</td>
</tr>
</tbody>
</table>
<p></p>
<p>
<br/>
</p>
<p>
OUTPUT FORMAT:
</p>
<p>
(file stall4.out)
</p>
<p>
 只有一行。输出一个整数，表示最多能分配到的牛栏的数量。
</p>
<h3>
SAMPLE INPUT (file stall4.in)
</h3>
<p>
5 5
</p>
<p>
2 2 5
</p>
<p>
3 2 3 4
</p>
<p>
2 1 5
</p>
<p>
3 1 2 5
</p>
<p>
1 2
</p>
<h3>
SAMPLE OUTPUT (file stall4.out)
</h3>
4
<p>
<br/>
</p>
<p>
<br/>
</p>
</div>
</div>
<p>
<br/>
</p>
