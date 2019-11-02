# 

 
 # 题目描述 
<p>
貝希被困在一個三角形的迷宮之中。這個迷宮有N行（1 <= N <= 1000000）。比如下圖是<br>一個3行的迷宮。<br><img border="0" src="/source/joyoi/tyvj-2603/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYwMy9wcm9ibGVtc19pbWFnZXMvMzA0NS8xNzcyXzEuanBn.jpg"><br><br>迷宮的第i行有2*i-1個三角形，從左到右分別編號為（i，1）、（i，2）等等。<br><br>貝希每次可以從一個三角形走到任意一個一個跟當前的三角形有鄰邊的三角形。比如說，如果<br>她目前處於三角形（3，3），那麼，她可以走到三角形（3，2）、（3，4）和（4，4）。貝<br>希每次需要一分鐘的時間來移動到下一個三角形。<br><img border="0" src="/source/joyoi/tyvj-2603/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYwMy9wcm9ibGVtc19pbWFnZXMvMzA0NS8xNzcyXzIuanBn.jpg"><br>農夫約翰發現貝希被困了！於是她跟蹤貝希的iPhone手機（可憐的觸摸屏～），得知貝希目<br>前處於三角形（Si，Sj）。因為約翰對貝希有著無窮無盡的濃濃愛意，所以他希望貝希能盡<br>可能快地回到他的身邊。<br><br>在迷宮的三角形之中，有M（1 <= M <= 10000）個是出口。在任何一個出口都可以讓貝希<br>逃離迷宮。一旦貝希進入一個作為出口的三角形，她用多一分鐘就可以逃離這個迷宮。<br><br>找到一個可以讓貝希逃離迷宮最小時間T，並輸出她應該從哪一個出口逃離迷宮，這個出口記為<br>（OUTi，OUTj）。如果有多個出口同時需要時間T，輸出那個行的編號小的出口，如果仍然有<br>多個出口，輸出那個列的編號小的。<br></p> 

 
 # 输入格式 
<p>
＊第一行：兩個由空格隔開的整數：N和M。<br><br>＊第二行：兩個由空格隔開的整數：Si和Sj。<br><br>＊第三到第M+2行：第i+2行有兩個由空格隔開的整數Ei和Ej，表示三角形（Ei，Ej）是出口。<br><br></p> 

 
 # 输出格式 
<p>
＊第一行：兩個由空格隔開的整數：OUTi和OUTj。<br><br>＊第二行：一個單獨的整數：T。<br><br></p> 
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
2 1
3 5
4 4

</td><td>4 4
4</td></tr></table>
