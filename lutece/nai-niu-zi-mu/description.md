
# Content

约翰家的奶牛用别人听不懂的“牛语”联络。牛语采用英文字母，而且区分大小写。牛语中的语法中，前后字母的衔接非常重要，存在P个基本组合，每个字母之后只能接固定的几个字母。 约翰担心奶牛正在密谋反对他，于是最近一直在偷听她们的对话。可是牛语太复杂了， 他只模模糊糊地听到了一个单词，并确定了这个单词中有U个大写字母，L个小写字母。约翰对这个单词很在意，他想知道，有多少牛语词汇拥有U个大写字母，L个小写字母。由于 这个数字太大了，你只要输出答案取 97654321 的余数就可以了。  
对于20%的数据 U + L <= 20，1<= P <= 10  
对于另外40%的数据  U + L <= 100  
对于100%的数据有  1 ≤ U, L ≤ 250，1 ≤ P ≤ 200

# Standard Input

第一行：三个用空格隔开的整数：U，L和P  
第二行到P + 1行：第i + 1有两个字母Ai和Bi，表示字母Ai后面可以接Bi，没有一对Ai和 Bi是完全相同的

# Standard Output

Line 1: A single integer, the number of valid words consistent with Farmer John's data mod 97654321.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2 2 7 
AB 
ab 
BA 
ba 
Aa 
Bb 
bB </td><td>7 </td></tr></table>


# Constraints



# Note

The word Farmer John overheard had 2 uppercase and 2 lowercase letters. The valid pairs of adjacent letters are AB, ab, BA, ba, Aa, Bb and bB.

The possible words are:

AabB ABba abBA BAab BbBb bBAa bBbB

# Source


