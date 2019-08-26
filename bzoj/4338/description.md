
# Description

<div class="content"><div>Alice 正在教她的弟弟 Bob 学数学。 </div>
<div>每天，Alice 画一个N行M 列的表格，要求 Bob在格子里填数。 </div>
<div>Bob已经学会了自然数1到K的写法。因此他在每个格子里填1 ~ K之间的整数。 </div>
<div>Alice 告诉 Bob，如果 Bob 填写完表格的 N*M 个数以后，每行的数从第 1 列到第 M</div>
<div>列单调不减，并且任意两行至少有一列的数不同，而且以前 Bob 没有填写过相同的表格，</div>
<div>那么Alice 就给Bob吃一颗糖果。 </div>
<div>Bob想知道，如果每天填写一遍表格，最多能吃到多少颗糖果。 </div>
<div>答案模P输出。 </div>
<p></p></div>

# Input

<div class="content"><div>第一行，四个整数依次是N, M, K, P。 </div>
<p></p></div>

# Output

<div class="content"><div>输出一行，一个整数，表示答案模P 后的结果。 </div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】 <br/>
1 3 3 10 <br/>
 【样例输入2】 <br/>
2 2 2 10 </span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】 <br/>
0 <br/>
【样例输出2】 <br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><div>【样例解释】 </div><br/>
<div>样例1。表格只有一行。每个格子可以填写1 ~ 3。有10种填写方法，依次为1 1 1，</div><br/>
<div>1 1 2，1 1 3，1 2 2，1 2 3，1 3 3，2 2 2，2 2 3，2 3 3，3 3 3。   </div><br/>
<div>样例2。表格有两行。有6 种填写方法，依次为  1 1/1 2, 1 1/2 2, 1 2/1 1, 1 2/2 </div><br/>
<div>2, 2 2/1 1, 2 2/1 2。 </div><br/>
<div> </div><br/>
<div>【数据规模与约定】 </div><br/>
<div>100% 的数据中，1 ≤ N, M ≤ 10^5，1 ≤ P, K ≤ 2*10^9. </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

