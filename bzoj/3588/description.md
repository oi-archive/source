
# Description

<div class="content"><p><span style="font-size: medium">　　对于一个n位的十进制数x（AnAn-1……A1），我们定义它的权重为：<br/>
　　F(x)=An*2n-1+An-1*2n-2+……+A1*20<br/>
　　现在，给你两个十进制数A和B，请计算出在闭区间[0, B]之中，有多少个数x的权重不大于A的权重，即F(x)&lt;=F(A)。由于答案可能很大，你只需要输出答案对1000000007（109 + 7）取模的结果即可。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　第一行一个正整数T，表示测例的个数。<br/>
　　随后T行，每行描述一个测例，包含两个非负整数A、B，之间用空格隔开。含义见问题描述。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">　　对于每个测例，单独输出一行”Case #t: ans”，其中t表示测例编号，从1开始递增，ans表示该组测例的答案（对1000000007取模后的结果）。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 100<br/>
1 10<br/>
5 100<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 1<br/>
Case #2: 2<br/>
Case #3: 13<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">样例说明<br/><br/>
　　对于Case #3，符合条件的数有0, 1, 2, 3, 4, 5, 10, 11, 12, 13, 20, 21, 100，共13个。</span></p><br/>
<p><span style="font-size: medium">　　//样例描述有修改，请注意！<br/><br/>
数据规模及约定<br/><br/>
　　对于20%的数据，A, B &lt;= 10^9；<br/><br/>
　　对于30%的数据，A, B &lt;= 10^18；</span></p><br/>
<p><span style="font-size: medium">　　对于100%的数据，A,B &lt;= 10200，T&lt;=5。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

