# 

 
 # 题目描述 
<p>
地母是这个世界上大地的主宰，在她眼中整个大地呈现两行N列这样一个状态（难不成她是对子眼?）。在这个大地上如珍珠般散落着各种宝藏，每个宝藏占据一个格子。不过这个消息让天公知道了，他想抢走这些宝藏。地母决定用”无极“牌帆布盖住这些宝藏。值得注意的是”无极“牌帆布全是矩形状的，而且地母现在手头比较紧，她决定用K块帆布盖住所有的宝藏.现在希望你求出这K块帆布的面积最小总和。<br>输入：<br>第一行给出三个数，分别代表牛的头数M，帆布的张数K，以及整个大地所呈现的列数N<br>1 <= N<= 15,000,000, 1 <= M <= 1000,K<=M<br>下面M行给出两个数，代表每个宝藏所在的位置。<br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers, N, K, and B.<br><br>* Lines 2..N+1: Two space-separated integers in the range (1,1) to<br>        (2,B) giving the  coordinates of the cell containing each cow.<br>         No cell contains more than one cow.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The minimum area required by the K barns in order to cover<br>        all of the cows.<br><br></p> 
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
<tr><td>8 2 9
1 2
1 6
1 7
1 8
1 9
2 2
2 3
2 4

INPUT DETAILS:

As pictured above.

</td><td>10

OUTPUT DETAILS:

As discussed above.</td></tr></table>
