# 题目描述


<span></span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;background-color:#003399;color:#B8D100;">福州NOIP2010培训Day1</span> 
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	可以用路径来描述文件夹，路径为一个包含若干部分的字符串，之间用<span>&#39;/&#39;</span>分隔。每部分均为一个文件夹的名称，且表示这个文件夹的父文件夹为前一部分描述的文件夹。
</p>
<p style="text-indent:21.0000pt;">
	例如：/home/fj/summer表示根目录下有一个名称为home的文件夹，这个home文件夹下有一个名称fj的文件夹，这个名称为fj的文件夹下有。
</p>
<p style="text-indent:21.0000pt;">
	每个路径的第1个字符总是<span>&#39;/&#39;</span>，且不会出现两个连续的<span>&#39;/&#39;</span>，最后一个字符不会是<span>&#39;/&#39;</span>。而所有文件夹仅包含数字和字母。
</p>
<p style="text-indent:21.0000pt;">
	现在先给出N个路径，一开始除了根目录不存在任何文件夹，在每给出一个路径后，对于第i个路径，你需要输出的是若要让第1个路径到第i个路径存在，最少需要新建多少个文件夹。
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	输入文件第1行为一个正整数N。
</p>
<p style="text-indent:21.0000pt;">
	接下来N行，每行为一个描述路径的字符串，长度均不超过100。
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	输出应包含N行，每行1个正整数，第i行输出若要使第1个路径到第i个路径存在，最少需要新建多少个文件夹。
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入输出】</span> 
</h3>
<pre>样例输入1：
2
/home/fj/summer
/home/fj/123

样例输出1：
3
4
样例输入2：
3
/chicken
/chicken/egg
/chicken

样例输出1：
1
2
2
样例输入3：
4
/a
/a/b
/a/c
/b/b

样例输出1：
1
2
3
5
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	<br/>
</p>
<p>
	数据规模：
</p>
<p style="text-indent:20.2500pt;">
	对于所有数据，N&lt;=1000。
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，有N&lt;=20；
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，有N&lt;=200； 
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，有对于所有路径最多存在两个&#39;/&#39;（包含第1个字符）。
</p>
<p>
	<br/>
</p>
