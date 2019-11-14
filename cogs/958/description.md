# 题目描述


<p>
	<b><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">第四题：</span></b><b><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">number</span></b>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">有一种序列按照如下定义：</span><span></span>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">．</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">在这个序列中</span><span></span>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">．这个序列是按照从小到大的顺序排列的</span><span></span>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">．如果一个数</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">出现在这个序列中，那么</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">2i+1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">和</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">4i+5</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">也一定存在在这个序列中。</span><span></span>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">现在要求你先一个程序将这个序列前</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">个数字连接成一个长串，并且在这个基础上，从得到的长串中删除</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">个数字，使得这个长串的字典序最大。</span><span></span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输入文件（</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">number.in</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">）</span><span></span>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输入文件一行，</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">个整数</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">m</span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输出文件（</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">number.out</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">）</span><span></span>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输出文件</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">行，第一行是未删除数字之前的原串。</span><span></span>
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第二行是删除数字之后的数字串</span><span></span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">样例：</span><span></span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">input</span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">4 2</span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">output</span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1379</span>
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">79</span>
</p>
