# 

 
 # 题目描述 
<p>
【题目描述】(block.cpp/c/pas)<br>　　春春幼儿园举办了一年一度的“积木大赛”。今年比赛的内容是搭建一座宽度为n的大厦，大厦可以看成由n块宽度为1的积木组成，第i块积木的最终高度需要是hi 。<br>　　在搭建开始之前，没有任何积木（可以看成n块高度为 0 的积木）。接下来每次操作，小朋友们可以选择一段连续区间[L, R]，然后将第L到第R块之间（含第 L 块和第 R 块）所有积木的高度分别增加1。<br>　　小M是个聪明的小朋友，她很快想出了建造大厦的最佳策略，使得建造所需的操作次数最少。但她不是一个勤于动手的孩子，所以想请你帮忙实现这个策略，并求出最少的操作次数。<br></p> 

 
 # 输入格式 
<p>
输入文件为 block.in<br>输入包含两行，第一行包含一个整数n，表示大厦的宽度。<br>第二行包含n个整数，第i个整数为hi 。<br></p> 

 
 # 输出格式 
<p>
输出文件为 block.out<br>仅一行，即建造所需的最少操作数。<br></p> 

 
 # 提示 
<p>
【样例解释】<br>其中一种可行的最佳方案，依次选择<br>[1,5] [1,3] [2,3] [3,3] [5,5]<br><br>【数据范围】<br>对于 30%的数据，有1 ≤ n ≤ 10；<br>对于 70%的数据，有1 ≤ n ≤ 1000；<br>对于 100%的数据，有1 ≤ n ≤ 100000，0 ≤ hi ≤ 10000。<br></p> 
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
23412
</td><td>5</td></tr></table>
