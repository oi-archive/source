
# Content

- 美国核潜艇来不了黄海，因为老百姓在种海带。

相应局座号召，$Pxt$打算研究海带种植。初步研究过供海带种植的海域后，$Pxt$将海域分为了环形的$n$块，顺时针编号$1$到$n$。并且每块海域都有一个预期收益$A_i$，如果在这里种海带预期可以得到$A_i$的收益。$Pxt$发现如果一个种植方案里，任意两片相邻海域不同时种海带，则花费相同成本种植收益更高而且防御核潜艇的面积更大（$i$号位置和$i+1$号位置叫相邻位置。$1$号和$n$号也是相邻位置）。

$Pxt$打算在$m$块区域种海带，请你帮忙设计方案满足以上条件并使得收益总和最大。如果无法将$m$片海域种上海带，给出无解信息。

# Standard Input

第1行两个正整数$n,m$。

第2行，每行$n$个整数$A_i$。

# Standard Output

一个整数表示最大预期收益。如果无解输出"$Error!$"

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
<tr><td>7 3 
1 2 3 4 5 6 7</td><td>15</td></tr></table>


# Constraints

$1≤m≤n≤200000$

$-1000≤ A_i ≤1000$

# Note

样例解释：选3,5,7，满足选择m块区域不相邻区域且收益最大

# Source


