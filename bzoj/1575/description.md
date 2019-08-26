
# Description

<div class="content"><p><span style="font-size: medium">为了研究农场的气候,Betsy帮助农夫John做了N(1 &lt;= N &lt;= 100)次气压测量并按顺序记录了结果M_1...M_N(1 &lt;= M_i &lt;= 1,000,000). Betsy想找出一部分测量结果来总结整天的气压分布. 她想用K(1 &lt;= K &lt;= N)个数s_j (1 &lt;= s_1 &lt; s_2 &lt; ... &lt; s_K &lt;= N)来概括所有测量结果. 她想限制如下的误差: 对于任何测量结果子集,每一个非此子集中的结果都会产生误差.总误差是所有测量结果的误差之和.更明确第说, 对于每一个和所有s_j都不同的i: * 如果 i 小于 s_1, 误差是: 2 * | M_i - M_(s_1) | * 如果i在s_j和s_(j+1)之间,误差是: | 2 * M_i - Sum(s_j, s_(j+1)) | 注:Sum(x, y) = M_x + M_y; (M_x 和 M_y 之和) * 如果i大于s_K,误差为: 2 * | M_i - M_(s_K) | Besty给了最大允许的误差E (1 &lt;= E &lt;= 1,000,000),找出最小的一部分结果史得误差最多为E. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第一行: 两个空格分离的数: N 和 E</span></p>
<p><span style="font-size: medium"> * 第2..N+1行: 第i+1行包含一次测量记录:M_i </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第一行: 两个空格分开的数: 最少能达到误差小于等于E的测量数目和使用那个测量数目能达到的最小误差. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 20<br/>
10<br/>
3<br/>
20<br/>
40<br/>
<br/>
输入解释:<br/>
<br/>
Bessie做了4次记录,分别为10,3,20,和40.最大允许误差是20.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 17<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">选择第二和第四次测量结果能达到最小误差17. 第一次结果的误差是2*|10-3| = 14; 第三次结果的误差是|2*20 - (3+40)|=3. </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

