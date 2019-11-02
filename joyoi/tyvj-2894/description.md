# 

 
 # 题目描述 
<p>
游乐园决定在一个n×m的广场上举办一次颁奖晚会，总管要你帮忙搭建一个舞台。<br>现在给你广场的布置图（规定地图的上方为正北），有些位置需要布置为观众席（记为1），另一些是空地（记为0）。舞台只能在空地上搭建。<br>为了使晚会更加吸引人，平平觉得舞台应该是朝北的h—金字塔形。h—金字塔形舞台是由h个矩形舞台相接而成的，其中后方的矩形舞台的两端必须超出在其前面的矩形舞台，且最小矩形面对的朝向为舞台的方向。下面给出几个实例:<br><br><img src="/source/joyoi/tyvj-2894/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjg5NC9wcm9ibGVtc19pbWFnZXMvMzQ1Ny9wZy5qcGc=.jpg"></img><br>舞台的面积应该尽量大，输出面积最大的朝北h—金字塔形舞台的面积。</p> 

 
 # 输入格式 
<p>
第一行3个整数 n、m、h。<br>接下来n行，每行m个0或1，中间用一个空格隔开。<br></p> 

 
 # 输出格式 
<p>
一个整数，表示最大的朝北的h—金字塔形舞台的面积。<br>如果没有符合题意的h—金字塔形舞台输出0。<br></p> 

 
 # 提示 
<p>
【提示】<br>样例对应的最优方案如下图：<br><br><img src="/source/joyoi/tyvj-2894/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjg5NC9wcm9ibGVtc19pbWFnZXMvMzQ1Ny9wZzIuanBn.jpg"></img><br>【数据规模和约定】<br>对于10％的数据 h=1；<br>对于40％的数据 h≤5；<br>对于100％的数据 h≤20；<br>对于100％的数据 n、m≤100。<br></p> 
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
<tr><td>4 6 2
0 0 1 0 0 1
0 0 0 0 0 0
0 0 1 0 0 0
0 1 1 0 0 0
</td><td>10</td></tr></table>
