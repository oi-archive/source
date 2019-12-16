# 

 
 # 题目描述 
<p>
你在一个组合式家具厂工作，这种组合式家具由各种形状不同的组件组成，例如：<br><br><br><center><img src="/source/joyoi/tyvj-2978/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk3OC9wcm9ibGVtc19pbWFnZXMvMzU3Ny90MS5ibXA=.bmp"></img></center> <br>                                                图1 三种不同形状的组件<br><br>这些组件生产出来后将被自动装箱，组件按生产的次序落下，第一个组件落在箱子底部，其后的组件依次落下，直至组件接触到之前装入的组件或箱子底部。例如，假设组件按图1从左至右的次序生产出来，装箱结果将如图2左所示。假如按图1从右至左的次序生产出来，装箱结果将如图2右所示。<br> <br><br><center><img src="/source/joyoi/tyvj-2978/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk3OC9wcm9ibGVtc19pbWFnZXMvMzU3Ny90Mi5ibXA=.bmp"></img></center><br>                                       图2 不同的生产次序导致两种不同的装箱结果<br><br>由于箱子高度有限，如图2左，三个组件已经超过了箱子的高度，这种情况第三个组件及之后的组件需要用新的箱子来装。<br>你的工作是为自动装箱系统编写程序，根据组件生产的次序，输出装完这些组件后，每个箱子的组件堆叠的高度。<br></p> 

 
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
