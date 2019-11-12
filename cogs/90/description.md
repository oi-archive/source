# 题目描述


<p>
	<strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">[问题描述] </span></strong> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    初期研究证实解读玛雅文是一项比预期复杂的任务，即使在过了两百年以后，也只有很少的内容能被人们真正理解，其实也仅是在最近的三十年人们才真正地对它展开研究。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 玛雅文是基于石刻的一些被认为是象形符号的表征声音的小图画，通常把一些象形符号放在不同的位置就组合成了一个玛雅文中的词。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     解读玛雅文时遇到的问题之一是在读的顺序上，在摆放几个符号以拼写成一个词的时候，玛雅文创作者有时按他们的主观感觉来决定符号的摆放位置，而不是按照任何特殊规则。这导致的问题是，尽管知道了许多符号的发音，但是考古学家们有时仍旧不能确定一个词的读法。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     考古学家正在寻找一个特殊的词w，他们知道组成它的各个符号，但是他们不知道所有这些符号的可能排列方法。后来他们听说你来了，就想求得你的帮助。他们将给你提供g个组成词w的符号，同时还有一个符号串s，里面包含了他们在研究石刻时发现的所有符号。请帮助他们计算一下词w有多少种可能的拼写方案。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">任务： </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     写一个程序，给定组成w的符号和石刻中的符号串s，计算s中w的可能拼写方案出现的次数；确切点说，s中每一个连续的长度为g的符号串都可能是w中那些符号的一个排列。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">约束条件： </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 1 ≤ g ≤ 3 000 w中的符号个数； </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> g ≤ |s| ≤ 3 000 000 |s|是s中符号的个数。</span> 
</p>
<p>
	<strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">[输 入] </span></strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">： </span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 第一行包含两个整数：g和|s|，空格隔开； </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 第二行包含g个连续的字符，分别表示组成w的g个符号，字符有效范围为&#39;a&#39;-&#39;z&#39;和&#39;A&#39;-&#39;Z&#39;，大小写字母有区别； </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 第三行包含|s|个连续的字符，表示石刻中的符号，字符有效范围为&#39;a&#39;-&#39;z&#39;和&#39;A&#39;-&#39;Z&#39;，大小写字母有区别。</span> 
</p>
<p>
	<strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">[输 出] </span></strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">： </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 只有一行，即s中w的可能拼写方案出现的次数。</span> 
</p>
<p>
	<strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">[输入输出样例] </span></strong><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> writing.in</span> 
</p>
<pre>4 11 
cAda 
AbrAcadAbRa 
</pre>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> writing.out： </span><br/>
</p>
<pre>2</pre>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">等级： </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 其中有50分的测试数据g≤ 1000。 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 对使用Pascal语言的选手的重要提醒： </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> FreePascal中默认字符串类型变量长度不能超过255个字符.</span> 
</p>
