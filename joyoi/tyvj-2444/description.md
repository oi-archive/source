# 

 
 # 题目描述 
<p>
农夫John的农场遭受了一场地震.有一些牛棚遭到了损坏,但幸运地,所有牛棚间的路经都还能使用.<br><br>FJ的农场有P(1 <= P <= 30,000)个牛棚,编号1..P. C(1 <= C <= 100,000)条双向路经联<br>接这些牛棚,编号为1..C. 路经i连接牛棚a_i和b_i (1 <= a_i<= P;1 <= b_i <= P).路经<br>可能连接a_i到它自己,两个牛棚之间可能有多条路经.农庄在编号为1的牛棚.<br><br>N (1 <= N <= P)头在不同牛棚的牛通过手机短信report_j(2 <= report_j <= P)告诉FJ它<br>们的牛棚(report_j)没有损坏,但是它们无法通过路经和没有损坏的牛棚回到到农场.<br><br>当FJ接到所有短信之后,找出最小的不可能回到农庄的牛棚数目.这个数目包括损坏的牛棚.<br><br>注意:前50次提交将提供在一些测试数据上的运行结果.<br><br></p> 

 
 # 输入格式 
<p>
* 第1行: 三个空格分开的数: P, C, 和 N<br><br>* 第2..C+1行: 每行两个空格分开的数: a_i 和 b_i<br><br>* 第C+2..C+N+1行: 每行一个数: report_j<br><br></p> 

 
 # 输出格式 
<p>
* 第1行: 一个数,最少不能回到农庄的牛的数目(包括损坏的牛棚).<br></p> 

 
 # 提示 
<p>
牛棚2遭到损坏,导致牛棚2, 3, 4里面的牛无法回到农庄.<br></p> 
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
<tr><td>4 3 1
1 2
2 3
3 4
3


</td><td>3
</td></tr></table>
