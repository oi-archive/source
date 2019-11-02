# 

 
 # 题目描述 
佳佳刚进高中，在军训的时候，由于佳佳吃苦耐劳，很快得到了教官的赏识，成为了“小教官”。在军训结束的那天晚上，佳佳被命令组织同学们进行篝火晚会。一共有&nbsp;n&nbsp;个同学，编号从&nbsp;1&nbsp;到&nbsp;n&nbsp;。一开始，同学们按照&nbsp;1&nbsp;，&nbsp;2&nbsp;，……，&nbsp;n&nbsp;的顺序坐成一圈，而实际上每个人都有两个最希望相邻的同学。如何下命令调整同学的次序，形成新的一个圈，使之符合同学们的意愿，成为摆在佳佳面前的一大难题。&nbsp;<BR><BR>佳佳可向同学们下达命令，每一个命令的形式如下：&nbsp;<BR><BR>(b&nbsp;1&nbsp;,&nbsp;b&nbsp;2&nbsp;,...&nbsp;b&nbsp;m&nbsp;-1&nbsp;,&nbsp;b&nbsp;m&nbsp;)&nbsp;<BR><BR>这里&nbsp;m&nbsp;的值是由佳佳决定的，每次命令&nbsp;m&nbsp;的值都可以不同。这个命令的作用是移动编号是&nbsp;b&nbsp;1&nbsp;，&nbsp;b&nbsp;2&nbsp;，……&nbsp;b&nbsp;m&nbsp;–1&nbsp;，&nbsp;b&nbsp;m&nbsp;的这&nbsp;m&nbsp;个同学的位置。要求&nbsp;b&nbsp;1&nbsp;换到&nbsp;b&nbsp;2&nbsp;的位置上，&nbsp;b&nbsp;2&nbsp;换到&nbsp;b&nbsp;3&nbsp;的位置上，……，要求&nbsp;b&nbsp;m&nbsp;换到&nbsp;b&nbsp;1&nbsp;的位置上。&nbsp;<BR><BR>执行每个命令都需要一些代价。我们假定如果一个命令要移动&nbsp;m&nbsp;个人的位置，那么这个命令的代价就是&nbsp;m&nbsp;。我们需要佳佳用最少的总代价实现同学们的意愿，你能帮助佳佳吗？<BR> 

 
 # 输入格式 
输入文件&nbsp;的第一行是一个整数&nbsp;n&nbsp;（&nbsp;3&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;50000&nbsp;），表示一共有&nbsp;n&nbsp;个同学。其后&nbsp;n&nbsp;行每行包括两个不同的正整数，以一个空格隔开，分别表示编号是&nbsp;1&nbsp;的同学最希望相邻的两个同学的编号，编号是&nbsp;2&nbsp;的同学最希望相邻的两个同学的编号，……，编号是&nbsp;n&nbsp;的同学最希望相邻的两个同学的编号。&nbsp;<BR> 

 
 # 输出格式 
输出文件&nbsp;包括一行，这一行只包含一个整数，为最小的总代价。如果无论怎么调整都不能符合每个同学的愿望，则输出&nbsp;-1&nbsp;。&nbsp;<BR> 

 
 # 提示 
对于30%的数据，n&nbsp;&lt;=&nbsp;1000；<BR>对于全部的数据，n&nbsp;&lt;=&nbsp;50000。<BR>noip2005提高组第3题 
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
<tr><td>4
3 4
4 3
1 2
1 2
</td><td>2
</td></tr></table>
