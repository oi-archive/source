# 

 
 # 题目描述 
<p>
无聊的自习（ant.pas\c\cpp）<br><br>【题目描述】<br>　　自习课总是做作业做到想睡…<br>　　但是也需要休息…<br>　　xm在休息时发现了杯子外壁有一只蚂蚁(可能是杯子里面的蜂蜜惹的祸…)。于是便注意起这只蚂蚁了…<br>　　这一看他便看出了一个大发现——<br>　　杯子的高度比蚂蚁到达过的最高位置高2cm…(这算什么发现)<br>　　然后他还发现，蚂蚁总是向上或向下走一段距离，然后休息一会儿。<br>　　出于无聊，他记下了每次蚂蚁移动的距离。<br>　　下课了，他屁颠屁颠地去找你，跟你讲了他的发现，然后问你：“我的杯子至少有多高？”<br></p> 

 
 # 输入格式 
<p>
　　输入文件ant.in第一行为一个整数n(0<=n<=1000)，表示xm记下蚂蚁移动的次数。<br>　　第二行有n个整数，第i个数表示蚂蚁第i次移动的距离为di mm。(数据保证移动距离之和小于等于1000，且初始时和最终蚂蚁都在桌面上)<br><br></p> 

 
 # 输出格式 
<p>
　　输出文件ant.out:<br>　　若xm记录的数据有错，则输出“IMPOSSIBLE”。<br>　　否则输出两行。<br>　　第一行输出杯子的高度(单位为mm)。<br>　　第二行输出每次蚂蚁是向上移动还是向下移动(U表示向上，D表示向下)。<br><br></p> 
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
20 20 20 20

</td><td>40
UDUD</td></tr></table>
