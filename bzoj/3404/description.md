
# Description

<div class="content"><div><span style="font-size: medium">    贝茜和约翰在玩一个数字游戏．贝茜需要你帮助她．</span></div>
<div><span style="font-size: medium">    游戏一共进行了G(1≤G≤100)场．第i场游戏开始于一个正整数Ni(l≤Ni≤1,000,000)．游</span></div>
<div><span style="font-size: medium">戏规则是这样的：双方轮流操作，将当前的数字减去一个数，这个数可以是当前数字的最大数码，也可以是最小的非0数码．比如当前的数是3014，操作者可以减去1变成3013，也可以减去4变成3010．若干次操作之后，这个数字会变成0．这时候不能再操作的一方为输家．    贝茜总是先开始操作．如果贝茜和约翰都足够聪明，执行最好的策略．请你计算最后的赢家．</span></div>
<div><span style="font-size: medium">    比如，一场游戏开始于13.贝茜将13减去3变成10．约翰只能将10减去1变成9．贝茜再将9减去9变成0．最后贝茜赢．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入一个整数G，之后G行一行输入一个Ni．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    对于每一场游戏，若贝茜能赢，则输出一行“YES”，否则输幽一行“NO”</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
9<br/>
10</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
NO</span></div>

# Hint

<div class="content"><p></p><pre><span style="font-size: medium">For the first game, Bessie simply takes the number 9 and wins.<br/>
For the second game, Bessie must take 1 (since she cannot take 0), and then<br/>
FJ can win by taking 9.</span></pre><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

