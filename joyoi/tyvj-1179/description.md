# 

 
 # 题目背景 
飘飘乎居士最近又迷恋上了一个MM，为了能够追到MM,他研究了一种游戏，希望和MM能够一起度过美好时光(*^__^*)&nbsp; 

 
 # 题目描述 
游戏的内容是这样的：开始时，游戏者会得到n个长度为m的数字，不足位数的用前导0补足。<BR>游戏者需要从这n个数字中按顺序找出k个数字，构成一个新的数列，<BR>这个数列必须满足以下性质：数列的第i个数字通过改变某个位置上的数字（而且只能改变一个位置），等于第i+1个数字，<BR>例如：0010与0110，改变0010的第三位数0，使他变长1，得到0110，就得到了下一个数字。<BR>但是，不能够不改变而直接得到下一个数字，例如&nbsp;1101与1101连在一起就是不合法的。<BR>为了能够让MM&nbsp;Orz&nbsp;飘飘乎居士，飘飘乎居士的任务就是尽快找出k的最大值。<BR> 

 
 # 输入格式 
第一行，2个正整数&nbsp;n和m，表示一共有n个长度为m的数字<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，每行1个长度为m的数字<BR> 

 
 # 输出格式 
一行，表示最大的数列长度k<BR> 

 
 # 提示 
对于30%的数据&nbsp;0&lt;n&lt;=2000<BR>对于100%的数据&nbsp;0&lt;n&lt;=20000&nbsp;&nbsp;0&lt;m&lt;=10<BR><BR>一个5个数字<BR>&nbsp;&nbsp;飘飘乎居士将会选择0010与0000构成新的数列，因为0010改变第2位的1能够变成0000，而最长的也就是这2个数列了。所以最后的答案是2飘飘乎居士——violet&nbsp;hill 
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
<tr><td>5 4
0010
9109
0000
1111
7878</td><td>2</td></tr></table>
