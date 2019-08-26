
# Description

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">Bytelandish连锁超市委托你编写一个程序来模拟一项即将施行的促销活动，该活动的规则如下： <br/>
●想要参与的顾客，只需把他的个人资料写在帐单上，并把帐单放入投票箱； <br/>
●每天活动结束时，数额最大、最小的两张帐单被取出，付款数额最大的顾客将获得一笔奖金，价值为取出的两张帐单的数额之差； <br/>
●为了不重复计算，取出的两张帐单不再放回箱子，而剩下的帐单仍保留在箱中，进行第二天的活动。 <br/>
超市每天的营业额很大，因此可假定：每天活动结束时，箱中至少有两张帐单以供取出。 <br/>
你的任务是根据每天投入箱中的帐单，计算出这项促销活动期间超市付出的奖金总数额。 <br/>
任务： <br/>
编写一个程序，完成下列工作： <br/>
●读入投入箱中的帐单的信息； <br/>
●算出促销活动期间的奖金总额； <br/>
</font></span></p></div>

# Input

<div class="content"><div><span style="font-size: medium"> </span></div>
<div>
<div style="text-indent: 21.25pt">
<div><span style="font-size: medium">第一行是一个整数 n（1 &lt;= n &lt;= 5000），表示促销活动历时的天数。</span></div>
</div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">以下的n行，每行包含若干由空格分隔的非负整数。第i+1行的数表示在第i天投入箱子的账单金额。每行的第一行是一个整数k（0 &lt;= k &lt;= 10<sup>5</sup>）， 表示当日账单的数目。后面的k个正整数代表这k笔账单的金额，均小于10<sup>6</sup>。</span></div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">整个活动中涉及到的账单笔数不会超过10<sup>6</sup> 。</span></div>
</div></div>

# Output

<div class="content"><div style="text-indent: 21.25pt"><span style="font-size: medium">唯一一行是一个整数，等于整个促销活动中应该付出的奖金总额。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
3 1 2 3<br/>
2 1 1<br/>
4 10 5 5 1<br/>
0<br/>
1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
19<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

