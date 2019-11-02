# 

 
 # 题目描述 
<p>
未出现的子串（unapeared.pas/c/cpp)<br><br>【说明】<br>　　此题中的子数字串,数字并不一定连续出现在母数字串中.比如我们定义1 3是串1 5 3的一个子串,但3 5不是1 5 3的一个子串.<br>串1 5 3的所有子串为:<br>　　1<br>　　5<br>　　3<br>　　1 5<br>　　5 3<br>　　1 3<br>　　1 5 3<br>共7个.<br><br>【题目描述】<br>　　有一个长度为n的数字串,其中会出现数字1,2,3,...,q(5<=q<=9).SubRaY遇到的问题是,需要求出一个长度最小的串(出现的数字也是1..q),使得该串不是这个数字串的子串.为了简化问题,你只需要输出这个串的长度即可.<br>　　例如对于数字串S=<br>　　1 3 5 2 4 1 3 5 2 2 2 2 3 4 1 5 3 2(q=5)<br>　　长度为1和2的数字子串全出现过,但是你找不出子串S'=4 4 4.因此答案是3<br></p> 

 
 # 输入格式 
<p>
　　输入文件unapeared.in第一行两个数,串长n和出现的数字的个数q<br>　　接下来n行表示该数字串每一位的数字.<br></p> 

 
 # 输出格式 
<p>
　　输出文件unapeared.out包含一个数，即未出现的子串的最小长度</p> 

 
 # 提示 
<p>
【数据范围】<br>　　对于30%的数据,1<=n<=20,q=5<br>　　对于100%的数据,1<=n<=100000,5<=q<=9<br></p> 
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
<tr><td>18 5
1
3
5
2
4
1
3
5
2
2
2
2
3
4
1
5
3
2
</td><td>3</td></tr></table>
