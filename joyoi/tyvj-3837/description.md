# 

 
 # 题目描述 
<p style="line-height: 20.7999992370605px;">鉴于sideman和yxcregneva在applepi乘坐电梯的时候，把电梯外每一层的按键都按了一次，于是applepi把他俩关到了另一个特质的电梯里。</p>

<p style="line-height: 20.7999992370605px;">这部电梯里有四个按键：上升a层、上升b层、上升c层、返回第1层。电梯最高到达h层，最低到达1层。如果按下某个按键后电梯接收到了一个到达高于h层的指令，电梯将不会移动。电梯最初在1层。</p>

<p style="line-height: 20.7999992370605px;">&ldquo;你们只有通过这四个按键在所有可能到达的楼层停留至少一次，电梯门才会解锁放你们出去。这次让你们玩个够，嘿嘿，呵呵呵呵，哈哈哈哈哈哈哈哈&hellip;&hellip;&rdquo;</p>

<p style="line-height: 20.7999992370605px;">听着applepi的声音渐行渐远，sideman和yxcregneva并没有惊慌，反而自顾自地玩弄起了这部电梯！不过他们想知道的是：在1~h层中到底有多少层是是可能到达的呢？</p> 

 
 # 输入格式 
<p>第一行一个整数h。</p>

<p>第二行三个整数a、b、c。</p> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-size: medium; line-height: 19.2000007629395px; text-align: justify; text-indent: 28px; font-family: 宋体;">一个整数，</span><span style="color: rgb(0, 0, 0); font-size: medium; line-height: 19.2000007629395px; text-align: justify; text-indent: 28px; font-family: 宋体;">表示可能</span><span style="color: rgb(0, 0, 0); font-size: medium; line-height: 19.2000007629395px; text-align: justify; text-indent: 28px; font-family: 宋体;">到达</span><span style="color: rgb(0, 0, 0); font-size: medium; line-height: 19.2000007629395px; text-align: justify; text-indent: 28px; font-family: 宋体;">的楼层数量。</span></p> 

 
 # 提示 
<p>对于20%的数据，1&lt;=h&lt;=1000000。</p>

<p>对于100%的数据，1&lt;=a,b,c&lt;=100000，1&lt;=h&lt;=10^18，a,b,c&lt;=h。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>15
4 7 9
</td><td>9
</td></tr></table>
