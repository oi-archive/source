# 

 
 # 题目描述 
Farmer&nbsp;John最近为奶牛们的图书馆添置了一个巨大的书架，尽管它是如此<BR>的大，但它还是几乎瞬间就被各种各样的书塞满了。现在，只有书架的顶上还留<BR>有一点空间。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;所有N(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;20,000)头奶牛都有一个确定的身高H_i<BR>(1&nbsp;&lt;=&nbsp;H_i&nbsp;&lt;=&nbsp;10,000)。设所有奶牛身高的和为S。书架的高度为B，并且保证<BR>1&nbsp;&lt;=&nbsp;B&nbsp;&lt;=&nbsp;S&nbsp;&lt;&nbsp;2,000,000,007。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;为了够到比最高的那头奶牛还要高的书架顶，奶牛们不得不象演杂技一般，<BR>一头站在另一头的背上，叠成一座“奶牛塔”。当然，这个塔的高度，就是塔中<BR>所有奶牛的身高之和。为了往书架顶上放东西，所有奶牛的身高和必须不小于书<BR>架的高度。显然，塔中的奶牛数目越多，整座塔就越不稳定，于是奶牛们希望在<BR>能够到书架顶的前提下，让塔中奶牛的数目尽量少。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;现在，奶牛们找到了你，希望你帮她们计算这个最小的数目。<BR> 

 
 # 输入格式 
*&nbsp;第1行:&nbsp;2个用空格隔开的整数：N&nbsp;和&nbsp;B<BR><BR>*&nbsp;第2..N+1行:&nbsp;第i+1行是1个整数：H_i<BR> 

 
 # 输出格式 
*&nbsp;第1行:&nbsp;输出1个整数，即最少要多少头奶牛叠成塔，才能够到书架顶部<BR> 

 
 # 提示 
输入说明:<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;一共有6头奶牛，书架的高度为40，奶牛们的身高在6..19之间。<BR><BR>输出说明:<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;一种只用3头奶牛就达到高度40的方法：18+11+13。当然还有其他方法，在<BR>此不一一列出了。<BR> 
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
<tr><td>6 40
6
18
11
13
19
11
</td><td>3
</td></tr></table>
