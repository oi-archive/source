<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在一个无穷大的平面上的原点处,有一个骑士。这个骑士每次可以走 A⃗ 或 B⃗ 。现在,骑士想去点 (X, Y ) 。由于某种特殊原因,平面上有 K 个点不能被经过。骑士想知道,他总共有多少种方案可以到 达目标点。注意,骑士到达了目标点之后仍然可以继续移动。<br/>
<br/>
　　两个方案不同,当且仅当两个方案的长度不同,或者存在至少一个 i ,使得第 i 步之后,骑士位于 不同的位置。</div>
# 输入格式

<div class="pdcont">　　本题有多组测试数据,第一行为一个正整数 T ,表示数据组数。<br/>
　　接下来为 T 组测试数据。对于每组测试数据<br/>
　　第一行3个可能为负的整数X,Y,K,意义如上。<br/>
　　第二行4个可能为负的整数,分别表示A⃗和B⃗<br/>
<br/>
<br/>
　　第三行 2K 个 可能为负 的整数,分别表示不能被经过的 K 个点。</div>
# 输出格式

<div class="pdcont">　　对于每组测试数据,你需要输出一行一个整数,即到达目标点的方案数。由于方案数过多,只需输出模 10^9 + 7 后的值即可。如果有无穷种方案,请输出 -1 。</div>
# 样例输入

<div class="pddata">3<br/>
<br/>
3 3 0<br/>
<br/>
1 2 2 1<br/>
9 9 2<br/>
1 2 2 1<br/>
1 2 6 6<br/>
1 1 0<br/>
0 0 0 0</div>
# 样例输出

<div class="pddata">2<br/>
4<br/>
0</div>
# 数据规模和约定

<div class="pdcont">　　定义2.6.1 向量⃗a和⃗b共线,当且仅当存在至少一组不全为0的实数(u,v),使得<br/>
<br/>
<br/>
　　u ⃗a + v ⃗b = ⃗0<br/>
<br/>
<br/>
　　测试点编号 数据范围<br/>
　　0: T =100,K =0,A⃗和B⃗不共线,坐标绝对值≤10<br/>
<br/>
<br/>
　　1:T =100,K =0,A⃗和B⃗不共线,坐标绝对值≤500<br/>
　　2-3:T =100,K ≤15,A⃗和B⃗不共线,坐标绝对值≤100<br/>
　　4-6:T =100,K ≤100,A⃗和B⃗不共线,坐标绝对值≤500<br/>
　　7:T = 100,K = 0,坐标绝对值≤ 10<br/>
　　8-9:T =100,K =0,坐标绝对值≤500<br/>
　　10 - 13:T = 100,K ≤ 15,坐标绝对值≤ 100<br/>
　　14 - 19:T = 100,K ≤ 100,坐标绝对值≤ 500</div>

</div>