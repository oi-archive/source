# 

 
 # 题目背景 
天使城有一个火车站，每辆火车都从A方向驶入车站，<BR>再从B方向驶出车站。 

 
 # 题目描述 
为了调度火车，火车站设有停放轨道，可存放5辆火车。已知从A进入车站顺序为1、2、3……。现在给你一个调度方案，判断是否可行，如果可行，输出出站顺序。<BR>有以下几种调度方法：<BR>A.	将A上的头一辆车驶出B方向<BR>B.	将A上的头一辆车停入暂停轨道<BR>C.	将暂停轨道上最外面的车驶出B方向<BR> 

 
 # 输入格式 
输入第一行一个整数N(n&lt;30)表示调度方案步骤数目。<BR>下一行一个字符串，有N个大写字母，表示调度方法。<BR> 

 
 # 输出格式 
输出若不可行（暂停站满了还停车、暂停站空了还出车），则输出一行“No”。<BR>若可行，输出一行“Yes”，再输出若干行，每行一个整数，表示车出站序列。<BR> 

 
 # 提示 
栈和队列 
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
<tr><td>[样例输入1]
6
ABBCCA
[样例输入2]
5
BACAC

</td><td>[样例输出1]
Yes
1
3
2
4
[样例输出2]
No
</td></tr></table>
