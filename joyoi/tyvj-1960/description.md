# 

 
 # 题目背景 
（Freda终于到了Rainbow的城堡）<BR>Rainbow：玩些什么呢lala~？<BR>Freda：唔，我想先试试你电脑的配置。<BR>Rainbow：啊嘞？怎么试呀&gt;_&lt;？<BR>Freda：哈哈~文明5这个游戏就够了lala~<BR>Rainbow：=&nbsp;=||| 

 
 # 题目描述 
题目叙述<BR>&nbsp;Freda很喜欢玩《文明》，因此它知道很多游戏的攻略。有一个攻略根据城市的N&nbsp;种资源的数量，对地图上许多位置的城市都计算了一个价值分数并给出了如下公式：<BR>一座城市的价值分数=资源1的数量*资源1的价值+资源2&nbsp;的数量*资源2的价值+资源3的数量*资源3的价值+……+资	源N&nbsp;的数量*资源N&nbsp;的价值。<BR>然而，Rainbow却是首次接触这个游戏。所以它非常好奇每种资源的价值是如何得出的，于是它找了N&nbsp;座城市，并获得了这N座城市每座城市N&nbsp;种资源的数量信息。由于数据量实在很大，因此Rainbow把这些数据给了你。它希望你能帮它算出，每种资源的价值是多少，这样它就能够自己计算出其它城市的价值分数了。 

 
 # 输入格式 
输入格式<BR>	输入文件第1&nbsp;行包含一个整数N，含义如题所述。<BR>	第2&nbsp;行到第N+1&nbsp;行，每行N+1&nbsp;个正整数。第i+1&nbsp;行的第j(j&lt;=N)个整数表示第i&nbsp;个城市含有资源j的数量，第N+1个整数表示这个城市的价值分数。 

 
 # 输出格式 
输出格式<BR>&nbsp;&nbsp;&nbsp;输出N行，每行一个整数，第i行的整数表示第i种资源的价值。&nbsp; 

 
 # 提示 
数据范围与约定<BR>对于40%的数据，N&lt;=10，每种资源的价值在[0,10^9]之间，资源的数量在[0,128]之间；<BR>对于70%的数据，N&lt;=100；<BR>对于100%的数据，N&lt;=200，每种资源的价值在[0,10^18]之间，资源的数量在[0,10^9]<BR>之间，保证有唯一解，保证答案一定为自然数。From&nbsp;-&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<BR>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>输入样例
1
1 1</td><td>输出样例
1</td></tr></table>
