# 

 
 # 题目描述 
<p>
光纤（Fiber.pas\c\cpp）<br><br>【题目描述】<br>　　几个公司决定构建互联网，称为“光纤网”。他们已经在世界各地安装了一些路由器。现在，服务提供商BD公司想知道某个结点能否发送数据到另外一个结点。输入文件给出一些结点之间的连接关系，只要两个结点之间有光纤连接，就能发送接收数据。请编程序帮助BD公司，对输入文件中的询问，回答是否能够发送数据，回答完全正确，你将得到BD公司的高薪聘请。<br><br></p> 

 
 # 输入格式 
<p>
　　输入文件：fiber.in<br>　　第一行：三个整数n,m,p，（n<=5000,m<=5000,p<=5000），分别表示有n    个结点，m个连接关系，询问p对问题。<br>　　以下m行：每行两个数Mi，Mj，1<=Mi，Mj<=N，表示Ai和Bi有光纤连接。<br>　　接下来p行：每行两个数Pi，Pj，询问Pi和Pj是否能发送数据。<br></p> 

 
 # 输出格式 
<p>
　　输出文件：fiber.out<br>　　P行，每行一个’Yes’或’No’。表示第i个询问的答案为“能够”或“不能够”发送数据的关系。<br></p> 
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
<tr><td>6 5 3
1 2
1 5
3 4
5 2
1 3
1 4
2 3
5 6
</td><td>Yes
Yes
No</td></tr></table>
