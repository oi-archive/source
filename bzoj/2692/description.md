
# Description

<div class="content"><div id="ptit" class="probtitle" style="text-align: center; padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: 微软雅黑, 黑体, &#39;Times New Roman&#39;; font-size: 24pt; font-weight: bold; padding-top: 0px"><span style="font-size: medium"><br/>
</span></div>
<div id="pcont1" style="text-align: left; padding-bottom: 0px; margin: 20px 0px 0px; padding-left: 0px; padding-right: 0px; font-family: 宋体, &#39;Times New Roman&#39;; padding-top: 0px">
<div class="pdcont" style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px"><span style="font-size: medium">　　Answer的数学太差了，他决定恶补一番。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
不过在学其他东西之前，他必须先精通加减乘除四则运算。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
他想知道对于N个变量，每个变量只能用一次，且不能有前导符号，在可以使用括号的基础上，有多少种本质不同的运算方案？由于答案会很大，所以只需要输出模1000000007之后的答案。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
两个方案本质相同即，无论如何改变这些变量的值，两种方案的结果不变(当然，要在表达式有意义的基础上)<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
例如:a/b/c和a/(b*c)的本质是相同的。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
</span></div>
<div class="pdsec" style="border-bottom: rgb(187,187,187) 1px solid; padding-bottom: 4px; background-color: rgb(248,248,255); margin: 8px 0px 4px; padding-left: 6px; padding-right: 0px; font-family: 微软雅黑, 黑体, 华文细黑; font-weight: bold; padding-top: 4px; border-top-left-radius: 4px; border-top-right-radius: 4px; border-bottom-right-radius: 0px; border-bottom-left-radius: 0px"><br/>
<font size="3"><br/>
</font></div>
</div>
<p></p></div>

# Input

<div class="content"><p></p>
<div></div>
<div>
<div id="pcont1" style="text-align: left; padding-bottom: 0px; margin: 20px 0px 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px">
<div class="pdcont" style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: 14px; padding-top: 0px"><span style="font-size: medium">　　输入的第一行包含一个正整数Test表示数据组数。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
以下Test行，每行表示一个询问N,询问N个变量的本质不同的表达式方案。<br style="padding-bottom: 0px; margin: 0px; padding-left: 0px; padding-right: 0px; padding-top: 0px"/>
</span></div>
<div class="pdsec" style="border-bottom: rgb(187,187,187) 1px solid; padding-bottom: 4px; background-color: rgb(248,248,255); margin: 8px 0px 4px; padding-left: 6px; padding-right: 0px; font-weight: bold; padding-top: 4px; border-top-left-radius: 4px; border-top-right-radius: 4px; border-bottom-right-radius: 0px; border-bottom-left-radius: 0px"><font color="#200000" size="3" face="&#39;Times New Roman&#39;, 宋体"><br/>
</font></div>
</div>
</div></div>

# Output

<div class="content"><div class="pdsec" style="border-bottom: rgb(187,187,187) 1px solid; text-align: left; padding-bottom: 4px; background-color: rgb(248,248,255); margin: 8px 0px 4px; padding-left: 6px; padding-right: 0px; font-family: 微软雅黑, 黑体, 华文细黑; font-size: 16px; font-weight: bold; padding-top: 4px; border-top-left-radius: 4px; border-top-right-radius: 4px; border-bottom-right-radius: 0px; border-bottom-left-radius: 0px"><span style="font-family: &#39;Times New Roman&#39;, 宋体; color: rgb(32,0,0); font-size: medium">　　输出一个非负整数，表示方案数模1000000007后的值。</span></div>
<div class="pddata" style="text-align: left; padding-bottom: 0px; margin: 0px; padding-left: 24pt; padding-right: 0px; font-family: &#39;Courier New&#39;, FixedSys; color: rgb(32,0,0); padding-top: 0px"><font size="3"><br/>
</font></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><div>样例说明</div><br/>
<div>　　对于N=2,有a+b,a-b,b-a,a*b,a/b,b/a六种方案。</div><br/>
<div>数据规模和约定</div><br/>
<div>　　对于30%的数据，满足1≤N≤50</div><br/>
<div>　　对于100%的数据,满足1≤N≤2000,1≤Test≤2000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

