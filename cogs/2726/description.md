# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
西天取经上大路，一走就是几万里。
</p>
<p>
唐僧师徒们走了一路，快要饿死了。。。
</p>
<p>
一座座大山挡在他们面前，山上有妖精，有猛兽， 还有悟空爱吃的桃子，八戒的西瓜，沙僧的鱼，白龙马的草。。
</p>
<p>
共有 n 座山， 编号为 1 到 n， 它们呈环形，相邻的山之间都有一定的距离；
</p>
<p>
每座山上有桃子，西瓜，鱼，草，若干；每个桃子（西瓜，鱼， 草）能走一里路，每到一座山上，
</p>
<p>
你就可以带走山上的所有食物，如果当前的食物不足以支撑你到下一座山，你就会死掉；
</p>
<p>
唐僧派悟空，八戒，沙僧，白龙马去巡山，如果他们能从某一座山出发，转一圈活着回到这座山，就算成功；
</p>
<p>
只要途中有一个死掉，就不算成功；
</p>
<p>
ps:徒弟走了唐僧在家吃神马呢？？百思不得其解。。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个数 n，表示山的总数；
</p>
<p>
下一行 n 个数，第 i 个数 xi 表示第 i 座山到第 i+1 座山距离
</p>
<p>
第 n 个数表示第 n 座山到第 1 座山的距离；接下来 n 行，每行 4 个数，分别表示桃子，西瓜，鱼，草的数量；
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
如果成功，就输出 出发点的编号（如果有多解，输出最小的编号）；如果失败就输出“No”；
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5
</p>

<p>
<br/>

</p>

<p>
3 4 5 1 2
</p>

<p>
<br/>

</p>

<p>
6 6 6 6
</p>

<p>
<br/>

</p>

<p>
2 3 3 3
</p>

<p>
<br/>

</p>

<p>
2 3 3 3
</p>

<p>
<br/>

</p>

<p>
2 3 3 3
</p>

<p>
<br/>

</p>

<p>
6 6 6 6
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
注意：1.你只能从编号小的山到编号大的山上（因为是环形，
</p>
<p>
<br/>
</p>
<p>
所以你能从 n 到 1）；
</p>
<p>
<br/>
</p>
<p>
2.悟空只吃桃子，八戒只吃西瓜，沙僧只吃鱼，马只吃草；
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
刘你好
</p>