# 

 
 # 题目描述 
<p>
Ramesses二世刚刚获胜归来。为了纪念这一胜利，他决定建造一座壮观的花园。这个花园里的植物排成一行，从他在Luxor的宫殿直达Karnak的神庙。所种植的植物只有莲花和纸莎草，因为它们分别代表上埃及和下埃及。<br>这个花园中必须有N棵植物，并且必须保持平衡，即在花园中任取一段，其中莲花和纸莎草的棵数之差不能超过2。<br>花园可以被表示为由字母L（莲花）和P（纸莎草）组成的字符串。例如，当N等于5时，有14种可能的平衡花园，按照字母排序如下：LLPLP，LLPPL，LPLLP，LPLPL，LPLPP， LPPLL，LPPLP，PLLPL，PLLPP，PLPLL，PLPLP，PLPPL，PPLLP 和 PPLPL。<br>给定长度的所有可能的平衡花园可按字母顺序排序，并从1开始编号。例如，当N等于5时，第12号花园是PLPPL。<br>任务<br>写一个程序，给定植物棵数N和一个表示平衡花园的字符串，计算该花园的序号模M的结果，其中M是一个给定的整数。<br>注意，在问题求解中，数值 M 除了简化计算外没有其他的作用。<br>限制<br>1 <= N <= 1,000,000<br>7 <= M <= 10,000,000<br>评分<br>有总分40分的测试点的N不超过40。<br></p> 

 
 # 输入格式 
<p>
你的程序需要从标准输入上读入下列数据：<br>&#61548;	第一行是整数N，说明花园中植物的数量。<br>&#61548;	第二行是整数M。<br>&#61548;	第三行是长度为N的由字符L或P组成的字符串，表示一个平衡的花园。<br></p> 

 
 # 输出格式 
<p>
你的程序需要向标准输出上输出一个介于0和M-1（含）的整数，占一行，表示该花园的序号模M。<br></p> 

 
 # 提示 
<p>
实际的序号是12。因此输出的是12模7，即5。<br></p> 
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
<tr><td>5
7
PLPPL	</td><td>5</td></tr></table>
