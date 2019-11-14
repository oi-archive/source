
# Description

<div class="content"><div>Karin在战斗之余的闲暇时光里喜欢上B站看鬼畜视频，尤其喜欢发弹幕。她这天对一个视频的弹幕产生了兴趣，她记录了每个时间点的弹幕数量，并且可能对一段呈等差数列的时间的弹幕数量求最大值；她还可能修改某个时间点的弹幕数量。</div>
<div>为了不在Yuuna面前暴露出她弱爆了的数学能力，保持她傲娇的属性，你需要帮助她。</div>
<div>精简题意：给定一个序列，支持以下操作：①对一段下标是等差数列的子序列进行求最大值操作(参见输入格式)；②单点修改。</div>
<p></p></div>

# Input

<div class="content"><div>第一行是一个整数n，</div>
<div>第二行是一个长度为n的整数序列a1...an，</div>
<div>第三行是一个整数m，</div>
<div>接下来m行，每行首先有一个整数op，</div>
<div>然后，若op=0，则之后有两个整数p，v，代表将a[p]的值加上v，</div>
<div>若op=1，则之后有两个整数x0，d，代表询问max{a[x0],a[x0+d],a[x0+2d],...,a[x0+kd]}(x0+kd&lt;=n,x0+(k+1)d&gt;n)。</div>
<div>数据中可能有多余空格。</div>
<p></p></div>

# Output

<div class="content"><div>
<div>对每个op=1，单独输出一行，代表该等差子序列的最大值。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例1】<br/>
10<br/>
1 6 1 4 9 4 8 2 8 5<br/>
10<br/>
1 3 3<br/>
0 5 4<br/>
0 3 8<br/>
1 2 5<br/>
1 4 8<br/>
1 7 5<br/>
1 3 6<br/>
0 1 2<br/>
1 5 3<br/>
1 4 9<br/>
<br/>
【输入样例2】<br/>
10<br/>
-9 -6 2 -10 -2 -6 10 6 -4 -2<br/>
10<br/>
1 2 3<br/>
1 6 3<br/>
0 7 8<br/>
0 4 -6<br/>
0 10 -5<br/>
1 10 4<br/>
0 3 -8<br/>
1 2 4<br/>
0 10 -5<br/>
1 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例1】<br/>
8<br/>
8<br/>
4<br/>
8<br/>
9<br/>
13<br/>
4<br/>
<br/>
【输出样例2】<br/>
6<br/>
-4<br/>
-7<br/>
-6<br/>
18</span></div>

# Hint

<div class="content"><p></p><div>【数据范围】</div><br/>
<div>1&lt;=n&lt;=70000，</div><br/>
<div>1&lt;=m&lt;=70000，</div><br/>
<div>保证任何时刻abs(a[i])(1&lt;=i&lt;=n)&lt;=2147483647，</div><br/>
<div>0&lt;=op&lt;=1，</div><br/>
<div>1&lt;=p&lt;=n，</div><br/>
<div>abs(v)&lt;=2147483647</div><br/>
<div>1&lt;=x0&lt;=n,</div><br/>
<div>1&lt;=d&lt;=n，</div><br/>
<div>保证涉及的所有数在C++的int内。</div><br/>
<div>2015.4.2新加四组数据</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

