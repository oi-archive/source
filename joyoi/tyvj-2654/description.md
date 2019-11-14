# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2654/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY1NC9wcm9ibGVtc19pbWFnZXMvMzExMy8xODQzLmpwZw==.jpg"> <br><br><br>給定一個戰場，金字塔，密室的大小資料，還有戰場內每一個方格的地形高度，<br>請寫一個程式來將金字塔放置到戰場中，以及將密室放置於金字塔內使得金字塔<br>的基底高度為所有可能性中的最高。<br></p> 

 
 # 输入格式 
<p>
第一行: 包含6個空白隔開的整數，分別是: m, n, a, b, c ,and d.<br>接下來的 n 行: 每一行包含m個空白隔開的整數，代表一列中方格的地形高度。<br>第一行代表最上方的一列方格(row 1)，最後一行代表最底的一列(row n)。<br>m個整數代表每一列的方格地形高度，從第一行開始<br></p> 

 
 # 输出格式 
<p>
第一行: 必須包含兩個空白隔開的整數表示金字塔基底的左上角座標<br>第一個整數為行數(column)，第二個整數為列數(row)。<br>第二行: 必須包含兩個空白隔開的整數代表密室的左上角座標<br>第一個整數為行數(column)，第二個整數為列數(row)。<br></p> 

 
 # 提示 
<p>
限制條件（CONSTRAINTS）<br>3  < = m  < = 1000 <br>3  < = n  < = 1000 <br>3  < = a  < = m<br>3  < = b  < = n<br>1  < = c  < = a – 2<br>1  < = d  < = b – 2<br><br><br>所有的地形高度都是介於1到100的整數<br><br><br>//暂不要提交....</p> 
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
<tr><td>8 5 5 3 2 1
1 5 10 3 7 1 2 5
6 12 4 4 3 3 1 5
2 4 3 1 6 6 19 8
1 1 1 3 4 2 4 5
6 6 3 3 3 2 2 2
</td><td>4 1
6 2</td></tr></table>
