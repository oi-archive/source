# 题目描述


<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	描述
</h2>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">lsp学习数学竞赛的时候受尽了同仁们的鄙视，终于有一天……受尽屈辱的lsp黑化成为了黑暗英雄Lord lsp。就如同中二漫画的情节一样，Lord lsp打算毁掉这个世界。数学竞赛界的精英lqr打算阻止Lord lsp的阴谋，于是她集合了一支由数学竞赛选手组成的超级行动队。由于队员们个个都智商超群，很快，行动队便来到了Lord lsp的黑暗城堡的下方。</span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">但是，同样强大的 Lord lsp 在城堡周围布置了一条“不可越过”的坚固防线。防线由很多防具组成，这些防具分成了 N 组。我们可以认为防线是一维的，那么每一组防具都分布在防线的某一段上，并且同一组防具是等距离排列的。也就是说，我们可以用三个整数 S，E和D来描述一组防具，即这一组防具布置在防线的 S，S+D，S+2D，...，S+KD（K∈Z，S+KD≤E，S+(K+1)D＞E）位置上。</span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">黑化的 Lord lsp 设计的防线极其精良。如果防线的某个位置有偶数个防具，那么这个位置就是毫无破绽的（包括这个位置一个防具也没有的情况，因为 0 也是偶数） 。只有有奇数个防具的位置有破绽，但是整条防线上也最多只有一个位置有奇数个防具。作为行动队的队长，lqr要找到防线的破绽以策划下一步的行动。但是，由于防具的数量太多，她实在是不能看出哪里有破绽。作为lqr可以信任的学弟学妹们，你们要帮助她解决这个问题。</span>
<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	输入格式
</h2>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">输入文件的第一行是一个整数T，表示有T组互相独立的测试数据。 </span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">每组数据的第一行是一个整数N。 </span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">之后N行，每行三个整数S</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">，E</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">，D</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">，代表第i组防具的三个参数。</span>
<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	输出格式
</h2>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">对于每组测试数据，如果防线没有破绽，即所有的位置都有偶数个防具，输出一行</span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">“There&#39;s no weakness.” （不包含引号） </span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">否则在一行内输出两个空格分隔的整数P和C，表示在位置P有C个防具。当然C应该是一个奇数。</span>
<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	样例输入
</h2>
<pre>3 
2 
1 10 1 
2 10 1 
2 
1 10 1 
1 10 1 
4 
1 10 1 
4 4 1 
1 5 1 
6 10 1 </pre>
<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	样例输出
</h2>
<pre>1 1 
There’s no weakness. 
4 3 </pre>
<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	限制
</h2>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">对于 30% 的数据，满足防具总数不多于 10</span><sup>7</sup><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">。</span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">对于 100% 的数据，满足防具总数不多于 10</span><sup>8</sup><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">，S</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">≤E</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">，1≤T≤5，N≤200000，0≤S</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">，</span><br/>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">E</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">，D</span><sub>i</sub><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">≤2</span><sup>31</sup><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">-1。</span>
<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	注释
</h2>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">见样例输出</span>
<h2 style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;background-color:#F0FFFF;">
	来源
</h2>
<span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:medium;line-height:normal;background-color:#F0FFFF;">【Nescafé II】杯模拟赛</span>
