# 题目描述


<h3>
【题目描述】
</h3>
<p>
 求一个<strong>字典序最小</strong>字串S。根据已知的一些子串在其中出现的次数和位置。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数n(1 ≤ n ≤ 10^5) — 已知子串的数目。
</p>
<p>
接下来n行是这些子串的信息。第i行包含子串ti，和正整数ki（表示ti在s中出现次数）,然后有升序排列的ki个正整数表示ti在s中出现位置。保证ti长度之和不超过10^6，且ki之和不超过10^6+2。 子串ti可以<strong>相同</strong>.
</p>
<p>
保证数据不会自相矛盾,因此至少存在一个答案。
</p>
<p>
数据字符集为小写字母
</p>
<h3>
【输出格式】
</h3>
<p>
输出<strong>字典序最小</strong> 的满足条件的字串s。
</p>
<h3>
【样例输入1】
</h3>
<p>
<br/>
</p>
<p>
3
</p>
<p>
a 4 1 3 5 7
</p>
<p>
ab 2 1 5
</p>
<p>
ca 1 4
</p>
<p>
<br/>
</p>
<h3>
【样例输出1】
</h3>
<p>
 abacaba
</p>
<h3>
【样例输入2】
</h3>
<p>
1
</p>
<p>
a 1 3
</p>
<h3>
【样例输出2】
</h3>
<p>
 aaa
</p>
<h3>
【样例输入3】
</h3>
<p>
3
</p>
<p>
ab 1 1
</p>
<p>
aba 1 3
</p>
<p>
ab 2 3 5
</p>
<h3>
【样例输出3】
</h3>
<p>
 ababab
</p>
<h3>
【来源】
</h3>
<p>
<u><strong>CodeForces</strong></u> 
</p>
<p>
<a href="http://codeforces.com/contest/827/problem/A" target="_blank">http://codeforces.com/contest/827/problem/A</a> 
</p>
<p>
<br/>
</p>
