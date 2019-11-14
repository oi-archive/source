# 

 
 # 题目背景 
请注意本题的内存限制T_T<br>另外，这1MB内存中包含程序编译和头文件、类库所占的内存，您在计算程序消耗的内存时应该把这部分内存计算在内！<br>在Tyvj上，编译运行一段包含主要头文件、不含任何变量的C++/C程序，需要消耗200~300KB的内存；<br>编译运行一段不调用任何库、不含任何变量的Pascal程序，需要消耗500~600KB内存。<br><br>教学：如何估算内存？<br>常见数据类型中&nbsp;char/byte为1B，short/integer为2B，int/longint为4B，long&nbsp;long/int64为8B。<br>例如你开了长度为L的int数组，估算内存为：(L*4)/1024/1024&nbsp;MB。其中4表示int占4B。<br><br> 

 
 # 题目描述 
VariantF在Minecraft中走着走着突然迷了路。Minecraft世界中有N座房屋，他目前所在的地方是1号房屋，而VariantF的家在N号房屋。每两座房屋之间都有一条长度为1的有向道路相连，但是由于某些道路上有僵尸、骷髅射手、蜘蛛、JJ怪、末影人等怪物，或者是岩浆、湍流、悬崖等恶劣环境，所以这些道路是不能通过的。道路的连接情况用一个N*N的01矩阵表示，如果矩阵中第i行第j列是1，那么从i到j的道路可以通过，否则不能。现在VariantF想尽快回到家，你能帮他求出从1到N的最短路径吗？<br><br><br> 

 
 # 输入格式 
输入数据的第一行是一个整数N。<br>接下来N行每行N个字符'0'或'1'，中间没有空格，表示描述道路连接情况的01矩阵。<br><br>Pascal选手请注意：由于本题内存限制较小，读入一行字符串可能会出现异常情况，强烈建议您使用repeat读入单个字符！<br>示例读入代码如下（ch:char;为当前要读入的字符）：<br>repeat&nbsp;read(ch);&nbsp;until&nbsp;(ch='0')or(ch='1');<br><br><br> 

 
 # 输出格式 
输出一个整数，表示从1到N的最短路长度。<br><br><br> 

 
 # 提示 
对于20%的数据，1&lt;=N&lt;=100.<br>对于100%的数据，1&lt;=N&lt;=1000.<br>保证存在解<br><br><br>Admin(zhqc)&nbsp;Tyvj三周年邀请赛&nbsp;第一题<br><br><br> 
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
<tr><td>3
010
101
111


</td><td>2


</td></tr></table>
