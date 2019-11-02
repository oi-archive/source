# 

 
 # 题目背景 
清北学堂杯Tyvj2周年邀请赛&nbsp;第四道 

 
 # 题目描述 
有一种特殊的集合叫做PFS（Prefix&nbsp;Free&nbsp;Set）集合。<BR>一个PFS集合由若干字符串构成，且不存在一个字符串是另一个字符串的前缀。空集也被看作是PFS集合。<BR>例如&nbsp;{"hello"}&nbsp;和&nbsp;{"hello",&nbsp;"goodbye",&nbsp;"giant",&nbsp;"hi"}&nbsp;是pfs集合，但&nbsp;{"hello","hell"}&nbsp;和&nbsp;{"great","gig","g"}&nbsp;不是。<BR>现在给你一个集合，请你求出它的子集是PFS集合的子集个数对9191取模后的答案。 

 
 # 输入格式 
输入数据第一行一个整数n，表示集合里元素的个数。<BR>以下n行，每行一个非空字符串s，仅包含小写英文字母，表示集合中的元素。数据保证不存在两个相同的字符串。 

 
 # 输出格式 
输出一个正整数ans，表示对9191取模后的答案。 

 
 # 提示 
【输入输出解释】<BR>除了&nbsp;{"hell","hello"}&nbsp;和&nbsp;{"hi","hello","hell"}&nbsp;两种情况外，其余情况均是PFS集合。<BR><BR>【数据范围】<BR>对于30%的数据，n≤20；<BR>对于100%的数据，1≤n≤50000，字符串长度不大于50。 
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
hello
hi
hell</td><td>6
</td></tr></table>
