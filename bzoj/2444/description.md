
# Description

<div class="content"><p><span style="font-size: medium"><br/>
奶牛们正在玩电线！他们学会了焊接：把两条电线连接起来，将某条的端点焊接到<br/>
另一条的中间某个位置(注意：不能够将两条电线的端点焊接起来，即中间某个位置<br/>
不包括端点)。当然，中间的同一个位置可以焊接多条电线。(并且焊接点必须为整数点，<br/>
这个好像英文题面没说，我是这么理解的)<br/>
<br/>
奶牛们准备建造一个神奇的结构。它是一个N(1 &lt;= N &lt;= 50,000)个节点N-1条边的图，<br/>
并且任意两个节点连通。每条边通过两个整数A,B来表示(1 &lt;= A &lt;=N; 1 &lt;= B &lt;= N; A != B)。<br/>
<br/>
奶牛们要从当地的店里买电线，然而，越长的电线就越贵，具体地：一条长度为L的电线<br/>
的售价为L*L，并且，电线是不允许连接或者裁断的。<br/>
<br/>
给出奶牛准备建造的结构，请帮助奶牛们找出最小的花费。<br/>
</span></p></div>

# Input

<div class="content"><p><br/>
* 第一行: 一个整数 N<br/>
<br/>
* 第二到N行: 每行两个整数A,B描述一条边<br/>
<br/>
</p></div>

# Output

<div class="content"><p><br/>
* 第一行：一个整数表示最小的花费，注意这个整数可能超过32位二进制数。<br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 2<br/>
1 3<br/>
1 4<br/>
1 5<br/>
1 6<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
由于每个节点都和1号节点相连，因此，我们只要购买1条长度为2的电线和3条长度为1的电线即可。<br/>
总的花费为2 * 2 +1 * 1 + 1 * 1 + 1 * 1 = 7。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

