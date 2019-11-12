# 题目描述


<h3>
【题目描述】
</h3>
<p>
辩论是件好事！众所周知，真理越辩越明。Ural锦标赛的两名组织者进行了一场辩论。第一个人说，对于编程竞赛而言，计算一个函数的值是一道非常愚蠢而且无用的题目。他的论证是：一旦一个函数的定义已知，并且有充分时间做必要的准备，就可以很快计算出这个函数在任意一点的值。第二名组织者却认为并非所有的函数都可以被足够快地计算出来。为了结束这场辩论，他们决定做一个试验。因此你需要证明你的确可以足够快地计算一个函数在任意一点的值。
</p>
<p>
这个函数f(n)，其中n是非负整数，递归定义如下：
</p>
<p>
f(0)=0
</p>
<p>
f(n)=g(n,f(n-1))，
</p>
<p>
其中g(x,y)=( (y-1)x^5 +x^3 - xy + 3x + 7y) % 9973，这里%符号代表取模（即C/C++中的%）
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件有一行一个整数n（0&lt;=n&lt;=10^8）.
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个整数f(n)。
</p>
<h3>
【样例输入】
</h3>
<pre>50</pre>
<h3>
【样例输出】
</h3>
<pre>6300</pre>
<h3>
【提示】
</h3>
<p>
你得写一个程序输出f(n)的值。并且它必须运行的非常快！
</p>
<h3>
【来源】
</h3>
<p>
<span style="font-family:Simsun;"><strong><a href="http://acm.timus.ru/problem.aspx?num=1309" target="_blank">Ural 1309 Dispute</a></strong></span> 
</p>
<p>
<span style="font-family:Simsun;"><strong>Problem Author:<span class="Apple-converted-space"> </span></strong><span style="color:#000000;text-transform:none;text-indent:0px;letter-spacing:normal;word-spacing:0px;float:none;display:inline !important;white-space:normal;-webkit-text-stroke-width:0px;">Idea - Alexander Klepinin, prepared by Alexander Klepinin, Stanislav Vasilyev</span></span><br style="color:#000000;text-transform:none;text-indent:0px;letter-spacing:normal;word-spacing:0px;white-space:normal;-webkit-text-stroke-width:0px;"/>
<b style="color:#000000;text-transform:none;line-height:22.39px;text-indent:0px;letter-spacing:normal;font-family:Simsun;font-size:medium;font-style:normal;font-variant:normal;word-spacing:0px;white-space:normal;-webkit-text-stroke-width:0px;">Problem Source:<span class="Apple-converted-space"> </span></b><span style="color:#000000;text-transform:none;text-indent:0px;letter-spacing:normal;word-spacing:0px;float:none;display:inline !important;white-space:normal;-webkit-text-stroke-width:0px;">VIII Collegiate Students Urals Programming Contest. Yekaterinburg, March 11-16, 2004</span> 
</p>
