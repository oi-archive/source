# 

 
 # 题目描述 
<p>
你在一个组合式家具厂工作，这种组合式家具由各种形状不同的组件组成，例如：

 
 # 输入格式 
<p>
第一行是用空格分隔的三个整数n,w,b。n是一套家具的组件数，1<=n<=100，w和b是箱子的宽和高，1<=w<=10，1<=b<=100。接下来是n个组件的形状描述，按生产的次序排列，每个组件描述第一行是一个整数h，1<=h<=10且h<=b，接下来h行每行w个字符，描述组件的形状，“X”代表组件的部分，“.”代表空间。</p> 

 
 # 输出格式 
<p>
m个整数（m代表装箱所需的箱子数），按装箱的次序输出m个箱子里组件的高度。</p> 
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
<tr><td>3 5 12
5
XXXXX
.XXXX
..XXX
...XX
....X
4
XXX..
..X..
..XXX
..X..
6
X....
X....
X....
X....
X....
XXXXX
</td><td>9 6</td></tr></table>