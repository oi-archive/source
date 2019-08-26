
# Description

<div class="content"><p><span style="font-size: medium">Farmer John尝试通过和奶牛们玩益智玩具来保持他的奶牛们思维敏捷. 其中一个大型玩具是牛栏中的灯. N (2 &lt;= N &lt;= 100,000) 头奶牛中的每一头被连续的编号为1..N, 站在一个彩色的灯下面.刚到傍晚的时候, 所有的灯都是关闭的. 奶牛们通过N个按钮来控制灯的开关; 按第i个按钮可以改变第i个灯的状态.奶牛们执行M (1 &lt;= M &lt;= 100,000)条指令, 每个指令都是两个整数中的一个(0 &lt;= 指令号 &lt;= 1). 第1种指令(用0表示)包含两个数字S_i和E_i (1 &lt;= S_i &lt;= E_i &lt;= N), 它们表示起始开关和终止开关. 奶牛们只需要把从S_i到E_i之间的按钮都按一次, 就可以完成这个指令. 第2种指令(用1表示)同样包含两个数字S_i和E_i (1 &lt;= S_i &lt;= E_i &lt;= N), 不过这种指令是询问从S_i到E_i之间的灯有多少是亮着的. 帮助FJ确保他的奶牛们可以得到正确的答案. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第 1 行: 用空格隔开的两个整数N和M</span></p>
<p><span style="font-size: medium"> * 第 2..M+1 行: 每行表示一个操作, 有三个用空格分开的整数: 指令号, S_i 和 E_i </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第 1..询问的次数 行: 对于每一次询问, 输出询问的结果. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
0 1 2<br/>
0 2 4<br/>
1 2 3<br/>
0 2 4<br/>
1 1 4<br/>
<br/>
输入解释:<br/>
一共有4盏灯; 5个指令. 下面是执行的情况:<br/>
	        灯<br/>
            1 2 3 4<br/>
  Init:     O O O O   O = 关  * = 开<br/>
  0 1 2 -&gt;  * * O O  改变灯 1 和 2 的状态<br/>
  0 2 4 -&gt;  * O * *<br/>
  1 2 3 -&gt;  1        输出在2..3的范围内有多少灯是亮的<br/>
  0 2 4 -&gt;  * * O O  改变灯 2 ,3 和 4 的状态<br/>
  1 1 4 -&gt;  2        输出在1..4的范围内有多少灯是亮的<br/>
<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

