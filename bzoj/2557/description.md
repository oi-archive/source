
# Description

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Bartie and his friends compete in the Team Programming Contest. There are n contestants on each team, and each team has access to n  computers. The contest lasts t minutes, during which the contestants are to solve m programming problems. Furthermore, penalties are imposed on the teams: solving a problem s minutes since the beginning of the contest amounts to  s penal points. The team that solved the most problems wins the contest, with ties broken in favour of the team with smaller penalty. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">On the contest day Bartie quickly glances over the problem statements and distributes them among his teammates. He knows his team so well that he can exactly assess who is able to solve which problem. Solving any problem takes any contestant that is able to solve it exactly r minutes of using the computer. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Bartie&#39;s team did not fare well in this year&#39;s contest. Bartie is obsessed with the thought that it might be his fault, due to wrong decisions regarding the distribution of problems. He asks you to write a program that, given what Bartie knew at the beginning of the contest, determines the best possible result of Bytie&#39;s team, together with the assignment of problems to team members that attains the result. </span></span></div>
<div style="line-height: 140%" align="left"></div>
<p><span style="font-size: medium"><!--StartFragment --></span></p>
<div><span style="font-size: medium">n个人m个题目，每个题要r分钟完成。比赛有t分钟。给出每个人会做哪些题目，请你安排一个每个人在什么时候做什么题目，使得做出来的题目数最多。在做题数一样多的情况下，罚时尽量小。<br/>
 <br/>
</span></div></div>

# Input

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: 14pt; color: #444444; line-height: 140%">Five integers n,m,r,t and k(1&lt;=n,m&lt;=500,1&lt;=r,t&lt;=10^6)) are given in the first line of the standard input, separated by single spaces. These denote, respectively: the number of contestants on a team, the number of problems, the time it takes a contestant to solve a problem, the duration of the contest, and the number of contestant-problem pairs given on the input. Each of the following k lines holds two integers a and b(1&lt;=a&lt;=n,1&lt;=b&lt;=m)), separated by a single space, denoting that the contestant a is able to solve the problem b. Each such pair appears at most once in the input. </span></div>
<div style="line-height: 140%" align="left"><span style="font-size: 14pt; color: #444444; line-height: 140%">In tests worth at least 30% of the points it additionally holds that n,m&lt;=100. </span></div>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: 14pt; color: #444444">In the first line of the standard output the best possible result of Bytie&#39;s team should be printed as two numbers separated by a single space: the number of solved problems z and the total penal points.</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 4 3 15 4<br/>
1 1<br/>
2 3<br/>
1 4<br/>
1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 12</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

