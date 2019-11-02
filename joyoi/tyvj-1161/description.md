# 

 
 # 题目背景 
明天就是candy的生日，candy又会邀请自己的一大堆好友来聚会了！哎！又要累坏飘飘乎居士了！！ 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;明天就是candy的生日。晚上，candy找到了飘飘乎居士。她给了飘飘乎居士一张名单，名单上记录了n个candy的好朋友。可是，飘飘乎居士发现，名单上有好多重复的名字啊，这可急坏了飘飘乎居士。所幸，飘飘乎居士找到了自己的oi朋友，希望能够帮助自己。飘飘乎居士会问某个名字，而你要做的任务就是计算出名单中出现了几次该名字。 

 
 # 输入格式 
第一行一个正整数n；<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，每行一个字符串（长度不超过20，均由小写字母组成），代表名单上的名字；<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来一行一个正整数m，表示飘飘乎居士一共会询问m次<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;紧接着m行，每行一个字符串（长度不超过20，均由小写字母组成），表示飘飘乎居士询问名单上的某个名字，如果没有出现过，则输出0；否则输出出现的次数。<BR> 

 
 # 输出格式 
一共m行。<BR>第i行对应飘飘乎居士第i次提问的名字在名单中出现的次数。<BR> 

 
 # 提示 
对于50%的数据，保证0&lt;n&nbsp;m&lt;2000<BR>对于100%的数据，保证0&lt;n&nbsp;m&lt;20000<BR>来源&nbsp;飘飘乎居士——Violet&nbsp;Hill&nbsp; 
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
candy
candy
candy
violethill
sugar
6
candy
candy
rooney
sugar
violethill
giggs
</td><td>3
3
0
1
1
0
</td></tr></table>
