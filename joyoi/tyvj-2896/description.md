# 

 
 # 题目描述 
<p>
sub的n个小弟们显然对sub的排名感到不满意(废话..因为投票者是sub选定的),于是他们决定自己pk来确定自己的排名.<br><br>Sub其实也很想知道他的这些小弟究竟谁强谁弱..于是他躲在幕后默默观察..<br><br>当然了,实力强的小弟总是能击败实力弱的小弟.sub现在知道了他的小弟们总共进行了m轮对决,并且知道了这m轮对决结果.<br><br>Sub现在想知道,根据这几轮对决的结果,能确定多少小弟的最终排名呢?<br></p> 

 
 # 输入格式 
<p>
第一行两个整数n,m表示总共有n个小第,m场对决.<br><br>1<=n<=100,1<=m<=4500.<br><br>以下m行,每行两个整数ai,bi,表示小弟ai战胜了小弟bi.<br></p> 

 
 # 输出格式 
<p>
一个数,表示能够确定名次的小弟的数量. </p> 

 
 # 提示 
<p>
[样例说明]<br><br>2号小弟输给了1,3,4号小弟,也就是说他的水平比这3个小弟都差.而5号小弟又输在了他的手下,也就是说,他的水平5号小弟强一些.于是,2号小弟的排名必然为第4,5号小弟的水平必然最差,其他3个小弟的排名仍无法确定.<br></p> 
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
<tr><td>5 5
4 3
4 2
3 2
1 2
2 5
</td><td>2</td></tr></table>
