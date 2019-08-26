
# Description

<div class="content"><div>
<div><span style="font-size: medium">在一片m*m的地上．驻扎着n个军队,编号依次为1~n,第i个军队的位置可用二元组(xi,yi)表示，可能有多个军队驻扎在同一个位置。</span></div>
<div><span style="font-size: medium">接下来有t个时刻，每个时刻会发生下列两种事件之一：</span></div>
<div><span style="font-size: medium">(1)第x个军队向一个方向（向上(U)向下(D)向左(L)向右(R)）移动了d个单位：</span></div>
<div><span style="font-size: medium">(2)第x个军队需要集结和它在同一行或同一列的且编号在[l,r]的军队，也就是说，这些军队需要赶到第x个军队的驻地。</span></div>
<div><span style="font-size: medium">定义第i个军队赶到第j个军队所需的花费为cost(i,j)=(xi-xj)^2+(yi-yj)^2</span></div>
<div><span style="font-size: medium">请你输出每次集结时，所有被集结的军队的花费之和，对10^9+7取模。</span></div>
</div></div>

# Input

<div class="content"><p><font size="4">  第一行，两个数n和M。<br/>
  描下来r一行，每行两个数xi,yi<br/>
  下一行，一个数t。<br/>
  描下来t行，每行的格式为下列两种格式之一<br/>
  (l)S x d,其中S∈{U,L,D,R}，代表第一种事：<br/>
  (2)Q x L R，代表第二种事件。<br/>
  为了体现在线询问,每次你读进x&#39;后，真正的x=x&#39; xor lastans,其中lastans是上一次答案对10^9+7取模后的结果，一开始lastans=0</font></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
对于每一个Q事件，输出一个答案，对10^9+7取模</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入】<br/>
5 3<br/>
1 2<br/>
2 2<br/>
3 2<br/>
2 1<br/>
2 3<br/>
7<br/>
Q 2 1 5<br/>
Q 6 3 4<br/>
D 1 1<br/>
Q 0 1 5<br/>
Q 7 1 5<br/>
L 5 1<br/>
Q 4 1 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
2<br/>
3<br/>
6<br/>
4<br/>
【样例解释】<br/>
解密后的输入：<br/>
Q 2 1 5<br/>
Q 2 3 4<br/>
D 3 1<br/>
Q 2 1 5<br/>
Q 4 1 5<br/>
L 3 1<br/>
Q 2 1 5<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img alt="" width="637" height="168" src="source/bzoj/3542/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNC9hYSgxKS5qcGc=.jpg"/></p><br/>
<p><span style="font-size: medium">样例还看不懂就看下图</span></p><br/>
<p><span style="font-size: medium"><br/><br/>
</span><span style="font-size: medium">【数据范围】<br/><br/>
n≤100000，m≤10^18。保证军队在移动过程中不会超出边界。<br/><br/>
每个军队集结后会回到原来的驻地</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Dzy">By Dzy</a></p></div>

