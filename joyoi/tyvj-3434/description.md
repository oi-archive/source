# 

 
 # 题目描述 
<p>
三元链（triple.pas\c\cpp）<br><br>【题目描述】<br>　　三元链是指包含三个数X,W,Y的一个链，一个三元链(X,W,Y)也可以反过来使用，即也可以看作是(Y,W,X)。给你一系列三元链和两个整数A，B，某个连接A和B的链可以看作是某些三元链的一个排列，如：<br>Xi1Wi1Yi1 Xi2Wi2Yi2 Xi3Wi3Yi…………….. Xik-1Wik-1Yik-1 XikWikYik<br>其中要求：<br>　　(1)　Xi1=A<br>　　(2)　Y ik=B<br>　　(3)　对于2<=j<=k,Xij= Yij-1<br>　　(4)　对于1<=j<=k,( Xij,Wij,Yij)或者( Yij,Wij,Xij)是题目中给定的某一三元链。<br>　　(5)　该排列的费用= <img src="/source/joyoi/tyvj-3434/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQzNC9wcm9ibGVtc19pbWFnZXMvMjIzOS8xLmpwZw==.jpg"><br>你的任务是对于给定的A，B输出连接A，B的链的最小费用。<br></p> 

 
 # 输入格式 
<p>
　　输入文件triple.in第一行包含三个整数M,A,B,其中M表示三元链的数量，接下来M行描述三元链，第i+1行包含正整数Xi,Wi,Yi</p> 

 
 # 输出格式 
<p>
　　输出文件triple.out；<br>　　如果A，B之间不存在链，输出“NO”，否则第一行输出“YES”，第二行输出最小费用。</p> 

 
 # 提示 
<p>
【数据说明】<br>　　100%的数据 1<=Xi,Wi,Yi<=2000 and M<=4000000<br></p> 
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
<tr><td>【样例输入1】
9 1 11
1 2 5
5 2 6
1 3 8
8 1 11
1 1 6
10 1 6
11 3 6
10 4 8
10 1 11

【样例输入2】
9 1 2
1 2 5
5 2 6
1 3 8
8 1 11
1 1 6
10 1 6
11 3 6
10 4 8
10 1 11
</td><td>
【样例输出1】
YES

【样例输出1】
NO
</td></tr></table>
