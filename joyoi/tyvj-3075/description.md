# 

 
 # 题目描述 
<p>
　　设有一棵二叉树，如图5-1：<br><br><center><img src="/source/joyoi/tyvj-3075/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA3NS9wcm9ibGVtc19pbWFnZXMvMTIzMC8xLmJtcA==.bmp"></img></center><br>　　其中，圈中的数字表示结点中居民的人口。圈边上数字表示结点编号，现在要求在某个结点上建立一个医院，使所有居民所走的路程之和为最小，同时约定，相邻接点之间的距离为l。如上图中，若医院建在：<br></p> 

 
 # 输入格式 
<p>
　　第一行一个整数n，表示树的结点数。(n≤100)<br>　　接下来的n行每行描述了一个结点的状况，包含三个整数，整数之间用空格(一个或多个)分隔，其中：第一个数为居民人口数；第二个数为左链接，为0表示无链接；第三个数为右链接。<br></p> 

 
 # 输出格式 
<p>
　　一个整数，表示最小距离和。</p> 

 
 # 提示 
<p>
　　本题的求解任务十分明了：求一个最小路径之和。<br>　　根据题意，对n个结点，共有n个路径之和：用记号Si表示通向结点i的路径之和，则 ，其中Wj为结点j的居民数，g(i,j)为结点j到结点i的最短路径长度。下面表中反映的是样例的各项数据：<br>j<br>g(i,j)<br>i	1	2	3	4	5	Si<br>1	0	1	1	2	2	0×13+1×4+1×12+2×20+2×40=136<br>2	1	0	2	3	3	1×13+0×4+2×12+3×20+3×40=217<br>3	1	2	0	1	1	1×13+2×4+0×12+1×20+1×40=81<br>4	2	3	1	0	2	2×13+3×4+1×12+0×20+2×40=130<br>5	2	3	1	2	0	2×13+3×4+1×12+2×20+0×40=90<br> <br>　　从表中可知S3=81最小，医院应建在3号居民点，使得所有居民走的路径之和为最小。<br>　　由此可知，本题的关键是求g[i,j]，即图中任意两点间的最短路径长度。<br>　　求任意两点间的最短路径采用下面的弗洛伊德（Floyd）算法。<br>　　（1）数据结构：<br>　　　　w:array[1..100]of longing;　　　　　　　描述个居民点人口数<br>　　　　g:array[1..100, 1..100]of longint　　　　初值为图的邻接矩阵，最终为最短路径长度<br>　　（2）数据的读入：<br>　　　　本题数据结构的原形为二叉树，数据提供为孩子标识法，分支长度为1，建立带权图的邻接矩阵，分下面两步：<br>　　　　　①g[i,j]←Max　　　　　　　{Max为一较大数，表示结点i与j之间无直接相连边}<br>　　　　　②读入n个结点信息：<br>　　for i:=1 to n do<br>　　　begin<br>　　　　　g[i,j]:=0;<br>　　　　　readln(w[i],l,r);<br>　　　　　if l>0 then begin<br>　　　　　　　　 g[i,l]:=l;	　　g[l,i]:=l<br>　　　　　 end;<br>　　if r>0 then begin<br>　　　　g[i,r]:=l;	　　　g[r,i]:=l<br>　　end;<br>　　（3）弗洛伊德算法求任意两点间的最短路径长度<br>　　　　for k:=1 to n do<br>　　　　　　for i:=1 to n do<br>　　　　　　　　if i<>k then for j:=1 to n do<br>　　　　　　　　　　if (i<>j)and(k<>j)and(g[i,k]+g[k,j]<g[i,j])  then g[i,j]:=g[i,k]+g[k,j];<br>　　（4）求最小的路程和min<br>　　　　min:=max longint;<br>　　　　for i:=1 to n do<br>　　　　　begin<br>　　　　　　　sum:=0;<br>　　　　　　　for j:=1 to n do sum:=sum+w[i]*g[i,j];<br>　　　　　　　if sum<min then min:=sum;<br>　　　　　end;<br>　　（5）输出<br>　　　　　writeln(min);<br></p> 
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
<tr><td>5						
13 2 3
4 0 0
12 4 5
20 0 0
40 0 0
</td><td>81</td></tr></table>
