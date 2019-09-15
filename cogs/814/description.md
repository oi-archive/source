# 题目描述


<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【问题描述】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">小D有N份工作要完成，每一份工作有一个难度系数。由于工作数目太多了，小D光靠自己的能力是无法完成的，所以他打算雇佣很多工人很多人来帮他。工人是非常精明的，他们要求按照工作数目收费，如果分派给他的工作数目小于k，他们将不愿意接受。工人完成一份工作的收费是C。但是，小D也是很精明的老板，考虑到有些工作之间很类似，完成了一份工作之后可以很轻松的完成下一份工作，所以他提出了这样的要求，工人能够得到的报酬将是C + (maxB–minB)^2。其中，maxB表示工人接受的所有工作中的难度系数的最大值，minB是最小值。显然，如果工人只接受了一份工作，那么他将得到的报酬是C。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 作为小D的助理，现在你需要告诉他，为了完成这些工作，他至少要支付多少钱给工人？</span> 
</p>
<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入文件】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">       第一行三个非负整数N、k、C，意义如题所述； </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">        第二行N个正整数分别描述N份工作的难度系数。</span> 
</p>
<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出文件】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">一个整数表示小D最少需要支付的工资。</span> 
</p>
<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 1 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 4</span> 
</p>
<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2</span> 
</p>
<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例说明】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">       如果分给一个工人做，收费为1 + (4–2)</span><sup><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2</span></sup><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> = 5； </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 如果分给两个工人作，收费为1 + 1 = 2； </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 所以最小收费为2。</span> 
</p>
<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【评分标准】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">       本题包含10个测试点，对于每个测试点，如果你的输出和标准输出完全一样则得到该测试点的全部分数，否则得0分。</span> 
</p>
<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【数据规模】</span> 
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">       对于50%的测试数据，满足1 ≤ k ≤ N ≤ 20</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 对于100%的测试数据，满足 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 1 ≤ k ≤ N ≤ 10 000</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">               0 &lt; C ≤ 1 000 000</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">               难度系数 ≤ 100 000 000</span> 
</p>
