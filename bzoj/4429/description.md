
# Description

<div class="content"><div>Ellen is teaching elementary math to her students and the time for the final exam has come. The exam consists of n questions. In each question the students have to add (+), subtract (−) or multiply (∗) a pair of numbers.</div>
<div>Ellen has already chosen the n pairs of numbers. All that remains is to decide for each pair which of the three possible operations the students should perform. To avoid students getting bored, Ellen wants to make sure that the n correct answers to her exam are all different.</div>
<div>Please help Ellen finish constructing the exam by automating this task.</div>
<div>Ellen给她的学生教小学数学。期末考试已经来临了。考试有n个题目，每一个题目学生们都要对一对数字进行加（+），减（-），乘（*）运算。</div>
<div>Ellen已经选好了n对数。剩下的是决定学生们应该对每对数执行什么运算。为了不让学生们感到厌烦，Ellen想确保n个正确答案都不一样。</div>
<div>请帮助Ellen自动化地构建考试。</div>
<p></p></div>

# Input

<div class="content"><div>The input consists of:</div>
<div>•<span class="Apple-tab-span" style="white-space: pre;">	</span>one line with one integer n (1≤n≤2500), the number of pairs of numbers;</div>
<div>•<span class="Apple-tab-span" style="white-space: pre;">	</span>n lines each with two integers a and b (−10^6≤a,b≤10^6), a pair of numbers used.</div>
<div>输入包括：</div>
<div>第一行是一个整数n（1&lt;=n&lt;=2500），表示共有n道题目。</div>
<div>接下来n行每行有2个整数a和b（-10^6&lt;=a,b&lt;=10^6）,表示每一题使用的整数。</div>
<p></p></div>

# Output

<div class="content"><div>For each pair of numbers (a,b) in the same order as in the input, output a line containing a valid equation. Each equation should consist of five parts: a, one of the three operators, b, an equals sign (=), and the result of the expression. All the n expression results must be different.</div>
<div>If there are multiple valid answers you may output any of them. If there is no valid answer, output a single line with the string “impossible” instead.</div>
<div>对于输入中的每一对(a,b)，输出一行有效的方程。每一个方程应该包含5部分：a，+、-、*中的一个运算符，b，=，答案。N个答案必须不同。</div>
<div>如果有多个有效答案，你可以输出任意一个。如果没有答案，输出“impossible”。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1000000 1000000<br/>
1000000 1000000<br/>
1000000 1000000<br/>
-1000000 1000000<br/>
-1000000 1000000</span></div>

# Sample Output

<div class="content"><span class="sampledata">1000000-1000000=0<br/>
1000000*1000000=1000000000000<br/>
1000000+1000000=2000000<br/>
-1000000-1000000=-2000000<br/>
-1000000*1000000=-1000000000000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

