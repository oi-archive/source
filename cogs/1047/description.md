# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>背景 Background </strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 	 　　吃过草莓刨冰之后，Vani和cl有些疲倦地坐在一个长椅上。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“呐，玩得开心吗？”Vani忽然问道。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“嗯……很，很开心的说。”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“那么，我有一个问题想要问你呢。”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　cl的脸有点红了起来。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“嗯……好吧。问、问吧……我会告诉你的哦……”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“那好。对于一个分数A / B……”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“嗯……哎？哎？！”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“……就是这个问题。我觉得这个问题好纠结啊……”</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　Vani淡定地说完这句话。</span><br/>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　“啊？！哈啊？！”</span> 
</p>
<p>
	<img src="/upload/image/20120824/20120824150951_75274.png" alt=""/><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>描述 Description </strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 	 　　对于给定的分数 A / B，求其在 K 进制下是有限小数还是循环小数。如果是有限小数，求小数点后的位数；如果是循环小数，则求混循环部分和循环节的长度又分别是多少。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　注意，循环节指的是最短循环节，且混循环部分的长度也指最短。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>输入格式 Input Format </strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 	 　　第一行一个正整数 T，表示测试数据的数目。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　每个测试数据包含三个空格分隔的整数 A, B, K。含义如题目所示。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>输出格式 Output Format </strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 	　　对于每个测试数据，在单独的一行内输出两个空格分隔的整数 M, R。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　其中 M 表示混循环部分的长度，R 表示循环节的长度。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　如果 A / B 在 K 进制下是有限小数，则 R = 0，M 为小数点后面的位数；如果 A / B 在 K 进制下是纯循环小数，则 M = 0。</span><br/>
<span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>样例输入 Sample Input</strong></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 8 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">17 99 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">217 990 10</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>样例输出 Sample Output </strong></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>时间限制 Time Limitation </strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 	各个测试点1s</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>注释 Hint </strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 	　　对于 50% 的数据，B≤100000。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　对于 100% 的数据，1≤A<b≤10^12，k≤10^12，t≤10。< span=""><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span> </b≤10^12，k≤10^12，t≤10。<></span>
</p>
<p>
	<span></span> 
</p>
<p>
	<br/>
</p>
<p>
	<br/>
</p>
