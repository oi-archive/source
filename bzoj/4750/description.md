
# Description

<div class="content"><div>有些人在社交网络中使用过许多的密码，我们通过将各种形式的信息转化为 01 信号，再转化为整数，可以将这个</div>
<div>人在一段时间内使用过的密码视为一个长度为 n 的非负整数序列 A_1,A_2,...,A_n 。一个人相邻几次在社交网络</div>
<div>中使用的密码很有可能是类似的，这使得密码并不是足够安全。为了检验某些人在某些时间段内是否可能受到不安</div>
<div>全的影响，我们需要计算上述序列的复杂程度。</div>
<div><img src="/source/bzoj/4750/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwMS9hYS5qcGc=.jpg" width="833" height="170" alt=""/></div>
<div></div>
<div></div>
<div>的值，这将作为我们评估密码复杂程度的一个部分。由于答案可能很大，你只需要给出答案对10^9+61 取模的值即可。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数 T ，表示有 T 组测试数据。</div>
<div>接下来依次给出每组测试数据。对于每组测试数据：</div>
<div>第一行包含一个正整数 n 。</div>
<div>第二行包含 n 个非负整数，表示 A_1,A_2,?,A_n 。</div>
<div>保证在一行中的每个整数之间有恰好一个空格，没有其他额外的空格。</div>
<div>100% 的数据满足：1≤T≤200,1≤n≤10^5,1≤∑n≤10^6,0≤A_i≤10^9</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据输出一行，包含一个整数，表示答案对10^9+61 取模的值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
61<br/>
5<br/>
1 2 3 4 5<br/>
5<br/>
10187 17517 24636 19706 18756</span></div>

# Sample Output

<div class="content"><span class="sampledata">3721<br/>
148<br/>
821283048<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

