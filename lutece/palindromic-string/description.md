
# Content

秋实大哥喜欢探索新鲜事物，最近他发明了一种新型回文串，叫K重回文串！今天他想用它来考考小朋友们。

秋实大哥给出了与$K$重回文串有关的信息
>#####任何字符串都属于0重回文串，包括空字符串。
>#####一个长度为$N$的字符串$S$，$S$是$K(k \geq 1)$重回文串，当且仅当$S$是回文串，且其长度为$\lfloor \frac{N}{2} \rfloor$的前缀和长度为$\lfloor \frac{N}{2} \rfloor$的后缀是$K-1$重回文串。
>#####如果一个字符串是$K$重回文串，则称该字符串有一个回文值为$K$。一个字符串可以有多个回文值，比如$S=abaaba$，其回文值可为0，1，2，3。
>#####字符串的最大回文值是该字符串所有回文值的最大值。
>#####若字符串$S$的最大回文值$ \geq 1$，则$S$一定是回文串。
>#####一个字符串$S$，如果其正着读和反着读是一样的，则称$S$是回文串，比如aabaa，aba，a。但abc，abab，aacba就不是回文串。
>#####一个长度为$N$的字符串$S$，其有$N+1$个前缀和$N+1$个后缀（不一定非空），比如abcde，有6个前缀，分别是空字符串，a，ab，abc，abcd，abcde；有6个后缀，分别是空字符串，e，de，cde，bcde，abcde。

####秋实大哥给你一个字符串$S$，他想问问你，$S$所有前缀的最大回文值之和是多少？

# Standard Input

第一行输入一个字符串$S（0<|S| \leq 2\cdot 10^6）$，$S$包含 大写英文字母（A－Z），小写英文字母（a－z），数字（0－9）

# Standard Output

输出一个整数，表示$S$所有前缀的最大回文值之和。

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
<tr><td>z</td><td>1</td></tr><tr><td>a2Az</td><td>1</td></tr><tr><td>abacaba</td><td>6</td></tr><tr><td>CCeCeCCCee</td><td>4</td></tr><tr><td>ZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZ</td><td>231</td></tr></table>


# Constraints



# Note

#####下面对样例3进行解释：

>#####abacaba有8个前缀，分别是 空字符串，a，ab，aba，abac，abaca，abacab，abacaba；

>#####设P(i) 表示第 i 个前缀的最大回文值，且空字符串是第0个前缀；

>#####则P(0)=0，P(1)=1，P(2)=0，P(3)=2，P(4)=0，P(5)=0，P(6)=0，P(7)=3；那么$\sum_{i=0}^7 P(i)=6$。

# Source


