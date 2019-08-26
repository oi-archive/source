
# Description

<div class="content"><div>小时候，小H是一名热爱学习的小学生。有一天，在数学课上，老师留了一道题让大家思考：一个整数，已知它和</div>
<div>整数a的最大公约数等于b，和整数c的最大公约数等于d。请算出这个整数的值。爱学习的小H没花多少时间就发现</div>
<div>，可能有很多整数都满足这样的条件，于是就去把疑惑告诉老师。老师很高兴，鼓励小H找出不小于整数l且不大于</div>
<div>整数r的所有满足条件的整数有哪些，观察一下有没有什么规律。然而这个问题太困难了，小H当时没有解决。现在</div>
<div>，已经读大学的小H在翻阅小学日记时重新看到了这个问题，可是依然不会做。请你帮忙解决这个问题。由于满足</div>
<div>条件的整数可能有很多，你只需要输出它们的和。</div>
<div></div></div>

# Input

<div class="content"><div>第一行，一个整数 T， 表示有几组测试数据。</div>
<div>接下来 T 行， 每行为六个由空格隔开的正整数， 依次是 l, r, a, b, c, d。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出 T 行，每行一个整数， 依次是每组数据的答案， 即 l 到 r 之间所有和 a 的最大公约</div>
<div>数为 b 并且和 c 的最大公约数为 d 的整数之和。 如果不存在这样的整数，输出 0 即可。</div>
<div>1 ≤ l ≤ r ≤ 10^30， 1 ≤ a, b, c, d ≤ 1014， 1 ≤ T ≤ 4， 保证 b 是 a</div>
<div>的约数， d 是 c 的约数</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 20 2 2 12 6<br/>
4 6 3 3 4 4<br/>
1 1000000000 1 1 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
0<br/>
333333333666666667<br/>
<br/>
【样例解释】<br/>
第 1 组数据： 1 到 20 之间满足条件的数只有 6 和 18， 和等于 24。<br/>
第 2 组数据： 4 到 6 之间不存在满足条件的数。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

