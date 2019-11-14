# 

 
 # 题目描述 
<p>
Catch（Catch.pas\c\cpp）<br><br>【题目描述】<br>　　在一个坐标轴上，有M辆坦克，第i辆坦克在时刻0处于pos[i]（pos[i]>0），speed[i]个单位，在时刻k就处于pos[i]+speed[i]*k。原点上有一炮台。炮台有N颗炮弹，在时刻0开始就可以发射炮弹，而且发射的顺序是你来确定的，每次只能发射一颗，一颗炮弹只能用一次。每个炮弹都有一个休息时间rest[i]，如果在某次发射了第i颗炮弹，要间隔rest[i]后才能在发射。一颗炮弹只能消灭范围D(0到D)内的一辆坦克。<br>　　最多能消灭多少辆坦克？<br></p> 

 
 # 输入格式 
<p>
　　输入文件Catch.in第一行：N，M，D(N,M≤1000)<br>　　接下来N行：rest<br>　　接下来M行：pos, speed<br>　　全部都是longint内的正整数。<br></p> 

 
 # 输出格式 
<p>
　　输出文件Catch.out输出最多能消灭坦克数量。</p> 
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
<tr><td>3 3 3
3
2
1
4 1
1 1
2 1
</td><td>2</td></tr></table>
