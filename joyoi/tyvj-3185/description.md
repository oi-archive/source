# 

 
 # 题目描述 
<p>
　　z小镇是一个景色宜人的地方，吸引来自各地的观光客来此旅游观光。z小镇附近共有n个景点（编号为1,2,3,…,n），这些景点被m条道路连接着，所有道路都是双向的，两个景点之间可能有多条道路。也许是为了保护该地的旅游资源，z小镇有个奇怪的规定，就是对于一条给定的公路ri，任何在该公路上行驶的车辆速度必须为vi。速度变化太快使得游客们很不舒服，因此从一个景点前往另一个景点的时候，大家都希望选择行使过程中最大速度和最小速度的比尽可能小的路线，也就是所谓最舒适的路线。<br></p> 

 
 # 输入格式 
<p>
　　输入文件(comf.in)<br>　　第一行包含两个正整数，n和m。<br>　　接下来的m行每行包含三个正整数：x，y和v。表示景点x到景点y之间有一条双向公路，车辆必须以速度v在该公路上行驶。<br>　　最后一行包含两个正整数s，t，表示想知道从景点s到景点t最大最小速度比最小的路径。s和t不可能相同。<br></p> 

 
 # 输出格式 
<p>
　　输出文件(comf.out)<br>　　如果景点s到景点t没有路径，输出“IMPOSSIBLE”。否则输出一个数，表示最小的速度比。如果需要，输出一个既约分数。<br></p> 

 
 # 提示 
<p>
样例二：<br>sample input<br>3 3<br>1 2 10<br>1 2 5<br>2 3 8<br>1 3<br><br>sample output<br>5/4<br><br><br>样例三：<br>sample input<br>3 2<br>1 2 2<br>2 3 4<br>1 3<br><br>sample output<br>2<br><br>数据范围：<br>　　1 < n ≤ 500；1 ≤ x,y ≤ n，0 < v < 30000，x≠y；0 < m ≤ 5000。<br><br>解题提示：<br>　　按速度由大到小排序，把依次加入边。<br></p> 
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
<tr><td>4 2
1 2 1
3 4 2
1 4
</td><td>IMPOSSIBLE</td></tr></table>
