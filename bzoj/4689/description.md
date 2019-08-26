
# Description

<div class="content"><div>Abacus教授刚刚完成了一个制作数表的计算引擎的设计。它被设计用于同时计算一个多项式在许多点的取值。例如</div>
<div>对于多项式 f(x)=x^2+2x+1 ，一种可能的计算结果是 f(0)=1,f(1)=4,f(2)=9.f(3)=16,f(4)=25 。不幸的是，引</div>
<div>擎存在一个故障使得计算出的值总有一个是错的，例如对于上述多项式，它可能输出 1,4,12,16,25 而不是 1,4,9</div>
<div>,16,25 。请你帮教授找出发生故障的是哪个点值。</div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组测试数据。</div>
<div>每组数据第一行包含一个正整数 d 表示多项式的度数，即多项式最高次项的项数，保证 d≤5 。</div>
<div>接下来 d+3 行，每行一个实数，第 i 行表示输出的 f(i)  的值，保证-100.0≤f(i)≤100.0 。</div>
<div>你可以认为恰好只有一个点值出故障，且与实际值的误差超过 1.0 。</div>
<div>由于不可避免的误差，其他数字与精确值的误差不超过10^(-6)  。</div>
<div>输入以一个零作为结束。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，输出一个非负整数 i 表示 f(i)  的值发生故障。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1.0<br/>
4.0<br/>
12.0<br/>
16.0<br/>
25.0<br/>
1<br/>
-30.5893962764<br/>
5.76397083962<br/>
39.3853798058<br/>
74.3727663177<br/>
4<br/>
42.4715310246<br/>
79.5420238202<br/>
28.0282396675<br/>
-30.3627807522<br/>
-49.8363481393<br/>
-25.5101480106<br/>
7.58575761381<br/>
5<br/>
-21.9161699038<br/>
-48.469304271<br/>
-24.3188578417<br/>
-2.35085940324<br/>
-9.70239202086<br/>
-47.2709510623<br/>
-93.5066246072<br/>
-82.5073836498<br/>
0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
1<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

