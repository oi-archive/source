# 题目描述


<h3>
【题目描述】
</h3>
<p>
你偶尔和朋友玩如下的游戏。你的朋友写下一个由01组成的序列。你选择连续的一段子序列（例如，从第3到第5个数的子序列），问他这一段中1的个数是偶数还是奇数。你的朋友会回答你的问题，然后你可以问他另外一段子序列，等等。你的任务是猜出整个序列。
</p>
<p>
你怀疑你朋友的一些回答可能是错误的，并且你希望证明他说了假话。因此你决定写一个程序来帮助你。这个程序将会收到你的一系列问题以及你朋友给出的答案。程序的目标是找到第一个被证明是错误的回答，即，存在一个序列能满足之前所有回答，但加上这个回答后就不存在相应的序列。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有一个整数，代表01序列的长度。长度不超过1000000000。
</p>
<p>
第二行有一个正整数，代表询问和回答的数量。数量不超过5000.
</p>
<p>
接下来的若干行描述了所有的了询问和回答。每一行包含了一个询问和对此询问的回答：两个整数（所选择的子序列的起止点），一个单词“even”或“odd”（答案，即该子序列中1的个数的奇偶性），其中“even”代表有偶数个，“odd”代表有奇数个。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个整数X。它意味着：存在一个01序列满足前X个奇偶性询问，但不存在满足前X+1个奇偶性询问的序列。如果存在满足所有询问的序列，X就应该是询问的总数。
</p>
<h3>
【样例输入】
</h3>
<h4>
<span style="color:inherit;line-height:20px;font-family:inherit;font-size:17.5px;background-color:white;">输入样例1：</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">10</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">5</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">1 2 even</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">3 4 odd</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">5 6 even</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">1 6 even</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">7 10 odd</span>
</h4>
<p>
<br/>
</p>
<h4>
<span style="color:inherit;font-family:inherit;font-size:17.5px;">输入样例2：</span> 
</h4>
<h4>
<span style="color:inherit;font-family:inherit;font-size:16px;font-weight:normal;">10</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">5</span> 
</h4>
<h4>
<span style="color:inherit;font-size:16px;font-weight:normal;">1 2 even</span> 
</h4>
<h4>
<span style="font-size:16px;font-weight:normal;">1 4 even</span> 
</h4>
<h4>
<span style="font-size:16px;font-weight:normal;">2 4 odd</span> 
</h4>
<h4>
<span style="font-size:16px;font-weight:normal;">1 10 even</span> 
</h4>
<h4>
<span style="font-size:16px;font-weight:normal;">3 10 even</span> 
</h4>
<h4>
<span style="font-size:16px;font-weight:normal;">1 2 even</span> 
</h4>
<h4>
</h4>
<h3>
【样例输出】
</h3>
<h4>
输出样例1：
</h4>
<h4>
<span style="font-size:16px;font-weight:normal;">3</span>
</h4>
<h4>
输出样例2：
</h4>
<h4>
<span style="font-size:16px;font-weight:normal;">5</span> 
</h4>
<h3>
【来源】
</h3>
<p>
CEOI 1999 Parity game
</p>
