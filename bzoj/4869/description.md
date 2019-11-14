
# Description

<div class="content"><div>Informatikverbindetdichundmich.</div>
<div>信息将你我连结。B君希望以维护一个长度为n的数组，这个数组的下标为从1到n的正整数。一共有m个操作，可以</div>
<div>分为两种：0 l r表示将第l个到第r个数（al,al+1,...,ar）中的每一个数ai替换为c^ai，即c的ai次方，其中c是</div>
<div>输入的一个常数，也就是执行赋值ai=c^ai1 l r求第l个到第r个数的和，也就是输出：sigma(ai),l&lt;=i&lt;=rai因为</div>
<div>这个结果可能会很大，所以你只需要输出结果mod p的值即可。</div>
<div></div></div>

# Input

<div class="content"><div>第一行有三个整数n,m,p,c，所有整数含义见问题描述。</div>
<div>接下来一行n个整数，表示a数组的初始值。</div>
<div>接下来m行，每行三个整数，其中第一个整数表示了操作的类型。</div>
<div>如果是0的话，表示这是一个修改操作，操作的参数为l,r。</div>
<div>如果是1的话，表示这是一个询问操作，操作的参数为l,r。</div>
<div>1 ≤ n ≤ 50000, 1 ≤ m ≤ 50000, 1 ≤ p ≤ 100000000, 0 &lt; c &lt;p, 0 ≤ ai &lt; p</div>
<div></div></div>

# Output

<div class="content"><div>对于每个询问操作，输出一行，包括一个整数表示答案mod p的值。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 7 2<br/>
1 2 3 4<br/>
0 1 4<br/>
1 2 4<br/>
0 1 4<br/>
1 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 <br/>
3</span></div>

# Hint

<div class="content"><p></p><p> 鸣谢多名网友提供正确数据，已重测！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=黑吉辽沪冀晋六省联考&amp;&amp;鸣谢xlk授权本OJ使用权">黑吉辽沪冀晋六省联考&amp;&amp;鸣谢xlk授权本OJ使用权</a></p></div>

