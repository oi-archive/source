
# Description

<div class="content"><div>有n位同学，每位同学都参加了全部的m门课程的期末考试，都在焦急的等待成绩的公布。第i位同学希望在第ti天</div>
<div>或之前得知所.有.课程的成绩。如果在第ti天，有至少一门课程的成绩没有公布，他就会等待最后公布成绩的课程</div>
<div>公布成绩，每等待一天就会产生C不愉快度。对于第i门课程，按照原本的计划，会在第bi天公布成绩。有如下两种</div>
<div>操作可以调整公布成绩的时间：1.将负责课程X的部分老师调整到课程Y，调整之后公布课程X成绩的时间推迟一天</div>
<div>，公布课程Y成绩的时间提前一天；每次操作产生A不愉快度。2.增加一部分老师负责学科Z，这将导致学科Z的出成</div>
<div>绩时间提前一天；每次操作产生B不愉快度。上面两种操作中的参数X,Y,Z均可任意指定，每种操作均可以执行多次</div>
<div>，每次执行时都可以重新指定参数。现在希望你通过合理的操作，使得最后总的不愉快度之和最小，输出最小的不</div>
<div>愉快度之和即可</div>
<div></div></div>

# Input

<div class="content"><div>第一行三个非负整数A,B,C，描述三种不愉快度，详见【问题描述】；</div>
<div>第二行两个正整数n,m(1≤n,m≤105)，分别表示学生的数量和课程的数量；</div>
<div>第三行n个正整数ti，表示每个学生希望的公布成绩的时间；</div>
<div>第四行m个正整数bi，表示按照原本的计划，每门课程公布成绩的时间。</div>
<div>1&lt;=N,M,Ti,Bi&lt;=100000,0&lt;=A,B,C&lt;=100000</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，表示最小的不愉快度之和。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">100 100 2<br/>
4 5<br/>
5 1 2 3<br/>
1 1 2 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
由于调整操作产生的不愉快度太大，所以在本例中最好的方案是不进行调整; 全部<br/>
5 的门课程中，最慢的在第 3 天出成绩;<br/>
同学 1 希望在第 5 天或之前出成绩，所以不会产生不愉快度;<br/>
同学 2 希望在第 1 天或之前出成绩，产生的不愉快度为 (3 - 1) * 2 = 4;<br/>
同学 3 希望在第 2 天或之前出成绩，产生的不愉快度为 (3 - 2) * 2 = 2;<br/>
同学 4 希望在第 3 天或之前出成绩，所以不会产生不愉快度;<br/>
不愉快度之和为 4 + 2 = 6 。</span></div>

# Hint

<div class="content"><p></p><p> <span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14.3999996185303px; line-height: 18.659200668335px;">存在几组数据，使得C = 10 ^ 16</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=黑吉辽沪冀晋六省联考">黑吉辽沪冀晋六省联考</a></p></div>

