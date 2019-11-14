# 

 
 # 题目描述 
&nbsp;&nbsp;某一天在网上闲逛的玖君不小心发现了TYVJ，就立刻被TYVJ吸引住了，果断驻扎下来。玖君决定按照顺序来切题，因为离复赛越来越近了，所以他希望能够用最短时间AC掉前面N道题目，完成第i道题目玖君需要花费t[i]个单位的代价。玖君做题有个特点，他喜欢看完几道题后，一次把几道题的代码写完。如果玖君决定一次写完从编号L到编号R的题目，那么他完成这些题目的总代价等于编号L到R题目的代价之和与R之积，即SUM{t[L..R]}&nbsp;*R。此外每道题在被切之前都会等待被切，等待的时间，也被算在代价里面，对于每个第k次被切的题，在它被切之前的等待代价为(k-1)*S。综上，切完N道题的总代价=第1次切题的代价+第2次切题的代价+...+第k次切题的代价+每道题的等待代价。现在我们想知道玖君切完这N道题目的最小代价。&nbsp; 

 
 # 输入格式 
第1行：2个用空格分开的整数N,&nbsp;S<BR>第2行：N个用空格分开的整数，分别表示t[1]到t[N]<BR> 

 
 # 输出格式 
第1行：1个整数，表示玖君完成N道题的最小代价<BR> 

 
 # 提示 
[样例解释]<BR>第1次切1、2、3题：代价为48<BR>第2次切4题：代价为24<BR>其中每道题的等待时间代价为:0,0,0,7<BR>共计48&nbsp;+&nbsp;24&nbsp;+&nbsp;7&nbsp;=&nbsp;79<BR><BR>[数据范围]<BR>对于70%的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;3000<BR>对于100%的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;30000<BR>对于100%的数据，1&nbsp;&lt;=&nbsp;S,t[i]&nbsp;&lt;=&nbsp;100<BR> 
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
<tr><td>4 7
8 1 7 6
</td><td>79
</td></tr></table>
