
# Description

<div class="content"><p><span style="font-size: medium">方伯伯正在做他的Oj。现在他在处理Oj上的用户排名问题。<br/>
Oj上注册了n个用户，编号为1～”，一开始他们按照编号排名。方伯伯会按照心情对这些用户做以下四种操作，修改用户的排名和编号：<br/>
1．操作格式为1 x y，意味着将编号为z的用户编号改为V，而排名不变，执行完该操作后需要输出该用户在队列中的位置，数据保证x必然出现在队列中，同时1，是一个当前不在排名中的编号。<br/>
2．操作格式为2 x，意味着将编号为x的用户的排名提升到第一位，执行完该操作后需要输出执行该操作前编号为z用户的排名。<br/>
3．操作格式为3 x，意味着将编号为z的用户的排名降到最后一位，执行完该操作后需要输出执行该操作前编号为z用户的排名。<br/>
4．操作格式为4 k，意味着查询当前排名为足的用户编号，执行完该操作后需要输出当前操作用户的编号。<br/>
但同时为了防止别人监听自己的工作，方伯伯对他的操作进行了加密，即将四种操作的格式分别改为了：<br/>
1 x+a y+a<br/>
2 x+a<br/>
3 x+a<br/>
4 k+a<br/>
其中a为上一次操作得到的输出，一开始a=0。<br/>
例如：<br/>
上一次操作得到的输出是5<br/>
这一次操作的输入为：1  13 15<br/>
因为这个输入是经过加密后的，所以你应该处理的操作是1 8 10<br/>
现在你截获丁方伯伯的所有操作，希望你能给出结果。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">输入的第1行包含2个用空格分隔的整数n和m，表示初始用户数和操作数。<br/>
此后有m行，每行是一个询问，询问格式如上所示。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出包含m行。每行包含一个整数，其中第i行的整数表示第i个操作的输出。</font></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10                     <br/>
1 2 11                     <br/>
3 13                       <br/>
25                        <br/>
37                         <br/>
28                        <br/>
2 10                       <br/>
2 11                       <br/>
3 14                       <br/>
2 18                      <br/>
4 9  </span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
2<br/>
4<br/>
3<br/>
5<br/>
5<br/>
7<br/>
8<br/>
11</span></div>

# Hint

<div class="content"><p></p><div>对于 100% 的数据，1 ≤ n ≤ 10^8，1 ≤ m ≤ 10^5</div><br/>
<div>输入保证对于所有的操作 1，2，3，x 必然已经出现在队列中，同时对于所有操作 1，1 ≤ y ≤ 2 × 10^8，并且</div><br/>
<div>y 没有出现在队列中。</div><br/>
<div>对于所有操作 4，保证 1 ≤ k ≤ n。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

