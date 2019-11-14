# 

 
 # 题目背景 
NOIp2012考后欢乐赛第三题 

 
 # 题目描述 
　　服务器的新防御系统快要建好了，但是当正在数据库升级的时候，突然有黑客入侵机房网络，但是就在那时，插网线的房间钥匙丢了。所以Admin开始做防御机房的工作。<br>　　不过，由于访问某台电脑可经过其他电脑加速，但是不能访问途经电脑，而且单位时间内一台电脑只能发出一条指令，指令不含嵌套指令，Admin只能一台一台的建立防御，幸好如此，黑客也是一台一台入侵，不过二人都会选择最优方案进行操作。所以Admin在主控端(教师端)不停的巡察各台电脑的同时，要求你在简短的时间内帮Admin计算一下哪些电脑将必然被入侵成功，以便于Admin及时做出额外的保护措施，如果所有可能被入侵的电脑都能被保护，那么请计算出将所有连接在主控端上的电脑做好防御所需的总时间。<br>　　注意：只有黑客的入侵时间短于Admin的防御时间，黑客才能成功入侵。 

 
 # 输入格式 
第一行为两个正整数N，M，表示有N台电脑，M条网线。(黑客近似地看为第N台电脑，在机房外)<br>第二行为N-2个正整数，表示每台电脑的访问时间t。<br>第三行到第&nbsp;M+2&nbsp;行，每行三个整数u,v,w，表示电脑u和v之间有一条网线，使用该网线互相到达对方电脑需要w个单位时间。 

 
 # 输出格式 
输出共两行。<br>如果有可能会防御失败的电脑，第一行输出"No"，第二行升序输出这些电脑的编号(空格隔开)。<br>否则第一行输出"Yes"，第二行输出将所有连接在主服务器上的电脑做好防御所需的总时间。 

 
 # 提示 
样例解释：<br>第一组：由于1-&gt;2:2，4-&gt;2:1，所以2号电脑会被入侵成功<br>第二组：1到2,3,4点的时间均为71,5到2,3,4点的时间均为71，防御成功<br><br>对于20%&nbsp;的数据，1&nbsp;&lt;=&nbsp;&nbsp;N&nbsp;&nbsp;&lt;=&nbsp;1000&nbsp;，1&nbsp;&lt;=&nbsp;&nbsp;M&nbsp;&nbsp;&lt;=&nbsp;2000<br>对于60%&nbsp;的数据，1&nbsp;&lt;=&nbsp;&nbsp;N&nbsp;&nbsp;&lt;=&nbsp;5000&nbsp;，1&nbsp;&lt;=&nbsp;&nbsp;M&nbsp;&nbsp;&lt;=&nbsp;100000<br>对于100%的数据，1&nbsp;&lt;=&nbsp;&nbsp;N&nbsp;&nbsp;&lt;=&nbsp;10000，1&nbsp;&lt;=&nbsp;&nbsp;M&nbsp;&nbsp;&lt;=&nbsp;200000<br>对于100%的数据，1&nbsp;&lt;=&nbsp;t,w&nbsp;&lt;=&nbsp;10000，1&nbsp;&lt;=&nbsp;u,v&nbsp;&lt;=&nbsp;N<br>提示：由于学生贪玩，有可能某个电脑没有连接主机，却接入网络；当然也有部分同学上课被禁网了。tjz 
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
<tr><td>[Sample 1]
4 6
1 2
1 2 10
1 3 5
1 4 1
2 3 4
2 4 1
3 4 10

[Sample 2]
5 7
1 1 1
1 2 70
1 3 70
1 4 70
1 5 70
2 5 70
3 5 70
4 5 70</td><td>[Sample 1]
No
2

[Sample 2]
Yes
213</td></tr></table>
