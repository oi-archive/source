# 题目描述


<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给定两个集合A、B，集合内的任一元素x满足1 ≤ x ≤ 10^9，每个集合的元素个数不超过10^5。我们希望求出A、B之间的关系。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 任　务：给定两个集合的描述，判断它们满足下列关系的哪一种：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> A是B的一个真子集，输出“A is a proper subset of B”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> B是A的一个真子集，输出“B is a proper subset of A”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> A和B的交集为空，输出“A and B are disjoint”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> A和B是同一个集合，输出“A equals B”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 上述情况都不是，输出“I&#39;m confused!”</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入格式：</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">两行，均为整数，第一行为集合A，其中第一个数表示集合A的元素个数，第二行为集合B，其中第一个数表示集合B的元素个数；</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出格式：</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一行，为两个集合的关系。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 输入 subset1.in</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 11 1 2 3 4 5 6 7 8 9 10 12</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 11 11 13 44 56 76 878 43 466 6657 19 678</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出 subset1.out</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> A and B are disjoint</span> 
</p>
<p>
	<br/>
</p>
