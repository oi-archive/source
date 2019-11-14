
# Description

<div class="content"><div>在经历过1e9次大型战争后的宇宙中现在还剩下n个完美维度，</div>
<div>现在来自多元宇宙的膜法师，想偷取其中的三个维度为伟大的长者续秒，</div>
<div>显然，他能为长者所续的时间，为这三个维度上能量的乘积，</div>
<div>但目前的宇宙很不乐观，胡乱偷取可能造成维度的崩溃，</div>
<div>所以，他必须按逆序偷取这些维度，且在偷取中，</div>
<div>每次偷取的维度的能量必须严格小于他上次偷取的能量，</div>
<div>由于膜法师生活在多元宇宙，所以他可以让所有可能的偷取方案全部发生</div>
<div>题目描述</div>
<div>但他数学不好，所以找到了你帮他求出能为长者续几秒，</div>
<div>你要做的，就是在给定的维度序列a中，</div>
<div>求出所有满足i&lt;j&lt;k且ai&lt;aj&lt;ak的ai*aj*ak的和</div>
<div>即 ∑ (a_i*a_j*a_k)，要求  i&lt;j&lt;k  且 a_i&lt;a_j&lt;a_k</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行1个数 n</div>
<div>第二行n个数 a_i</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一个数，表示能为长者续几秒，由于长者是不朽的，</div>
<div>所以能活很久，不妨将答案对**19260817**取模吧</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例1<br/>
4<br/>
1 2 3 4<br/>
<br/>
样例二<br/>
10<br/>
6 8 4 1 3 0 7 5 9 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1<br/>
50<br/>
样例输出2<br/>
1737<br/>
样例解释<br/>
对于样例 1<br/>
有满足条件的序列为<br/>
{1，2，3}——6<br/>
{1，2，4}——8<br/>
{1，3，4}——12<br/>
{2，3，4}——24<br/>
ans=6+8+12+24=50<br/>
数据范围<br/>
30%的数据n&lt;=300<br/>
60%的数据n&lt;=3000<br/>
100%的数据n&lt;=300000<br/>
0&lt;=a[i]&lt;=2147483647</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By szwujq">By szwujq</a></p></div>

