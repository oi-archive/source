
# Description

<div class="content"><div>九条可怜是一个热爱出题的女孩子。</div>
<div></div>
<div>虽然出题本身是一件非常有趣的事情，但是要把题目给出成正式比赛，就不是那么有趣了：</div>
<div>造数据总是一件让人心力憔悴的事情。</div>
<div></div>
<div>在ZJOI2018Day1中，可怜出了一道和树相关的非常有趣的题，</div>
<div>她打算采用一种常用的方式随机生成一棵n个节点的有根树：</div>
<div></div>
<div>节点1作为树的根。</div>
<div>对于i∈[2,n]，独立地从[1,i)中等概率随机选取一个节点作为i的父亲。</div>
<div></div>
<div>可怜不是很想考虑这样随机出来的数据能不能卡掉暴力，毕竟乱搞也是OI比赛的一部分。</div>
<div>可怜比较在意的是题目的区分度，以及是不是所有可能的分数都出现了。</div>
<div>因此，可怜希望任何两个测试点的树是有区别的：</div>
<div>这样就可能会有错误的程序能只通过其中一个点。</div>
<div></div>
<div>因此，可怜想要计算，通过上面的方法独立的随机生成k棵n个节点的有根树T<sub>1</sub>至T<sub>k</sub>，</div>
<div>他们两两同构的概率是多少。</div>
<div></div>
<div>两棵n个节点的有根树T1和T2同构当且仅当存在长度为n的排列p，</div>
<div>满足p<sub>1</sub>=1，且对于存在i∈[2,n]，若i在T<sub>1</sub>的父亲是f，则p<sub>i</sub>在T<sub>2</sub>的父亲是p<sub>f</sub>。</div>
<div></div></div>

# Input

<div class="content"><div>
<div>第一行输入三个整数n,k,p，表示节点个数，树的个数以及模数。</div>
<div>10^8&lt;=p&lt;=10^9,且p是质数。</div>
<div>N&lt;=2000</div>
<div>K&lt;=10^9</div>
</div>
<div></div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，表示答案对p取模后的值。</div>
<div>即如果答案的最简分数表示为a/b，输出a×b<sup>−1</sup> mod p。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 998244353<br/>
3 2 998244353<br/>
4 2 998244353<br/>
10 2 998244353<br/>
50 233 998244353</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
499122177<br/>
332748118<br/>
113919852<br/>
634280054<br/>
样例中有五组不同的数据，所以输入格式略有不同。<br/>
在实际的测试数据中，输入只有一行。在第一组数据中，能够生成的树是唯一的，<br/>
因此生成的两棵树必定相同。<br/>
在第二组数据中，能够生成的树只有两种，他们是不同构的。<br/>
因此生成的两棵树同构的概率为1，在模998244353意义下为499122177。<br/>
在第三组数据中，能够生成的树有6种，如下图所示。<br/>
其中第二、三、四棵（第一排中间三棵）是同构的，其余两两不同构。<br/>
因此生成的两棵树同构的概率为1，在模998244353意义下为332748118。</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/5307/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwNC92djEoMykuanBn.jpg" width="501" height="260" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

