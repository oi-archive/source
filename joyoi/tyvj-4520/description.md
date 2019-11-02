# 

 
 # 题目背景 
<p>自从shy在化学课上学习了烷烃，shy觉得C<sub>n</sub>H<sub>2n+2</sub>真的十分的神奇。但是shy很懒，课后作业多麻烦呀，每次都要画结构简式；所以，shy希望你能帮助TA为烷烃命名&gt;_&lt;</p> 

 
 # 输入格式 
<p>第一行为正整数n：n表示碳原子个数，标号为1~n。</p>

<p>第二行开始n-1行每行两个整数u，v：表示u和v之间有一根碳碳单键。输入数据保证符合化学中烷烃的性质，即<strong>1个碳原子最多与4个碳原子相连</strong>。</p> 

 
 # 输出格式 
<p>当数据为链时，也就是正n烷时：如果只有1个C，输出JiaWan（注：分子式CH4，中文名甲烷）；如果有2个C，输出YiWan；...；如果有11个C，输出ShiYiWan；...；如果有16个C，输出ShiLiuWan；...如果有109个C，输出YiBaiLingJiuWan；如果有110个C，输出YiBaiYiShiWan；...依此类推。</p>

<p>如果数据不为链，取最长链为主链，<strong>数据保证支链上的点的度数小于等于2</strong>；如果主链有多条，取支链数目最多的一条链为主链；将支链从左到右以位置作为其编号，选择使编号字典序尽量小的方案；当编号相同时，按照甲基、乙基...的优先级来使甲基的编号尽量小。输出时数字与数字用&rsquo;,&rsquo;隔开，数字与文字用&rsquo;-&rsquo;隔开。使用类似化学上的系统命名法输出名字的拼音，开头大写。具体请移步样例。</p> 

 
 # 提示 
<p>30%的数据，构造为一条链。</p>

<p>30%的数据，n&lt;=15。</p>

<p>40%的数据，n&le;300000（假设题目中的长碳链能在一定条件下稳定&larr;强行解释）。</p>

<p>对于样例，样例一是2-甲基丙烷；样例二是3,5-二甲基辛烷；样例三是3-甲基-4-乙基己烷。</p>

<p>由于数据规模较大，pascal的同学请在程序前添加{$M&nbsp;100000000,0,100000000}来扩大栈空间。</p>

<p>其实就是道码农题，细心慢慢做就能成功的。</p>

<p><u>Thanks&nbsp;for&nbsp;viewing&nbsp;this&nbsp;problem.</u></p> 
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
<tr><td>4
1 2
4 2
2 3</td><td>2-JiaJiBingWan

（样例一其实就是异丁烷）</td></tr><tr><td>10
1 2
2 3
3 4
4 5
2 6
6 7
4 8
8 9
9 10</td><td>3,5-ErJiaJiXinWan</td></tr><tr><td>9
1 2
2 3
3 4
4 5
5 6
3 7
7 8
4 9</td><td>3-JiaJi-4-YiJiJiWan</td></tr></table>
