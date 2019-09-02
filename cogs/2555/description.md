# 题目描述


<div id="content">
<h3>
Mahjong
</h3>
<h5>
Time Limit : 2000/2000ms (Java/Other)   Memory Limit : 234567/234567K (Java/Other)
</h5>
<h5>
Total Submission(s) : 0   Accepted Submission(s) : 0
</h5>
<h3 onclick="ObjFolder(&#39;procon&#39;)">
Problem Description
</h3>
<div id="procon">
麻将源于中国，流行于世界。这道题不要求你会打麻将，而且我们将使用不同的规则。<br/>
<br/>
在我们的麻将中，玩家有4K张牌。每张牌上写着一个点数，1~K的每个点数都有四张完全相同的牌。例如，对于K=5，牌组就是：1, 1, 1, 1, 2, 2, 2, 2, 3, 3, 3, 3, 4, 4, 4, 4, 5, 5, 5, 5.<br/>
<br/>
玩家的目标是从牌组中选出M张，形成一副和牌。一幅和牌由若干（可能为零）个三元组和恰好一个对子组成。一个对子包含两张点数相同的牌。一个三元组要么是三张点数相等的牌（如“2 2 2”），要么是三张点数连续的牌（例如，“3，4，5”）.不考虑点数循环的情况，例如，“4 5 1”不是合法的三元组。<br/>
<br/>
给定K和M，求能够组成多少种不同的和牌方案。两种方案相同当且仅当它们包含的牌的集合相同，无论它们的三元组和对子为何。我们认为相同点数的牌完全相同。例如，对于K=4，M=8，如下两种和牌相同：<br/>
<br/>
&#34;1 2 3, 1 2 3, 4 4&#34;<br/>
<br/>
&#34;1 1, 2 3 4, 2 3 4&#34;
</div>
<h3 onclick="ObjFolder(&#39;proinput&#39;)">
Input
</h3>
<div id="proinput">
第一行一个正整数T(1&lt;=T&lt;=100)，代表数据组数。接下来T行，每行两个正整数K(1&lt;=K&lt;=200)和M(2&lt;=M&lt;=min(200,4K)，且M==2 (mod 3)).
</div>
<h3 onclick="ObjFolder(&#39;prooutput&#39;)">
Output
</h3>
<div id="prooutput">
对每组数据，输出一行形如Case #x: y，其中x是第几组数据，从1编号，y是和牌方案数模10^9+7的值。
</div>
<h3 onclick="ObjFolder(&#39;prosamplein&#39;)">
Sample Input
</h3>
<div id="prosamplein">
<pre>4
1 2
3 5
4 5
9 14</pre>
</div>
<h3 onclick="ObjFolder(&#39;prosampleout&#39;)">
Sample Output
</h3>
<div id="prosampleout">
<pre>Case #1: 1
Case #2: 9
Case #3: 20
Case #4: 13259</pre>
</div>
<h3 onclick="ObjFolder(&#39;prohint&#39;)">
Hint
</h3>
<div id="prohint">
对第一组数据，只有四张牌：1,1,1,1，因此唯一和牌方案为&#34;1 1&#34;。<br/>
<p>
  
</p>
(注意所有的1完全相同，所以不考虑你选取哪两张。)<br/>
<br/>
对第二组数据，有12张牌： 1, 1, 1, 1, 2, 2, 2, 2, 3, 3, 3, 3 ，和牌方案包含一个三元组和一个对子。九种方案如下:<br/>
<br/>
1 1 1, 2 2<br/>
1 1 1, 3 3<br/>
2 2 2, 1 1<br/>
2 2 2, 3 3<br/>
3 3 3, 1 1<br/>
3 3 3, 2 2<br/>
1 2 3, 1 1<br/>
1 2 3, 2 2<br/>
1 2 3, 3 3<br/>
<br/>
注意&#34;3 3, 1 1 1&#34;和&#34;1 1 1, 3 3&#34;相同，因为它们包含的牌的集合相同。
</div>
<h3 onclick="ObjFolder(&#39;prosource&#39;)">
Source
</h3>
<div id="prosource">
The 2015 China Collegiate Programming Contest
</div>
<hr color="#1A5CC8" size="1"/>
</div>
