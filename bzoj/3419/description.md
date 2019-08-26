
# Description

<div class="content"><p><span style="font-size: medium">Byteasar wants to take a taxi from the town Bytehole to the town Bytepit, which is m kilometres away from Bytehole. Exactly dkilometres along the way from Bytehole to Bytepit, there is a base of n taxis, numbered from   to n. The taxi no. i has enough fuel to drive exactly Xi kilometres.<br/>
Byteasar can change taxis at any point. All the taxis start at their base but need not return there. Your task is to determine whether Byteasar can be driven from Bytehole to Bytepit, and if so, what it the minimum number of taxis required for such a journey.<br/>
</span></p>
<p><span style="font-size: medium"><span>杭州是一个风景优美的城市，但是这里的出租车不太好打……</span></span></p>
<pre><span style="font-size: medium">然后叫来第2辆车，第二辆车的路径为23-&gt;27-&gt;42，
小F成功回家<br/>小F现在在西湖边的雷峰塔，他想打出租车回家 
但是现在出租车都在换班……不愿意开太远(什么破理由) 
我们可以把雷峰塔到小F的家的路径抽象成一条线段，
这条线段长为m 而在线段上恰好有杭州最大的一个出租车
停车处,它到雷峰塔的距离为d 现在小F知道杭州所有的
出租车都在那个停车处那里，停车处那里有n辆车 现在由
于出租车都在换班……它们都不愿意开太远…… 第i辆车
能开的最远路程是x[i](注意是路程不是位移) 注意所有
车都是从停车处出发的 小F坐上车之后可以随时下车，
小F也能随时呼叫来一辆停在停车处的车 注意一辆车
只能被呼叫来一次 倒霉的小F现在想回家……你能帮他么…… 
因为他逛西湖已经走不动路了，所以他回家全程必须得做出租车，
不然他浑身难受 每叫一辆出租车小F就要付1块钱…… 
因为小F不是土豪……所以如果有打车方案能送他回家的话，
你得给他一个花钱最少的方案…… 如果小F不能打车回家的话……
请给他一个0让他开心一下——至少他不用花钱了 
Input 
第一行三个正整数：m,d,n 
第二行n个正整数：第i个整数表示xi
 Output 
如果能回去，输出最小的花费 
否则输出0 
Sample Input 
42 23 6 20 25 14 27 30 7 
Sample Output 
4 
Hint 
样例解释： 我们用数字表示一个位置的坐标，例如样例里停
车处坐标为23，雷峰塔坐标为0 一个最优打车方案是这样的： 
小F先叫来第4辆车，第4辆车的路径为：23-&gt;0-&gt;4，小F由此
到达了4 然后叫来第5辆车，第5辆的路径为：23-&gt;4-&gt;15，小
F由此到达了15 然后叫来第1辆车，第1辆车的路径为23-&gt;15-&gt;27，
小F到达了27 </span></pre>
<p></p></div>

# Input

<div class="content"><p><font size="4">The first line of the standard input holds three integers,m,d and n (1&lt;=d&lt;=10^18,1&lt;=N&lt;=500000), separated by single spaces. Those denote, respectively: the distance from Bytehole to Bytepit, the distance from Bytehole to the taxi base, and the number of taxis at the base. The second line of input contains n integers, x1,x2…Xn (1&lt;=Xi&lt;=10^18), separated by single spaces. The number Xi denotes the maximum distance (in kilometres) that the i-th taxi can travel.<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">Your program should print a single integer to the standard output: the minimum number of taxis Byteasar has to take to get from Bytehole to Bytepit. If getting there is impossible, your program should print the number 0.<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">42 23 6<br/>
20 25 14 27 30 7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
Explanation of the example: Byteasar can take the taxis no. 4, 5, 1, and 2, in this order.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Wcmg提供译文">鸣谢Wcmg提供译文</a></p></div>

