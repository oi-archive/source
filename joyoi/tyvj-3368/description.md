# 

 
 # 题目描述 
<p>
　　NOIP公园中有一个近乎圆形的湖，有100个主要景点分布在湖边，为了方便游客，公园在一些景点之间开设了直通的摩托飞艇摆渡的项目一来减少游客在景点到景点之间所花的时间，二来也可以让游客体验一下惊险刺激的摩托飞艇。果然摩托飞艇摆渡项目大为成功，为了充分满足游客需要，摆渡线路越来越多。不料随着线路的增加，危险性也随之增加。如果两个摆渡线路之宰有交叉（如左图2－7和4－12等），在这两个线路上的飞艇一旦发生碰撞，后果将不堪设想。前不久，就发生过类似的险情。<br>公园的管理层近日做出决定，本着安全第一的原则，在这个湖上取消一些线路，使剩下的任意两条线路在行驶阶段（即不考虑码头）不交叉。同时，考虑到经济效益，他们要求被取消的线路数最小，即保留尽量多的线路。他们希望你能够帮助他们决定应该保留哪些线路。<br><br><center><img src="/source/joyoi/tyvj-3368/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM2OC9wcm9ibGVtc19pbWFnZXMvMjE1NS8xLmpwZw==.jpg"></img></center></p> 

 
 # 输入格式 
<p>
　　输入文件：boat.in，数据的第一行为N，表示现有的线路数。接下来的N行，每行有两个1至100的数a,b，表示a至b之间有飞艇往返。显然a不会等于b，且若a至b有线路，则b至a也必有线路，它们不会同时出现在输入文件中。<br></p> 

 
 # 输出格式 
<p>
　　输出文件：boat.out<br>　　有一行输出，即保留下来的线路的最大值。<br></p> 
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
91　31
1　45
27　5
11　65
43　72
</td><td>3</td></tr></table>
