
# Description

<div class="content"><div>FarmerJohn打算将电话线引到自己的农场，但电信公司并不打算为他提供免费服务。于是，FJ必须为此向电信公司</div>
<div>支付一定的费用。FJ的农场周围分布着N(1&lt;=N&lt;=1,000)根按1..N顺次编号的废弃的电话线杆，任意两根电话线杆间</div>
<div>都没有电话线相连。一共P(1&lt;=P&lt;=10,000)对电话线杆间可以拉电话线，其余的那些由于隔得太远而无法被连接。</div>
<div>第i对电话线杆的两个端点分别为A_i、B_i，它们间的距离为L_i(1&lt;=L_i&lt;=1,000,000)。数据中保证每对{A_i，B_i</div>
<div>}最多只出现1次。编号为1的电话线杆已经接入了全国的电话网络，整个农场的电话线全都连到了编号为N的电话线</div>
<div>杆上。也就是说，FJ的任务仅仅是找一条将1号和N号电话线杆连起来的路径，其余的电话线杆并不一定要连入电话</div>
<div>网络。经过谈判，电信公司最终同意免费为FJ连结K(0&lt;=K&lt;N)对由FJ指定的电话线杆。对于此外的那些电话线，FJ</div>
<div>需要为它们付的费用，等于其中最长的电话线的长度（每根电话线仅连结一对电话线杆）。如果需要连结的电话线</div>
<div>杆不超过K对，那么FJ的总支出为0。请你计算一下，FJ最少需要在电话线上花多少钱。</div></div>

# Input

<div class="content"><div>* 第1行: 3个用空格隔开的整数：N，P，以及K</div>
<div>* 第2..P+1行: 第i+1行为3个用空格隔开的整数：A_i，B_i，L_i</div></div>

# Output

<div class="content"><div>* 第1行: 输出1个整数，为FJ在这项工程上的最小支出。</div>
<div>如果任务不可能完成， 输出-1</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 7 1<br/>
1 2 5<br/>
3 1 4<br/>
2 4 8<br/>
3 2 3<br/>
5 2 9<br/>
3 4 7<br/>
4 5 6<br/>
输入说明:<br/>
一共有5根废弃的电话线杆。电话线杆1不能直接与电话线杆4、5相连。电话<br/>
线杆5不能直接与电话线杆1、3相连。其余所有电话线杆间均可拉电话线。电信<br/>
公司可以免费为FJ连结一对电话线杆。</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
输出说明:<br/>
FJ选择如下的连结方案：1-&gt;3；3-&gt;2；2-&gt;5，这3对电话线杆间需要的<br/>
电话线的长度分别为4、3、9。FJ让电信公司提供那条长度为9的电话线，于是，<br/>
他所需要购买的电话线的最大长度为4。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

