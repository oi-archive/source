# 题目描述


<div>
	<h1 style="text-align:center;">
		<span style="font-size:24px;font-family:&#39;Microsoft YaHei&#39;;">1．这也叫破译？（crack）</span> 
	</h1>
	<p>
		<br/>
	</p>
	<h3>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【题目描述】</span> 
	</h3>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;"> NOIP吧是个很和谐的吧，一直为了OI事业而奋斗。但是，由于吧的日益壮大，各种矛盾还是避免不了。</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">  这两天，传说中的NOIP吧官方群群主接到一封神秘而好笑的信。神秘在于信的表面有两个特别大的字——神秘（⊙﹏⊙b汗）；好笑在于信的开头说，你一定猜不出这封信源自何处，结尾处署名CCF（⊙﹏⊙b汗）。</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">    言归正传，CCF的信让老练的群主大吃一惊，觉得也没有招惹过CCF啊。信中说这封信的内容加密过了，你需要完成这封信上的任务，完成之后内容就会自然的显现了（这也叫破译？⊙﹏⊙b汗）。群主觉得这等小事何足挂齿，只是最近ACM那边很多事啊，所以交给你了。（什么？你要推脱？告诉你，群主是个愤青，impossible！！！）</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">    信中给了n 个单词，每个单词都由小写字母构成。信的后面给了一个字母表，字母表如下：</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">a b c d e f g h i j k l m n o p q r s t u v w x y z</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4 2 5 6 1 4 5 6 7 2 3 4 8 9 3 1 2 6 8 9 2 6 3 2 5 7</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">    这些字母对应一个数字，暂且称作：权值。一个单词的权值定义为单词所含的字母的权值之和。你的任务是按权值降序（从大到小）,(若权值相等，按字符串排序。注：两个字符串先输出长度大的，长度相同输出字典序大的,完全相同则直接输出)输出前m（1&lt;=m&lt;=n）个单词和单词的权值。</span> 
	</p>
	<h3>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入格式】</span> 
	</h3>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入文件crack.in包含n+1行；</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第一行是整数n，m，表示单词的个数和所需输出的单词的个数；</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第2~n+1行，每行一个单词。</span> 
	</p>
	<h3>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出格式】</span> 
	</h3>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输出文件crack.out包含m行。</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第1~m行，每行一个单词和一个权值，单词和权值之间用一个空格隔开。</span> 
	</p>
	<h3>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入样例】</span> 
	</h3>
</div>
<p>
	<span style="font-size:16px;"><br/>
</span> 
</p>
<pre>10 10
noip
noi
ceoi
ctsc
apoi
usaco
nocow
vijos
crack
tyvj
</pre>
<div>
	<h3>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出样例】</span> 
	</h3>
<pre>ctsc 27
vijos 26
nocow 23
crack 23
usaco 22
tyvj 22
noip 20
noi 19
ceoi 16
apoi 15
</pre>
	<p>
		<br/>
	</p>
</div>
<br/>
<div>
	<h3>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【数据范围】</span> 
	</h3>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">40%的数据满足：1&lt;=n&lt;=5000</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">80%的数据满足：1&lt;=n&lt;=20000</span> 
	</p>
	<p>
		<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100%的数据满足：1&lt;=n&lt;=50000</span> 
	</p>
</div>
