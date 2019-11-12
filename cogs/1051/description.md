# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">描述</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Victoria是一位颇有成就的艺术家，他因油画作品《我爱北京天安门》闻名于世界。现在，他为了报答帮助他的同行们，准备开一个舞会。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Victoria准备邀请n个已经确定的人，可是问题来了：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">这n个人每一个人都有一个小花名册，名册里面写着他所愿意交流的人的名字。比如说在A的人名单里写了B，那么表示A愿意与B交流；而且如果A名单里面有B，那么B名单里面肯定有A，也就是说两个人如果一方愿意和另一方交流，那么另一方也肯定愿意和这一方交流。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Victoria觉得需要在这n个人里面确定m个人，保证这m个人每一个人都能在舞会中找到至少k个人交流，并求出一种方案以确定m的最大值是多少。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">注意：自己的名单里面不会有自己的名字。</span><br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">格式</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入格式</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行两个数n和k。接下来n行，每i+1行表示编号为i的人的小花名册名单，名单以0结束。1&lt;=n,k&lt;=200。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出格式</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一个数，m。</span><br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输入</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">22 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4 5 10 11 20 21 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3 6 8 11 16 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3 5 8 12 15 16 18 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 5 6 10 11 12 16 18 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3 4 16 20 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 4 19 21 22 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8 9 13 19 20 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3 7 10 19 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">7 10 14 16 19 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 4 8 9 10 20 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 2 4 18 19 20 21 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 4 13 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">7 12 15 16 18 19 21 22 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9 16 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 13 21 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3 4 5 9 13 14 20 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">18 22 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 4 11 13 17 21 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6 7 8 9 11 13 19 21 22 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 5 7 10 11 16 21 22 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 6 11 13 15 18 19 20 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6 13 17 19 20 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输出</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">22</span><br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">限制</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">每个测试点1秒。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">来源</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Vivian Snow</span><br/>
