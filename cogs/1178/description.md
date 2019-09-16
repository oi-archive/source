# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><span></span>Assassin&#39;s Creed II的主角Ezio接受了一个任务：清除A城的所有卫兵。已知A城有N个路口，M条道路，路口之间被道路连接着（道路没有方向之分，且A城各个路口之间一定是直接或间接连通的），而卫兵们分散在各个道路上巡逻。<br/>
 <br/>
 因为A城实在很大，Ezio如果单独去执行任务的话，很容易陷入被围攻的境地，所以，Ezio可以雇佣了其他刺客。Ezio可以安排刺客们在某些路口执行任务，刺客们可以清除掉这个与他所在的路口相连道路上的所有敌人。当然，事情不会这么顺利，在每个路口安置刺客上都有不同的风险度。幸运的是，Ezio事先评估了这些路口的风险度，这能大大的提高任务的成功率。<br/>
 <br/>
 另外，刺客们互相都不一定认识，如果其中的两人被安排到了路口A和路口B，而路口A和B之间又有道路相连，那么，这两个刺客完全有可能会将对方当成敌人，互相残杀。这时Ezio不希望看到的。<br/>
 <br/>
 所以，Ezio现在唯一的问题就是，找到一种风险度最低的方案，使得A城所有士兵都能被清除，自己人又不被误杀。<br/>
<span></span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行是两个数字N和M，表示A城有N个路口，M条道路。(N &lt;= M &lt;=1000000)<br/>
 第二行是N个数字D， D[i]表示第i个路口的风险度（1 &lt;= D[i] &lt;= 100）<br/>
 接下来的M行，每行两个数字X和Y，表示路口X和路口Y之间有道路相连<br/>
</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">若有解，则输出最少的风险度值。若无解，则输出’NO’（不包含引号）</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>5 5
10 30 10 25 20
1 2
2 3
2 4
3 5
4 5
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>45</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;line-height:17px;background-color:#FFFFFF;">样例解释：在1,3,4三个路口上安排刺客，风险度为10+10+25 =45</span></span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;line-height:17px;background-color:#FFFFFF;"><span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;line-height:17px;background-color:#FFFFFF;">时间制限：1S</span></span></span> 
</p>
<h3>
	<span><span style="font-size:15px;"><span></span><br/>
</span></span>
</h3>
