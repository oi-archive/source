# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;某公司加工一种由铁、铝、锡组成的合金。他们的工作很简单。首先进口一些铁铝锡合金原材料，不同种类的原材料中铁铝锡的比重不同。然后，将每种原材料取出一定量，经过融解、混合，得到新的合金。新的合金的铁铝锡比重为用户所需要的比重。<BR>&nbsp;&nbsp;&nbsp;&nbsp;<BR>现在，用户给出了n种他们需要的合金，以及每种合金中铁铝锡的比重。公司希望能够订购最少种类的原材料，并且使用这些原材料可以加工出用户需要的所有种类的合金。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;第一行两个整数m和n（m,&nbsp;n&nbsp;≤&nbsp;500），分别表示原材料种数和用户需要的合金种数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2到m&nbsp;+&nbsp;1行，每行三个实数a,&nbsp;b,&nbsp;c（a,&nbsp;b,&nbsp;c&nbsp;≥&nbsp;0&nbsp;且&nbsp;a&nbsp;+&nbsp;b&nbsp;+&nbsp;c&nbsp;=&nbsp;1），分别表示铁铝锡在一种原材料中所占的比重。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第m&nbsp;+&nbsp;2到m&nbsp;+&nbsp;n&nbsp;+&nbsp;1行，每行三个实数a,&nbsp;b,&nbsp;c（a,&nbsp;b,&nbsp;c&nbsp;≥&nbsp;0&nbsp;且&nbsp;a&nbsp;+&nbsp;b&nbsp;+&nbsp;c&nbsp;=&nbsp;1），分别表示铁铝锡在一种用户需要的合金中所占的比重。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;一个整数，表示最少需要的原材料种数。若无解，则输出–1。 
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
<tr><td>3 2
0.25 0.25 0.5
0 0.5 0.5
1 0 0
0.7 0.1 0.2
0.85 0.05 0.1
</td><td>2</td></tr></table>
