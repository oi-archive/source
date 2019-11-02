<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近凌峰大神准备上网<span style="font-family: arial;">→_<span style="font-family: arial;">→（凌峰自恋ing）</span></span></p><p><span style="font-family: arial;"><span style="font-family: arial;">注:此题不坑!不是一道坑爹题目!</span></span></p><p><span style="font-family: arial;"><span style="font-family: arial;">此题目灰常简单，是凌峰给刚刚学编程的小伙伴们设定滴~</span></span></p><p><span style="font-family: arial;"><span style="font-family: arial;">话说他上着上着突然想:我不是编程大神吗怎么不整一个判断网站是否合法的程序？</span></span></p><p><span style="font-family: arial;"><span style="font-family: arial;">于是他开始弄了!</span></span></p><p><span style="font-family: arial;"><span style="font-family: arial;">你:话说这关我什么事。。。</span></span></p><p><span style="font-family: arial;"><span style="font-family: arial;">凌峰:如果跟你没关系这题就没法做了!所以我给你设定的剧情就是:</span></span></p><blockquote><p><span style="font-family: arial;"><span style="font-family: arial;">你觉得很有意思，于是你也想试试~</span></span></p></blockquote><p><span style="font-family: arial;">你:</span><span style="font-family: arial;">这什么鬼剧情?</span></p><p><span style="font-family: arial;">凌峰:算了不管了，就这样了~</span></p><p><span style="font-family: arial;">那么我们开始吧。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个待判断的网址。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>这个网址是否合法。如果合法则输出Yes，否则输出No。</p><p>合法条件:</p><p>开头必须是。http://、https://或ftp://</p><p>结尾必须是.com/，.org/，.cn/，.net/。(凌峰不准备整得太难。)</p><p>http://、https://或ftp://后面，.com/，.org/，.cn/，.net/前面必须有文字。</p><p>如网址当中含有www.，那么www.后面不能直接跟.com/，.org/，.cn/，.net/。</p><p style="text-align: left;">如果开头是ftp://那么结尾不用跟.com/，.org/，.cn/，.net/。</p><p>不能有连续的多个点。</p><p>如:</p><p>https://hhh.com/ &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; /*合法。*/</p><p>ftp://hhh.asdfadsf/ &nbsp; &nbsp;/*不合法，不能以asdfasdf结尾。*/</p><p>http://llllllll/ &nbsp; &nbsp; &nbsp;/*不合法，.不能以llllllll结尾。*/</p><p>http://www.com/&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/*不合法,www.后面没有东西。*/</p><blockquote><p>你:好像很简单啊~</p></blockquote><p>没错~是很简单!那么赶紧编吧!</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]</p><p>https:///</p><p><br></p><p>[Sample 2]</p><p>http://233333333333333333333333333333333......com/</p><p><br></p><p>[Sample 3]</p><p>ftp://172.20.233.333/</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br></p><p>No</p><p><br></p><p>[Sample 2]</p><p>No</p><p><br></p><p>[Sample 3]</p><p>Yes</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>网址最大长度不超过string类型的最大限制。</p>
</div>
</div>