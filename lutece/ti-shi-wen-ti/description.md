
# Content

最近在JLOI网上的一个流行游戏中，选手要回答很难的问题。假如在规定时间内不能回答，系统将给出1个提示，之后再依次给出第2，3个提示。出现在答案中的是字母和下列字符:`. , : ; ! ? -`和空格（空格不会在开头和结尾出现）  
字母是指：小写字母'a'...'z' 大写字母 'A'...'Z'，其中aeiouAEIOU是元音字母。  
生成提示的规则：  
第1个提示：简单的将所有字母换成'.'即可；  
第2个提示：从第1个提示而来，将所有字母的个数求出，再将总个数除以三，得到的最接近商的自然数N，将第1个提示中的前N个字母显示；  
第3个提示：从第2个提示而来，将剩下的元音字母显示。假如没有可显示的元音字母，则从第1个提示而来，即我们将前2/3的字母显示（同样如不能被3整除则取最接近的整数）。  
**对于20%的数据有 输入不包含元音**  
**对于另外20%的数据有 字符数 是 3 的倍数**  
**对于100%的数据有 字符数 <= 50000**

# Standard Input

仅一行，给出问题

# Standard Output

三行：按规则输出的三行提示

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
<tr><td>Upomoc! Lpv s nm pkrl sv smglsnk.</td><td>......! ... . .. .... .. ........ 
Upomoc! Lp. . .. .... .. ........ 
Upomoc! Lpv s nm pkrl s. ........</td></tr></table>


# Constraints



# Note



# Source


