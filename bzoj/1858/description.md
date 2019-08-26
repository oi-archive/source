
# Description

<div class="content"><p>lxhgww最近收到了一个01序列，序列里面包含了n个数，这些数要么是0，要么是1，现在对于这个序列有五种变换操作和询问操作： 0 a b 把[a, b]区间内的所有数全变成0 1 a b 把[a, b]区间内的所有数全变成1 2 a b 把[a,b]区间内的所有数全部取反，也就是说把所有的0变成1，把所有的1变成0 3 a b 询问[a, b]区间内总共有多少个1 4 a b 询问[a, b]区间内最多有多少个连续的1 对于每一种询问操作，lxhgww都需要给出回答，聪明的程序员们，你们能帮助他吗？</p></div>

# Input

<div class="content"><p>输入数据第一行包括2个数，n和m，分别表示序列的长度和操作数目    第二行包括n个数，表示序列的初始状态    接下来m行，每行3个数，op, a, b，（0 &lt; = op &lt; = 4，0 &lt; = a &lt; = b）</p></div>

# Output

<div class="content"><p>对于每一个询问操作，输出一行，包括1个数，表示其对应的答案</p></div>

# Sample Input

<div class="content"><span class="sampledata">   10 10<br/>
   0 0 0 1 1 0 1 0 1 1<br/>
   1 0 2<br/>
   3 0 5<br/>
   2 2 2<br/>
   4 0 4<br/>
   0 3 6<br/>
   2 3 7<br/>
   4 2 8<br/>
   1 0 5<br/>
   0 5 6<br/>
   3 3 9<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">   5<br/>
   2<br/>
   6<br/>
   5<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于30%的数据，1&lt;=n, m&lt;=1000    对于100%的数据，1&lt; = n, m &lt; = 100000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

