# 

 
 # 题目描述 
<h2 style="font-style:italic;">&nbsp;</h2>

<p><span style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">一天有</span><span lang="EN-US" style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">T</span><span style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">个时段，约翰正打算安排他的</span><span lang="EN-US" style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">N</span><span style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">只奶牛来值班。每只奶牛都有自己的空闲时间段</span><span lang="EN-US" style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">[si,ei],</span><span style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">只能安排空闲的奶牛来值班，而且，每个时间段都必须有奶牛值班。最少需要动用多少奶牛参与值班？如果无法安排，则输出-1</span></p> 

 
 # 输入格式 
<p style="color: rgb(0, 0, 0); font-family: &quot;Times New Roman&quot;; font-size: 14px;">第1行：整数N和T</p>

<p style="color: rgb(0, 0, 0); font-family: &quot;Times New Roman&quot;; font-size: 14px;">第2..N+1行：第i行表示第i-1奶牛空闲的起始时间和结束时间</p> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-family: &quot;Times New Roman&quot;; font-size: 14px; background-color: rgb(228, 240, 248);">一行：约翰需要雇佣的最少奶牛数，如果无法安排，输出-1</span></p> 

 
 # 提示 
<p><span style="color: rgb(0, 0, 255); font-family: 宋体; font-size: 14px; background-color: rgb(228, 240, 248);">1&lt;=T&lt;=10^6&nbsp;</span><span lang="EN-US" style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">1&lt;=N&lt;=25000&nbsp;</span><span lang="EN-US" style="font-size: 14px; background-color: rgb(228, 240, 248); color: blue; font-family: 宋体;">1&lt;=si&lt;=ei&lt;=T</span></p> 
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
<tr><td>3 10
1 7
3 6
6 10</td><td>2</td></tr></table>
