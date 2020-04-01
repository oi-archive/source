
# Description

<div class="content"><div>给出一张n个点的有向图G(V,E)。对于任意两个点u,v(u可以等于v)，u向v的连边数为：</div>
<div>∑OUT(u,i) * IN(v,i),其中1&lt;=i&lt;=K</div>
<div>其中k和数组out,in均已知，现在给出m个询问，每次询问给出三个参数u,v,d，你需要回答从节点</div>
<div>u出发，经过不超过d条边到达节点v的路径有多少种。答案模10^9+7。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n,k。</div>
<div>接下来n行，第i行有2k个整数，前k个整数描述outi，后k个数描述ini。</div>
<div>接下来一行一个整数m。</div>
<div>接下来m行，每行三个整数u,v,d(0&lt;=d&lt;2^31)，描述一组询问。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问，输出一行一个整数，描述答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
2 5 4 3<br/>
7 9 2 4<br/>
0 1 5 2<br/>
6 3 9 2<br/>
2147483647 1000000001 233522788488<br/>
10<br/>
1 1 0<br/>
2 2 1<br/>
2 4 5<br/>
4 3 10<br/>
3 4 50<br/>
1 5 1000</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
51<br/>
170107227<br/>
271772358<br/>
34562176<br/>
890241289</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=N&lt;=1000</div><br/>
<div>1&lt;=K&lt;=20</div><br/>
<div>1&lt;=M&lt;=50</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

