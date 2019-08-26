
# Description

<div class="content"><div>qmqmqm希望给sublinekelzrip出一道可做题。于是他想到了这么一道题目：给一个长度为n的非负整数序列ai,你需</div>
<div>要计算其异或前缀和bi,满足条件b1=a1,bi=bi?1 xor ai(i≥2).但是由于数据生成器出现了问题，他生成的序列a</div>
<div>的长度特别长，并且由于内存空间不足，一部分ai已经丢失了，只剩余m个位置的元素已知。现在qmqmqm找到你，</div>
<div>希望你根据剩余的ai,计算出所有可能的a序列对应的b序列中∑=bi(1&lt;=i&lt;=N)的最小值。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入第一行两个非负整数n,m,分别表示原始序列a的长度及剩余元素的个数。</div>
<div>之后m行，每行2个数i,ai，表示一个剩余元素的位置和数值。</div>
<div>1&lt;=N&lt;=10^9,0&lt;=M&lt;=Min(n,10^5),0&lt;=ai&lt;=10^9</div>
<div>注意未知的 ai 可以超过已知 ai 的范围。</div>
<div>保证输入中所有的 i 不同，且满足 1 ≤ i ≤ n。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数表示可能的最小值</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
4 0<br/>
3 7<br/>
5 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
已知的 a 序列为： X, X, 7, 0, 0, 其中X表示这个位置丢失了。一种可能的 a 序列为<br/>
0, 7, 7, 0, 0, 对应的 b 序列为 0, 7, 0, 0, 0, 和最小为 7。可以证明不存在和更小的情况</span></div>

# Hint

<div class="content"><p></p><div>来自 CodePlus 2017 11 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。</div><br/>
<div>Credit：idea/卢政荣　命题/卢政荣　验题/何昊天</div><br/>
<div>Git Repo：https://git.thusaac.org/publish/CodePlus201711</div><br/>
<div>本次比赛的官方网址：cp.thusaac.org</div><br/>
<div>感谢腾讯公司对此次比赛的支持。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

