
# Description

<div class="content"><div>JYY 有一个维护数列的任务。 他希望你能够来帮助他完成。</div>
<div>JYY 现在有一个长度为 N 的序列 a1,a2,…,aN，有如下三种操作：</div>
<div>1、 把数列中的一段数全部乘以一个值；</div>
<div>2、 把数列中的一段数全部加上一个值；</div>
<div>3、 询问序列中的一段数的和。</div>
<div>由于答案可能很大，对于每个询问，你只需要告诉 JYY 这个询问的答案对 P</div>
<div>取模的结果即可。</div></div>

# Input

<div class="content"><div>第一行包含两个正整数， N 和 P；</div>
<div>第二行包含 N 个非负整数，从左到右依次为 a1,a2,…,aN。</div>
<div>第三行有一个整数 M，表示操作总数。</div>
<div>接下来 M 行，每行满足如下三种形式之一：</div>
<div>1、“ 1 t g c”（不含引号）。表示把所有满足 t ≤ i ≤ g 的 ai 全部乘以 c；</div>
<div>2、“ 2 t g c”（不含引号）。表示把所有满足 t ≤ i ≤ g 的 ai 全部加上 c；</div>
<div>3、“ 3 t g”（不含引号）。表示询问满足 t ≤ i ≤ g 的 ai 的和对 P 取模的值。</div>
<div>1 ≤ N,M ≤ 10^5， 1 ≤ P, c, ai ≤ 2*10^9， 1 ≤ t ≤ g ≤ N</div></div>

# Output

<div class="content"><div>对于每个以 3 开头的操作，依次输出一行，包含对应的结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">7 43<br/>
1 2 3 4 5 6 7<br/>
5<br/>
1 2 5 5<br/>
3 2 4<br/>
2 3 7 9<br/>
3 1 3<br/>
3 4 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
35<br/>
8<br/>
【样例说明】<br/>
初始时数列为(1,2,3,4,5,6,7)。<br/>
经过第 1 次操作后，数列为(1,10,15,20,25,6,7)。<br/>
对第 2 次操作，和为 10+15+20=45，模 43 的结果是 2。<br/>
经过第 3 次操作后，数列为(1,10,24,29,34,15,16}<br/>
对第 4 次操作，和为 1+10+24=35，模 43 的结果是 35。<br/>
对第 5 次操作，和为 29+34+15+16=94,模 43 的结果是 8。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round1">Round1</a></p></div>

