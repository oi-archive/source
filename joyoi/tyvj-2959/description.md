# 

 
 # 题目描述 
<p>
区间覆盖（cover.cpp/c/pas）<br><br>【问题描述】<br><br>    给出一个长度为N的小写字母序列。然后给出M个区间，区间可以表示成[Li，Ri]，你可以对这M个区间中的任何一个区间操作。一次操作为左移[Li-1，Ri-1]或者右移[Li+1，Ri+1]，你最多可以操作k次(同一个区间可以操作多次)。<br>    操作完之后你得到新的M组区间，这些区间的交集为[L,R]，你希望[L,R]覆盖的区间内出现次数最多的字母出现次数尽可能的多，询问最多是多少？如果交集不存在则输出0。<br></p> 

 
 # 输入格式 
<p>
第一行三个用空格隔开的正整数N，M，K。接下来一行一个长度为N的由小写字母组成的字符串S。再接下来M行，每行两个用空格隔开的正整数Li和Ri，表示第i个区间Li和Ri。<br></p> 

 
 # 输出格式 
<p>
仅一行表示一些操做完后M个区间形成的交集内出现次数最多的字母出现的次数。无交集则输出0。<br></p> 

 
 # 提示 
<p>
【数据范围】<br>对于30% 的数据 N≤100 M≤100  k≤100<br>对于50% 的数据 N≤1000 M≤10000 k≤10^9 <br>对于100% 的数据 <br>1≤N≤100000  M≤300000  k≤3*10^10  1≤Li≤Ri≤N<br>保证字符串内仅出现小写字母。<br></p> 
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
<tr><td>5 2 2
abbbc
1 3
3 5</td><td>3</td></tr></table>
