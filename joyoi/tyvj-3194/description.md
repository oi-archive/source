# 

 
 # 题目描述 
<p>
水塔水位（cistern.pas/c/cpp）<br>【题目描述】<br><br><center><img src="/source/joyoi/tyvj-3194/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE5NC9wcm9ibGVtc19pbWFnZXMvMTU2NC9wMS5qcGc=.jpg"></img></center><br>     由于人类对水资源无节制的开发和浪费，到下个世纪，世界上的某些地区会经历严重的水资源缺乏。出于最坏的打算，一个叫Uqbar的小镇已经为即将到来的危机着手准备了。他们建立了一个水管网络，将小镇上所有的水塔连了起来。因此，现在可以通过对唯一的一个入口注水就将所有的水塔灌满。<br>所有的水塔都是长方体的，容积不一，处于的水平高度也不尽相同。因此，往这些水塔注水时，总是那些位置比较靠下的水塔先被装上水，如图所示：<br><br>    现在要求你写一个程序，对于给出的水塔和要注的水量，计算出水平面所处的高度；当然，如果要注的水大于所有水塔的容积之和，输出溢出即可。简单起见，所有管子的容积我们都可以忽略不计。<br></p> 

 
 # 输入格式 
<p>
     输入数据第一行有一个整数n，表示一共有多少个水塔。接下来的n行，每行包含四个非负整数b, h, w, d，对应每一个水塔的信息。b表示水塔底部距离地面的距离；h表示水塔的高度；w和d分别表示长宽。最后一行，一个整数v表示要注入的水量。<br>注意：1≤n≤50,000，0≤b≤1,000,000，1≤h×w×d≤40,000，1≤v≤2,000,000,000<br></p> 

 
 # 输出格式 
<p>
	若是要求注入的水的容量大于所有水塔的总容积之和，输出OVERFLOW；否则输出水位线的高度（保留两位小数）。</p> 
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
<tr><td>【样例1】
Cistern1.in

4
11 7 5 1
15 6 2 2
5 8 5 1
19 4 8 1
132


【样例2】
Cistern2.in

4
11 7 5 1
15 6 2 2
5 8 5 1
19 4 8 1
78

</td><td>【样例1】
Cistern1.out

OVERFLOW


【样例2】
Cistern2.out

17.00</td></tr></table>
