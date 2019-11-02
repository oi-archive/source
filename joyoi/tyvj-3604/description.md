# 

 
 # 题目描述 
<p>
最近，一个方块填数的游戏风靡全球：<br>	给定一个n*m的方块。n行从上到下标号为1到n，m列从左到右标号为1到m。如果一个方格所在的行的标号和所在的列的标号都是奇数，那么该方格就称为奇方格。游戏的开始所有的奇方格中都填上了数。你需要在其他的方格里填数，如果填完数后，方块满足下面条件，你就赢得了这个游戏：<br>1、	任意一个a1*b1的子方块中所有数的和大于0；<br>2、	任意一个a2*b2的子方块中所有数的和小于0；<br>其中，a1、b1、a2、b2都是在游戏的开始给定的。一个a*b的子方块是指行标号在i（1≤i≤n-a+1）到i+a-1之间，列标号在j(1≤j≤m-b+1)到j+b-1之间的所有的方格的集合。<br>小P很喜欢这种游戏，他希望你帮助写一个程序给出一种填数的方案，或者告诉他这样的方案不存在。<br></p> 

 
 # 输入格式 
<p>
<img border="0" src="/source/joyoi/tyvj-3604/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYwNC9wcm9ibGVtc19pbWFnZXMvMjQ1Mi8xMTU0XzEuanBn.jpg"><br></p> 

 
 # 输出格式 
<p>
如果填数方案不存在，输出一行“No”。<br>如果填数方案存在，第一行输出“Yes”。<br>接下来的n行，每一行有用空格分开的m个整数，描述一个填数方案。输出的每一个整数必须在-109到109之间。<br></p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-3604/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYwNC9wcm9ibGVtc19pbWFnZXMvMjQ1Mi8xMTU0XzIuanBn.jpg"><br><br>填完数后，任意 2*2 的方块中的数字之和是1；3*3的方块中的数字之和是-1。<br><br></p> 
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
<tr><td>3 3 2 2 3 3
1 1
1 1

</td><td>Yes
1 -1 1
-4 5 -4
1 -1 1
</td></tr></table>
