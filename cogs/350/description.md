# 题目描述


<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">小吃店</span>
</p>
<div>
	<h3>
		<span style="font-family:Microsoft YaHei;font-size:16px;">【背景】</span>
	</h3>
</div>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">    小白终于决定了去小吃店的方案。来到小吃店的小白被琳琅满目的小吃看得直流口水。他对自己说：我一定要把钱全部用来买小吃！！但是小白最近在减肥，所以他不希望吃太多，他给自己又定了一个量，他希望正好达到这个量，不能多也不能少。假设每种最多买一份。</span>
</div>
<div>
	<h3>
		<span style="font-family:Microsoft YaHei;font-size:16px;">【问题描述】</span>
	</h3>
</div>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">    给出n个数对（ai，bi），每个数对都满足ai&gt;=bi。要求在这n个数对中选出k对，使得ai1+ai2+ai3+……+aik=m且bi1+bi2+bi3+……+bik=w，k为任意数，有几种方案。</span>
</div>
<div>
	<h3>
		<span style="font-family:Microsoft YaHei;font-size:16px;">【输入文件】</span>
	</h3>
</div>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">第一行有三个整数n,m,w。</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;"> 接下来n行每行二个整数ai,bi。</span>
</div>
<div>
	<h3>
		<span style="font-family:Microsoft YaHei;font-size:16px;">【输出文件】</span>
	</h3>
</div>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">方案总数。</span>
</div>
<div>
	<h3>
		<span style="font-family:Microsoft YaHei;font-size:16px;">【输入输出样例】</span>
	</h3>
</div>
<pre>food.in
4 3 2
2 1
3 2
1 1
2 1
</pre><pre>food.out
3
</pre>
<br/>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">样例解释</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;"> {1,3}、{2}和{3，4} （这里的数字表示第几对）</span>
</div>
<div>
	<h3>
		<strong><span style="font-family:Microsoft YaHei;font-size:16px;">【数据范围】 </span></strong>
	</h3>
</div>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于 30%数据, 0&lt;=n&lt;=10; 0&lt;=m,w&lt;=100</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;"> 对于100%数据, 0&lt;=n&lt;=50; 0&lt;=m,w&lt;=2,500</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;"> 对于 100%数据，0&lt;=ai,bi&lt;=100</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;"> 保证运算和输出不会超过maxlongint</span>
</div>
