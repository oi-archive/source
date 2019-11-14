# 

 
 # 题目描述 
从前，有一个小青蛙决定去荷叶上练习跳跃.<BR>现在有n个荷叶排成一排，小青蛙一开始在最左边的荷叶(一号荷叶)上，当然，这个青蛙是很牛X的，可以在任意两个荷叶之间跳跃。<BR>有一天这个青蛙突发奇想，想用一种奇怪的方式完成跳跃练习:<BR>1.它希望每次跳到不同的荷叶上<BR>2.每一次跳的距离不同<BR>当然，作出这个决定是何其的简单，但是跳跃方式是何其的困难……,所以他希望你可以帮他解决这个问题.<BR><BR>下面给出这个问题严格的数学定义<BR>请给出1到n这n个自然数的一个排列a1,a2,a3……an<BR>使得<BR>1：a1=1<BR>2：对于任意的i&lt;&gt;j(1&lt;=i,j&lt;=n-1)，有|ai-a(i+1)|&lt;&gt;|aj-a(j+1)|<BR>其中n是给定的 

 
 # 输入格式 
一行，一个数n 

 
 # 输出格式 
一行，n个数，用一个空格隔开,末尾没有多余空格<BR><BR> 

 
 # 提示 
数据范围：<BR>对于20%的数据，1&lt;n&lt;=4<BR>对于100%的数据，1&lt;n&lt;=10000西部314&nbsp;&nbsp;TYVJ首届月赛&nbsp;第一道 
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
</td><td>1 3 2
</td></tr></table>
