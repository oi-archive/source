
# Description

<div class="content"><p><span style="font-size: medium; ">Little Edna has received the take-out game as a present. Take-out is a single player game, in which the player is given a sequence of  adjacent blocks, numbered from 1 to n. Each block is either black or white, and there are k times as many white blocks as there are black ones.<br/>
The player&#39;s goal is to remove all the blocks by certain permissible moves.<br/>
A single move consists in removing exactly k white blocks and a single black block without changing the positions of other blocks. The move is permissible if there is no &#34;gap&#34; (a space left by a previously taken out block) between any two blocks being removed.<br/>
Help poor little Edna in finding any sequence of permissible moves that remove all the blocks.<br/>
</span></p>
<p><span style="font-size: medium; "> </span></p>
<p><span style="font-size: medium; "><span style="white-space: pre-wrap; ">小F喜欢玩一个消除游戏——take-out</span></span></p>
<pre style="white-space: pre-wrap; "><span style="font-size: medium; ">保证k+1|n，保证输入数据有解<br/>这是一个单人游戏 游戏者的目标是消除初始时给定的一列砖块，从左往右标号为1到n，若两个砖块标号相差1，则它们相邻 每一块砖块要么是黑的，要么是白的，这列砖块里面白砖块的数量是黑砖块的数量的k倍 游戏者可以通过执行移除操作来消除砖块 一步移除操作会将k个白砖块和1个黑砖块从序列中移除，而这些被移除的砖块原来所在的位置用透明砖块所代替，其它砖块的位置不变 一个移除操作是合法的当且仅当： 在这次移除中，任意两个被移除的砖块之间，没有透明砖块，且恰好移走k个白砖块和1个黑砖块 显然一个砖块不能被移除两次 小F的智商不够……他对着面前密密麻麻的砖块看傻了眼…… 你能帮他玩通关么? Input 第一行两个数:n,k，意义同题目描述 接下来一行一个由&#39;b&#39;和&#39;c&#39;组成的字符串，长度为n，描述这列砖块 第i个砖块如果是黑色的，那么第i个字符为&#39;c&#39; 否则是白色的，第i个字符为&#39;b&#39; (注:波兰文中b是bialy的首字母,c是czarny的首字母) Output 输出n/(k+1)行，每行k+1个数，用空格分开，要求递增 第i行表示第i次移除操作移除砖块的位置集合 Sample Input 12 2 ccbcbbbbbbcb Sample Output 10 11 12  1 8 9  2 6 7  3 4 5  HINT 2&lt;=n&lt;=1000000,1&lt;=k&lt;n </span></pre>
<p></p></div>

# Input

<div class="content"><p><font size="4">In the first line of the standard input there are two integers, n and k (2&lt;=N&lt;=1000000,1&lt;=K&lt;=N-1), separated by a single space, that denote the total number of blocks used in the game, and the number of white blocks per black node (to be removed in every move). In all the tests the condition k+1|N holds.<br/>
In the second line there is a string of n letters b or c. These tell the colours of successive blocks (in Polish): b (for biały) - white, c(for czarny) - black. You may assume that in all the tests there exists a sequence of permissible moves that takes out all the blocks.<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">Your program should print n/(k+1) lines to the standard output. Successive lines should describe successive moves. Each line should contain K+1 integers, in increasing order, separated by single spaces, that denote the numbers of blocks to be removed in the move.<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 2<br/>
ccbcbbbbbbcb<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10 11 12 <br/>
1 8 9 <br/>
2 6 7 <br/>
3 4 5 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Wcmg提供SPJ 译文">鸣谢Wcmg提供SPJ 译文</a></p></div>

