
# Description

<div class="content"><div>Bessie为了存钱给她的牛棚新建一间隔间，开始在当地的马戏团里表演，通过在平衡木上小心地来回走动来展示她</div>
<div>卓越的平衡能力。Bessie能够通过表演赚到的钱取决于她最终成功跳下平衡木的位置。平衡木上从左向右的位置记</div>
<div>为0,1,…,N+1。如果Bessie到达了位置0或是N+1，她就会从平衡木的一端掉下去，遗憾地得不到报酬。如果Bessie</div>
<div>处在一个给定的位置k，她可以进行下面两项中的任意一项：</div>
<div>1. 投掷一枚硬币。如果背面朝上，她前往位置k-1，如果正面朝上，她前往位置k+1（也就是说，每种可能性1/2的概率）。</div>
<div>2. 跳下平衡木，获得f(k)的报酬（1≤f(k)≤10^9）。</div>
<div>Bessie意识到她并不能保证结果能够得到某一特定数量的报酬，这是由于她的移动是由随机的掷硬币结果控制。然</div>
<div>而，基于她的起始位置，她想要求出当她进行一系列最优的决定之后，她能够得到的期望报酬（“最优”指的是这</div>
<div>些决定能够带来最高可能的期望报酬）。例如，如果她的策略能够使她以1/2的概率获得10的报酬，1/4的概率获得</div>
<div>8的报酬，1/4的概率获得0的报酬，那么她的期望报酬为加权平均值10(1/2)+8(1/4)+0(1/4)=7</div>
<p></p></div>

# Input

<div class="content"><p>输入的第一行包含N（2≤N≤10^5）。以下N行包含f(1)…f(N)</p>
<p></p></div>

# Output

<div class="content"><div>
<div>输出N行。第i行输出105乘以Bessie从位置i开始使用最优策略能够获得的报酬的期望值，向下取整。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">150000<br/>
300000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum ">Platinum </a></p></div>

