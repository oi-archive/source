
# Description

<div class="content"><div>
<div>有一天，ydc在网上乱逛的时候，发现了一场比赛。这场比赛要求正好n个人参加，且如果你能在这场比赛中获得第i名，那么你可以得到pi的软妹币。</div>
<div>有奖金可以拿，ydc是自然不会放过这个便宜的，而且软妹币肯定是拿得越多越好。所以ydc制定了一系列的策略，并且提前了解了其他n-1名选手的各项能力，根据他们的能力值分别计算出了他们得分的概率。</div>
<div>这场考试的满分为1分，最低为0分，分数可以为任意小数。对于第i个人，他得x分的概率，与函数fi(x)成正比。</div>
<div>如果一个人的函数为f(x)=2，那么他获得任意分数的概率都是相等的；如果一个人的函数为f(x)=2-x，那么他获得越高的分的概率就越低，且他获得0分的概率是获得1分的概率两倍。</div>
<div>现在你需要计算的是如果ydc在这场比赛中使用当前的策略，他期望能得到多少的奖金，从而决定是否采用当前的策略。由于分数可以为小数，所以无需考虑排名相等的情况。</div>
<div>ydc当然早就算出来啦！但是他为了考考你，特地要你把答案对于998244353（7*17*2^23+1，一个质数）取模之后再输出来。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>输入共n+2行。</div>
<div>第一行包含一个整数n。</div>
<div>在第二行有n个整数，第i个数代表pi。</div>
<div>接下来n-1行，每行第一个数为ti，代表第i个人所对应的函数是一个ti-1次函数，接下来ti个实数，第j个数代表该函数中xj-1项的系数。</div>
<div>最后一行，第一个数为tn，代表ydc所对应的函数是一个tn-1次函数，接下来tn个实数，第j个数代表该函数中xj-1项的系数。</div>
<div>保证所有人的函数在[0,1]的范围以内大于等于0，且函数在[0,1]的范围内与x轴所成的面积在模意义下不等于0。</div>
<p></p></div>

# Output

<div class="content"><div>输出1行，包含一个整数，表示ydc期望能获得的软妹币。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 1<br/>
1 1.00<br/>
2 0.00 1.00</span></div>

# Sample Output

<div class="content"><span class="sampledata">665496237</span></div>

# Hint

<div class="content"><p></p><div>N&lt;=500</div><br/>
<div>S&lt;=4000</div><br/>
<div>S=Sigma(T_i)</div><br/>
<div>输入的所有实数仅有2位小数，且除了常数项以外的系数绝对值均小于5，常数项的绝对值小于30。</div><br/>
<div>由于出题人太懒了，所有数据均为随机生成。</div><br/>
<div>pi的范围在0到10000之间，且对于1≤i&lt;n，有pi≥pi+1。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年集训队互测">2015年集训队互测</a></p></div>

