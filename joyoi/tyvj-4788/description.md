# 

 
 # 题目背景 
<p><span style="color: rgb(0, 0, 0); font-family: serif; font-size: 16px;">在市场上有很多商品的定价类似于&nbsp;999&nbsp;元、4999&nbsp;元、8999&nbsp;元这样。它们和&nbsp;1000&nbsp;元、5000&nbsp;元和&nbsp;9000&nbsp;元并没有什么本质区别，但是在心理学上会让人感觉便宜很多，因此也是商家常用的价格策略。不过在你看来，这种价格十分荒谬。于是你如此计算一个价格&nbsp;p（p&nbsp;为正整数）的荒谬程度：</span></p> 

 
 # 题目描述 
<p style="margin: 0px 10px; font-family: serif; padding: 3px; color: rgb(0, 0, 0); font-size: 16px;">1、首先将&nbsp;p&nbsp;看做一个由数字组成的字符串（不带前导&nbsp;0）；</p>

<p style="margin: 0px 10px; font-family: serif; padding: 3px; color: rgb(0, 0, 0); font-size: 16px;">2、然后，如果&nbsp;p&nbsp;的最后一个字符是&nbsp;0，就去掉它。重复这一过程，直到&nbsp;p&nbsp;的最后一个字符不是&nbsp;0；</p>

<p style="margin: 0px 10px; font-family: serif; padding: 3px; color: rgb(0, 0, 0); font-size: 16px;">3、记&nbsp;p&nbsp;的长度为&nbsp;a，如果此时&nbsp;p&nbsp;的最后一位是&nbsp;5，则荒谬程度为&nbsp;2&nbsp;*&nbsp;a&nbsp;-&nbsp;1；否则为&nbsp;2&nbsp;*&nbsp;a。</p>

<p style="margin: 0px 10px; font-family: serif; padding: 3px; color: rgb(0, 0, 0); font-size: 16px;">例如，850&nbsp;的荒谬程度为&nbsp;3，而&nbsp;880&nbsp;则为&nbsp;4，9999&nbsp;的荒谬程度为&nbsp;8。</p>

<p style="margin: 0px 10px; font-family: serif; padding: 3px; color: rgb(0, 0, 0); font-size: 16px;">现在，你要出售一样闲置物品，你能接受的定价在&nbsp;[L,&nbsp;R]&nbsp;范围内，你想要给出一个荒谬度最低的价格。</p> 

 
 # 输入格式 
<p style="margin: 0px 10px; font-family: serif; padding: 3px; color: rgb(0, 0, 0); font-size: 16px;">输入文件的第一行包含一个正整数&nbsp;T，表示测试数据的数目。</p>

<p style="margin: 0px 10px; font-family: serif; padding: 3px; color: rgb(0, 0, 0); font-size: 16px;">每个测试数据占单独的一行，包含两个空格分隔的正整数&nbsp;L,&nbsp;R，表示定价的区间。</p> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-family: serif; font-size: 16px;">对于每个测试数据，在单独的一行内输出结果。如果荒谬度最低的价格不唯一，输出最小的那个。</span></p> 
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
<tr><td>3
998 1002
998 2002
4000 6000</td><td>1000
1000
5000</td></tr></table>
