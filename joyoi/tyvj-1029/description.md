# 

 
 # 题目背景 
USACO&nbsp;OCT09&nbsp;3RD 

 
 # 题目描述 
奶牛们灰常享受在牛栏中牟叫，因為她们可以听到她们牟声的回音。虽然有时候并不能完全听到完整的回音。Bessie曾经是一个出色的秘书，所以她精确地纪录了所有的牟叫声及其回声。她很好奇到底两个声音的重复部份有多长。<BR><BR>输入两个字符串（长度為1到80个字母），表示两个牟叫声。你要确定最长的重复部份的长度。两个字符串的重复部份指的是同时是一个字符串的前缀和另一个字符串的后缀的字符串。<BR><BR>我们通过一个例子来理解题目。考虑下面的两个牟声：<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;moyooyoxyzooo<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;yzoooqyasdfljkamo<BR><BR>第一个串的最后的部份"yzooo"跟第二个串的第一部份重复。第二个串的最后的份"mo"跟第一个串的第一部份重复。所以"yzooo"跟"mo"都是这2个串的重复部份。其中，"yzooo"比较长，所以最长的重复部份的长度就是5。 

 
 # 输入格式 
输入格式:<BR><BR>*&nbsp;前两行:&nbsp;每一行是1个字符串表示奶牛的牟声或它的回声。<BR><BR><BR><BR> 

 
 # 输出格式 
输出格式:<BR><BR>*&nbsp;第一行:&nbsp;包含一个单独的整数表示输入的2个字符串中，一个字符串的前缀和另一个字符串的后<BR>	缀的最长的重复部份的长度。<BR><BR> 

 
 # 提示 
"abcxxxxabcx"是第一个字符串的前缀和第二个字符串的后缀。 
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
<tr><td>abcxxxxabcxabcd
abcdxabcxxxxabcx
</td><td>11
</td></tr></table>
