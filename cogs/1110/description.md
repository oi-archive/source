# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">小y是苏联的总书记。</span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">苏联有n个城市，某些城市之间修筑了公路。任意两个城市都可以通过公路直接或者间接到达。</span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">小y发现有些公路被毁坏之后会造成某两个城市之间无法互相通过公路到达。这样的公路就被称为dangerous pavement。</span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为了防止美帝国对dangerous pavement进行轰炸，造成某些城市的地面运输中断，小y决定在所有的dangerous pavement驻扎重兵。可是到底哪些是dangerous pavement呢？你的任务就是找出所有这样的公路。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行n，m(1&lt;=n&lt;=150, 1&lt;=m&lt;=5000)，分别表示有n个城市，总共m条公路。</span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">以下m行,每行两个整数a, b，表示城市a和城市b之间修筑了直接的公路。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出有若干行。</span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">每行包含两个数字a,b(a<b)，表示<a,b>是dangerous pavement。</b)，表示<a,b></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">请注意：输出时，所有的数对<a,b>必须按照a从小到大排序输出；如果a相同，则根据b从小到大排序。</a,b></span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>　6 6
　1 2
　2 3
　2 4
　3 5
　4 5
　5 6</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>　1 2
　5 6</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">福州NOIP2010培训Day5</span> 
</p>
