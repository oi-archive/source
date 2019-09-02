# 题目描述


<div>
<b>USACO Contest Feb2012 Bronze</b> 
</div>
<div>
<b>Problem 3. Moo  Moo游戏</b> 
</div>
<div>
<i>Translated by Freddy</i> 
</div>
<div>
奶牛们迷上了一个名为“Moo”的新的单词游戏。
</div>
<div>
在玩该游戏时，奶牛们站成长长的一排，在队列中的每一头
</div>
<div>
奶牛都有责任尽可能快的大声说出一个特定的字母。
</div>
<div>
 
</div>
<div>
在Moo游戏中，这个单词序列严格上说是无穷的，它是这样开始的：
</div>
<div>
m o o m o o o m o o m o o o o m o o m o o o m o o m o o o o o
</div>
<div>
 
</div>
<div>
这一串最好由递归表示：令S(0)为三个字符的序列“moo”
</div>
<div>
那么更长的字符串S(k)由三部分组成，第一部分是S(k-1)，第二部分是”m o…o”(k+2个’o&#39;)，第三部分又是S(k-1)。例如：
</div>
<div>
S(0)=”m o o”
</div>
<div>
S(1)=”m o o m o o o m o o”
</div>
<div>
S(2)=”m o o m o o o m o o m o o o o m o o m o o o m o o”
</div>
<div>
 
</div>
<div>
正如你所看到的，这个过程最终将会产生一个无穷的长字符串，并且
</div>
<div>
这个长字符串正是被玩Moo游戏的奶牛一个一个说出。
</div>
<div>
 
</div>
<div>
Bessie这头奶牛，自我感觉很聪明，他想要预测第N头奶牛将会说出m还是o。请你帮助他！
</div>
<div>
 
</div>
<div>
输入：
</div>
<div>
一个正整数N(N&lt;=10^9)
</div>
<div>
输出 :
</div>
<div>
输出文件只有一行，包含一个字符，“o”或者“m”
</div>
<div>
 
</div>
<div>
输入样例：
</div>
<div>
11
</div>
<div>
输出样例：
</div>
<div>
m
</div>
