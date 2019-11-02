# 

 
 # 题目描述 
<p>
	曾经有一个国家，那国家有一个女王，她很想有一个儿子。终于10个月后她真的生了个儿子叫TOM。当很不幸，她的儿子有点傻，他只会将若干个整数加起来然后去跟一个给定的整数a比较，看是比a大还是比a小。另外，那些整数要写成一列，TOM只会将这列数中连续的几个数加起来。<br>	后来老国王死了，TOM继承了王位。人们都指责TOM的愚昧。大臣们为了推翻国王于是出了一连串的问题来考他，这一连串的问题是一个整数数列。TOM用他的老方法将这数列的连续几个数加起来，<br>例如，他说:”i n gt k ”，这表示从数列的第i个数开始一直加到第i+n个数所得的和比k要大（注意:gt表示大于，lt表示小于）。又例如，<br>他说：“i n lt k”,这表示丛数列的第i个数开始一直加到第i+n个数所得的和比k要小。TOM一连串说出很多这样子的话，至于是否有一个整数数列完全符合它所说的话，他自己却不知道，现在要你来帮他解决这问题。</p> 

 
 # 输入格式 
<p>
第一行输入m,n(m表示这数列的长度，n表示TOM总共说了n句话)<br>下面共有n行（每行的格式为：’i n gt k’或’i n lt k’ ，其中i,n,k 皆表示整数。本题有多组输入数据，当m等于0时输入结束。</p> 

 
 # 输出格式 
<p>
如果存在一个整数数列符合TOM所说关系的则输出:<br>lamentable kingdom<br>否则输出：<br>successful conspiracy</p> 
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
<tr><td>4 2
1 2 gt 0
2 2 lt 2
1 2
1 0 gt 0
1 0 lt 0
0</td><td>lamentable kingdom
successful conspiracy</td></tr></table>
