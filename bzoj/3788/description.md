
# Description

<div class="content"><div>话说考古学家ZL走进了一个山洞…………</div>
<div>ZL在山洞深处发现了一组密码锁，并断定这里藏着数不清的宝藏。经过一番寻找，ZL发现该密码锁上写着一串阿拉伯数字，看起来这些数字中有着一些微妙的联系。于是他动用了120分脑细胞，凭着藐视一切IMO选手的强大逻辑推理能力，找到了规律，并破解了几个密码锁。</div>
<div>可ZL毕竟是人，他也是会累的呀T_T</div>
<div>况且他的GPS显示前方还有成百上千个密码锁~！！！！</div>
<div>于是他把问题简化了一下，求助于身为OI神犇的你。</div>
<div>{============================================}</div>
<div>数列a[n]由如下关系式定义：</div>
<div>a[0]=0;</div>
<div>a[n]=f(a[n-1])</div>
<div>其中f(x)是一个正整数系数的m次多项式</div>
<div>对任意给定的x和y，求a[x]和a[y]的最大公约数d</div>
<div>令s为d模x的余数，t为d模y的余数</div>
<div>给定r和一个奇质数p，保证r不是p的整数倍</div>
<div>废话完毕，现在我们的问题是：</div>
<div>求方程 (rx2+sx+t) mod p = 0</div>
<div>有几个模p意义下的正整数解</div>
<div>对每个函数y=f(x)将进行T次询问</div>
<p></p></div>

# Input

<div class="content"><div>输入文件包括T+3行</div>
<div>第一行一个正整数m</div>
<div>第二行m+1个正整数cm，…，c0，其中ci(i=m，m-1，…，0)表示f(x)中xi的系数</div>
<div>第三行一个正整数T，表示询问次数</div>
<div>以下T行每行4个正整数，分别表示x，y，r，p</div>
<div>//保证输入文件合法</div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出文件包含T行，每行仅输出一个整数表示方程有多少组解（模p的意义下）</div>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
2 1<br/>
1<br/>
4 8 7 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
</span></div>

# Hint

<div class="content"><p></p><p><a id="fck_paste_padding">﻿</a>对于100%的数据，T&lt;=1000，m&lt;=10，x&lt;y，x&lt;=10^5，y&lt;=10^8，p&lt;=10^8。</p><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

