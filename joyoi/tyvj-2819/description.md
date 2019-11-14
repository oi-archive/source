# 

 
 # 题目描述 
<p>
Michel想考一个车牌。因为他已经会开车了，所以没有复习就去考试了。没想到，驾照还要考笔试，Michel于是窘掉了。<br>为了帮助Michel过关，Yoki决定提前偷到试题，然后给Michel答案。（都是选择题。）虽然Yoki可以瞬间得出正确答案，但是因为时间太短，Michel只能记下一部分。为了Michel能顺利过关，Yoki希望你编一个程序，让Michel背尽量少的答案，拿到尽量高的分数。<br>如果Michel把背下的答案都按顺序填上去了还有没填的题，Michel就会重复填一次。例如他背下了ABC，一共10道题，那么Michel的最终答案就是ABCABCABCA。<br></p> 

 
 # 输入格式 
<p>
输入文件的第一行为两个整数n，m，表示题目的数量和Michel能背下的最长的答案。<br>第二行n个字母，描述了每题的答案。<br></p> 

 
 # 输出格式 
<p>
第一行为答案正确的题目数。<br>第二个为Michel需要背的答案长度k。<br>第三行k个字母，描述了Michel背的答案。<br></p> 

 
 # 提示 
<p>
数据范围：<br>对于30％的数据，1<=n<=1000，1<=m<=5<br>对于100％的数据，1<=n<=10000，1<=m<=1000，答案只能是A或B或C或D。<br><br>注意：<br>如果有多组答案，输出答案长度最短的。如果有多种最短答案，输出按字典排序最小的。<br></p> 
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
<tr><td>10 4
ABCABCABCD
</td><td>9
3
ABC</td></tr></table>
