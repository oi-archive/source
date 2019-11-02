# 

 
 # 题目描述 
<p>
(*注:宝治punch为一种有多种果汁,香料混合而成的饮料.其中时常还掺入酒. <br>宝治盅punch-bowl就是用来混合各种配料来制作宝治的大碗) <br><br>农夫约翰的牛们得到了一份兼职，设计宝治盅花样。是这样制作的： <br><br>* 先取来一个 W cm x H cm 平板 (3 <= W <= 300, 3 <= H <= 300) <br><br>* 在每个平板上 1 cm x 1 cm 的正方形上，放一个截面为 1 cm x 1 cm <br>的方块，其高度为 B (1 <= B <= 1,000,000,000) <br><br>这些方块被小心的粘在了一起,以使宝治不会从它们中间留出.实际上,它们被粘的 <br>如此的好,以至于角落的方块无足重要. <br><br>但是这些牛不能计算出它们的宝治盅能盛下多少宝治.架设盅是独立的(即盅周围 <br>没有墙围住),计算这个盅可以盛多少果汁.当然某些盅会从边缘露出所有的果汁, <br>只能盛 0. </p> 

 
 # 输入格式 
<p>
* 第一行：两个由空格分开的整数，W 与 H <br>* 第二至H+1行：第i+1行，由W个由空格分开的整数组成，每个代表盅第i行中方 <br>块的高度B。第一个数代表此行第一列的高度，第二个数代表第 <br>二列的高度，如此类推。 <br><br><br><br><br></p> 

 
 # 输出格式 
<p>
<br>* 第一行：一个整数，以毫升为单位的盅容量。 <br><br></p> 
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
<tr><td>4 5
5 8 7 7
5 2 1 5
7 1 7 1
8 9 6 9
9 8 9 9

</td><td>12

OUTPUT DETAILS:

Fill-up the two squares of height 1 to height 5, for 4 cc for each square.
 Fill the square of height 2 to height 5, for 3 cc of joice.  Fill the
square of height 6 to height 7 for 1 cc of juice.  2*4 + 3 + 1 = 12.</td></tr></table>
