# 

 
 # 题目描述 
参加jsoi冬令营的同学最近发现，由于南航校内修路截断了原来通向计算中心的路，导致去的路程比原先增加了近一公里。而食堂门前施工虽然也截断了原来通向计算中心的路，却没有使路程增加，因为可以找到同样长度的路作替代。其实，问题的关键在于，路截断的地方是交通要点。<BR>&nbsp;&nbsp;&nbsp;&nbsp;同样的情况也出现在城市间的交通中。某些城市如果出了问题，可能会引起其他很多城市的交通不便。另一些城市则影响不到别的城市的交通。jsoi冬令营的同学发现这是一个有趣的问题，于是决定研究这个问题。<BR>&nbsp;&nbsp;&nbsp;&nbsp;他们认为这样的城市是重要的：如果一个城市c被破坏后，存在两个不同的城市a和b（a,&nbsp;b均不等于c），a到b的最短距离增长了（或不通），则城市c是重要的。<BR>jsoi冬令营的同学面对着一张教练组交给他们的城市间交通图，他们希望能找出所有重要的城市。现在就请你来解决这个问题。<BR> 

 
 # 输入格式 
第一行两个整数N,&nbsp;M（N&nbsp;&lt;=&nbsp;200），N表示城市数，M表示城市间的道路数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下N行，每行三个整数s,&nbsp;t和len。表示城市s到城市t之间存在一条道路，长度为len。（s和t是1到N的整数，1&nbsp;&lt;=&nbsp;len&nbsp;&lt;=&nbsp;10000）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;两个城市间可能存在多条道路。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;一行，若干个整数，按递增次序列出所有重要城市的编号。相临两个整数间用一个空格分隔，行尾不要输出多余空格。<BR>&nbsp;&nbsp;&nbsp;如果不存在重要城市，则输出一行“No&nbsp;important&nbsp;cities.”<BR> 

 
 # 提示 
//&nbsp;城市2是重要的。因为城市2被破坏后，城市1到城市3的最短距离由2增加到4。 
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
<tr><td>4 4
1 2 1
2 3 1
4 1 2
4 3 2
</td><td>2</td></tr></table>
