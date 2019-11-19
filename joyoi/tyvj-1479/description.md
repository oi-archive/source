# 

 
 # 题目描述 
小Z是某市的著名作曲家，曾经谱写过著名的音乐《The&nbsp;Forgotten&nbsp;Sky》。同时呢，他又是一个狂热的OI爱好者。他总是喜欢提出一些常人难以理解也难以回答的问题。这天他碰见了来泡机房的Andy，于是想出题难一难Andy。可是又不能用现成的问题……因为Andy实在是太牛逼了，以至于他居然刷遍了所有的OJ，切过了所有的Contest，并把标程熟记于心……无奈之际，小Z拿出他最近写的乐谱，灵光一现，给Andy提出了一个问题，一下子难倒了Andy。<BR><BR>小Z的乐谱上有N个音符A[i]（用整数表示，每个都在1到N之间），同时每个音符存在一个和谐值B[i]（用整数表示，每个都在1到N之间），小Z让Andy求出最和谐的一段谱子。最和谐的谱子的和谐值定义为：Max((B[i]+B[j])*k^2)&nbsp;(i&lt;j)&nbsp;，其中k为乐谱中以i开头的后缀和以j开头的后缀的最长公共前缀。<BR><BR>Andy被这个莫名其妙的古怪问题给难倒了……只好来求助于你。希望你给他一个解答。<BR><BR> 

 
 # 输入格式 
第一行：Test表示测试数据的组数；<BR>以下每组：<BR>第一行：N(N&lt;=10^5)；<BR>第二行：A[1..N]&nbsp;&nbsp;(1&lt;=A[i]&lt;=N)；<BR>第三行：B[1..N]&nbsp;&nbsp;(1&lt;=B[i]&lt;=N)；<BR>中间没有空行。 

 
 # 输出格式 
对应每组读入单独一行，输出最大的和谐值。 

 
 # 提示 
【样例解释】<BR>3和4的后缀分别为2&nbsp;2&nbsp;1和2&nbsp;1，最长公共前缀为1，所以k=1<BR>Ans=1*1*(3+4);<BR>【数据范围】：<BR>25%&nbsp;&nbsp;N&lt;=100;<BR>50%&nbsp;&nbsp;N&lt;=5000;<BR>100%&nbsp;N&lt;=100000，Test&lt;=6;<BR>【提示】：<BR>C++选手请尽量使用scanf和printf而不是cin和cout.钱桥大牛出题；<BR>Skywalker_Q小菜提供题目描述； 
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
<tr><td>1
5
1 1 2 2 1
1 2 3 4 5</td><td>7</td></tr></table>
