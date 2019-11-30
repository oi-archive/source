# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;在Admin小时候呆着的幼儿园里有一个巨大的转盘。有N个小朋友按照一定顺序坐在转盘边缘的N个座位上，所有座位之间的距离都相等。有些小朋友之间可能会闹矛盾，为了使得幼儿园更加的和谐，你需要重新安排小朋友的排列。<br>&nbsp;&nbsp;&nbsp;初始情况下正北方向座位上坐着的小朋友编号为1，后依次按照顺时针方向将小朋友编号为2到N。如下图：<br>&nbsp;&nbsp;&nbsp;<img src="/source/joyoi/tyvj-2001/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjAwMS9Qcm9ibGVtSW1nL3AyMDAxLmpwZw==.jpg" border=0 align=middle><br>&nbsp;&nbsp;&nbsp;我们可以用一个序列描述一个转盘上小朋友的情况，从正北方向开始，依次按照顺时针方向将小朋友的编号列出来，如上图对应的序列就是{1,2,3,4,5}。<br>&nbsp;&nbsp;&nbsp;现在你只可以用过下面三种方式操作：<br>&nbsp;&nbsp;&nbsp;1.将整个转盘顺时针旋转1/N圈。这样操作会使得序列变成{5,1,2,3,4}。<br>&nbsp;&nbsp;&nbsp;2.将整个转盘逆时针旋转1/N圈。这样操作会使得序列变成{2,3,4,5,1}。<br>&nbsp;&nbsp;&nbsp;3.交换正北方向的座位和正北顺时针方向第一个座位上的小朋友。这样操作会使得序列变成{2,1,3,4,5}。<br>&nbsp;&nbsp;&nbsp;现在给出你目标序列，输出你最少需要操作多少步。如果这个数大于30，则输出-1。<br><br> 

 
 # 输入格式 
第1行为一个数n，表示有n个小朋友。<br>第2行有n个数，表示目标序列<br><br> 

 
 # 输出格式 
共一行，表示最少操作多少步。<br> 

 
 # 提示 
【样例解释】<br>共经过三次操作<br>1.将序列{1,2,3,4}变为{2,3,4,1}<br>2.将序列{2,3,4,1}变为{3,2,4,1}<br>3.将序列{3,2,4,1}变为{1,3,2,4}<br><br>【数据规模和约定】<br>对于30%的数据&nbsp;n&lt;=5<br>对于50%的数据&nbsp;n&lt;=8<br>对于100%的数据&nbsp;2&lt;=n&lt;=20<br><br><br> 
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
1 3 2 4

</td><td>3
</td></tr></table>
