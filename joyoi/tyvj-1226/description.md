# 

 
 # 题目描述 
为了庆祝元旦，J市决定举办全市小学足球联赛。各学校积极响应，共有N支球队报名参加，爱好足球的小W也参加了。为了活动的开展和不影响学生学习，只能安排K场比赛，每支球队最多参加两场比赛，至少参加零场比赛。因球队水平不同，每支球队都拥有一个和其他球队不同的水平等级（用一个正整数来表示）。在比赛中，等级高的球队必须作为客场，等级低的球队必须作为主场。每个球队最多只能做一次主场和一次客场。为了增加比赛的观赏度，观众希望K场比赛中球队水平差距的总和最小。比如有7支球队，他们的等级分别是30、17、26、41、19、38、18，要进行3场比赛。那么最好安排是球队2&nbsp;&nbsp;vs&nbsp;球队7,&nbsp;球队7&nbsp;vs&nbsp;球队5&nbsp;,球队6&nbsp;vs&nbsp;球队4，此时等级差的总和等于(18-17)&nbsp;+&nbsp;(19-18)&nbsp;+&nbsp;(41-38)&nbsp;=&nbsp;5达到最小。 

 
 # 输入格式 
第一行两个正整数N&nbsp;，K。<BR>接下来有N&nbsp;行，第i行表示第i&nbsp;支球队的等级。<BR> 

 
 # 输出格式 
共一行，输出最小的等级差的总和。 

 
 # 提示 
n&lt;=10000&nbsp;k&lt;=1000&nbsp;等级小于maxlongint 
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
<tr><td>7 3 
30 
17 
26 
41 
19 
38 
18
</td><td>5</td></tr></table>
