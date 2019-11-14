
# Description

<div class="content"><p>lqp在为出题而烦恼，他完全没有头绪，好烦啊… 他首先想到了整数拆分。整数拆分是个很有趣的问题。给你一个正整数N，对于N的一个整数拆分就是满足任意m&gt;0，a1 ,a2 ,a3…am&gt;0，且a1+a2+a3+…+am=N的一个有序集合。通过长时间的研究我们发现了计算对于N的整数拆分的总数有一个很简单的递推式，但是因为这个递推式实在太简单了，如果出这样的题目，大家会对比赛毫无兴趣的。然后lqp又想到了斐波那契数。定义F0=0，F1=1，Fn=Fn-1+Fn-2 (n&gt;1)，Fn就是斐波那契数的第n项。但是求出第n项斐波那契数似乎也不怎么困难… lqp为了增加选手们比赛的欲望，于是绞尽脑汁，想出了一个有趣的整数拆分，我们暂且叫它：整数的lqp拆分。和一般的整数拆分一样，整数的lqp拆分是满足任意m&gt;0，a1 ,a2 ,a3…am&gt;0，且a1+a2+a3+…+am=N的一个有序集合。但是整数的lqp拆分要求的不是拆分总数，相对更加困难一些。对于每个拆分，lqp定义这个拆分的权值Fa1Fa2…Fam，他想知道对于所有的拆分，他们的权值之和是多少？简单来说，就是求 由于这个数会十分大，lqp稍稍简化了一下题目，只要输出对于N的整数lqp拆分的权值和mod 109（10的9次方）+7输出即可。</p></div>

# Input

<div class="content"><p>输入的第一行包含一个整数N。</p></div>

# Output

<div class="content"><p>输出一个整数，为对于N的整数lqp拆分的权值和mod 109（10的9次方）+7。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
【样例说明】<br/>
	F0=0，F1=1，F2=1，F3=2。<br/>
对于N=3，有这样几种lqp拆分：<br/>
3=1+1+1, 权值是1*1*1=1。<br/>
3=1+2，权值是1*2=2。<br/>
3=2+1，权值是2*1=2。<br/>
所以答案是1*1*1+1*2+2*1=5。</span></div>

# Hint

<div class="content"><p></p><p>20%数据满足：1≤N≤25 50%数据满足：1≤N≤1000 100%数据满足：1≤N≤1000000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

