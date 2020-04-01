<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>1．对于给定的一个长度是N的0，1字符串S = s<sub>1</sub>s<sub>2</sub>...s<sub>n</sub>。</p>
<p>2．S的子串S(l,r) = [s<sub>l</sub>,s<sub>l+1</sub>,s<sub>l+2</sub>,...,s<sub>r</sub>]。</p>
<p>3．若S(l,r)中'0'的个数是'1'个数的2倍，称S(l,r)这个为good串，否则为bad串。</p>
<p> </p>
<p>选择一对整数a, b (1 &lt;= a &lt;= b &lt;= N)。</p>
<p>Num1：开始位置l和结束位置r都在闭区间[a,b]上的子串中good串的个数；</p>
<p>Num2：开始位置l和结束位置r都不在闭区间[a,b]上的子串中good串的个数，但可以包含[a,b]子串，即l，r有如下三种情况l&lt;a且r&lt;a，l&gt;b且r&gt;b，l&lt;a且r&gt;b；</p>
<p>求有多少对a, b使得Num1与Num2相等？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入一个整数n。</p>
<p>第二行输入一个由’0’和’1’组成的长度为n的字符串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，即使Num1和Num2相等的a,b数对。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>010</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>[a,b]=[1,1]时：</p>
<p>       开始位置l和结束位置r都在闭区间[a,b]上的子串如下：</p>
<p>       "0"(good子串的个数是0个)。</p>
<p>       开始位置l和结束位置r都不在闭区间[a,b]上的子串如下：</p>
<p>       "1","0","10"(good子串的个数是0个)。</p>
<p>所以[1,1]满足条件。</p>
<p> </p>
<p>[a,b]=[1,2]时：</p>
<p>       开始位置l和结束位置r都在闭区间[a,b]上的子串如下：</p>
<p>       "0","1","01"(good子串的个数是0个)。</p>
<p>       开始位置l和结束位置r都不在闭区间[a,b]上的子串如下：</p>
<p>       "0"(good子串的个数是0个)。</p>
<p>所以[1,2]满足条件。</p>
<p> </p>
<p>[a,b]=[1,3]时：</p>
<p>       开始位置l和结束位置r都在闭区间[a,b]上的子串如下：</p>
<p>       "0","1","0","01","10","010"(good子串的个数是1个:"010")。</p>
<p>       不存在开始位置l和结束位置r都不在闭区间[a,b]上的子串(good子串的个数是0个)。</p>
<p>所以[1,3]不满足条件。</p>
<p> </p>
<p>[a,b]=[2,2]时：</p>
<p>       开始位置l和结束位置r都在闭区间[a,b]上的子串如下：</p>
<p>       "1"(good子串的个数是0个)。</p>
<p>       开始位置l和结束位置r都不在闭区间[a,b]上的子串如下：</p>
<p>       "0","0","010"(good子串的个数是1个:"010")。</p>
<p>所以[2,2]不满足条件。</p>
<p> </p>
<p>[a,b]=[2,3]时：</p>
<p>       开始位置l和结束位置r都在闭区间[a,b]上的子串如下：</p>
<p>       "1","0","10"(good子串的个数是0个)。</p>
<p>       开始位置l和结束位置r都不在闭区间[a,b]上的子串如下：</p>
<p>       "0"(good子串的个数是0个)。</p>
<p>所以[2,3]满足条件。</p>
<p> </p>
<p>[a,b]=[3,3]时：</p>
<p>       开始位置l和结束位置r都在闭区间[a,b]上的子串如下：</p>
<p>       "0"(good子串的个数是0个)。</p>
<p>       开始位置l和结束位置r都不在闭区间[a,b]上的子串如下：</p>
<p>       "0","1","01"(good子串的个数是0个)。</p>
<p>所以[3,3]满足条件。</p>
<p> </p>
<p>所以有4对a,b满足题意。</p>
<p> </p>
<p>10%的数据中1&lt;=N&lt;=60;</p>
<p>30%的数据中1&lt;=N&lt;=1000;</p>
<p>40%的数据中1&lt;=N&lt;=5000;</p>
<p>100%的数据中1&lt;=N&lt;=100000;</p>
</div>
</div>