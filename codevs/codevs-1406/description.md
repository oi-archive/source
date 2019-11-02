<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一类书的序言是以罗马数字标页码的。传统罗马数字用单个字母表示特定的数值，以下是标准数字表: <br><br> I 1 L 50 M 1000<br> V 5 C 100<br> X 10 D 500<br> 最多3个同样的可以表示为10n的数字(I,X,C,M)可以连续放在一起，表示它们的和: <br><br> III=3<br> CCC=300<br> 可表示为5x10n的字符(V,L,D)从不连续出现。 <br><br> 除了下一个规则，一般来说，字符以递减的顺序接连出现: <br><br> CCLXVIII = 100+100+50+10+5+1+1+1 = 268<br> 有时，一个可表示为10n的数出现在一个比它大1级或2级的数前(I在V或X前面，X在L或C前面，等等)。在这种情况下，数值等于后面的那个数减去前面的那个数: <br><br> IV = 4<br> IX = 9<br> XL = 40<br> This compound mark forms a unit and may not be combined to make another compound mark (e.g., IXL is wrong for 39; XXXIX is correct). <br><br> 像XD, IC, 和XM这样的表达是非法的，因为前面的数比后面的数小太多。对于XD(490的错误表达)，可以写成 CDXC; 对于IC(99的错误表达)，可以写成XCIX; 对于XM(990的错误表达)，可以写成CMXC。 90 is expressed XC and not LXL, since L followed by X connotes that successive marks are X or smaller (probably, anyway). <br><br><br> 给定N(1 &lt;= N &lt; 3,500)， 序言的页码数，请统计在第1页到第N页中，有几个I出现，几个V出现，等等 (从小到大的顺序)。不要输出并没有出现过的字符。 <br><br> 比如N = 5, 那么页码数为: I, II, III, IV, V. 总共有7个I出现，2个V出现。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个整数N</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每行一个字符和一个数字k，表示这个字符出现了k次。字符必须按数字表中的递增顺序输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>I 7<br>V 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1s</p>
</div>
</div>