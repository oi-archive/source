# 

 
 # 题目描述 
<p>
矿泉水（spring）<br>【题目描述】<br>　　Hewr 又回到了三鑫。<br>　　但是他发现，电脑室里面只有一台饮水机，他有 n 只水杯（众人哗然 ~ ），因为 他喜欢好事成双，所以他又偶数只杯。 Hewr 常常带 2 只空水杯去打水，每次都把水装到极限（假设水量无穷）。设 Hewr 拿的水杯是 x 和 y ，则他需要 time[x,y] 分钟。<br>　　Hewr 想要在最少的时间内用自己的力量把桌子上所有的空杯装满。 Hewr 觉得 这是个难题，于是来找你帮忙。<br></p> 

 
 # 输入格式 
<p>
　　第一行有一个数字，是 n 。<br>　　接下来 n 行，每行 n 个数字，代表了 time 矩阵。 time 矩阵中每一个数都是正 整数，且 time 矩阵中 time[i,i] 是没有用的。（注意： time[i,j]=time[j,i] ）<br></p> 

 
 # 输出格式 
<p>
　　仅包含一行，就是最佳 打 水方案的最少时间。</p> 

 
 # 提示 
<p>
【数据规模】<br>　　100% 的数据中， time 矩阵中的每一个数字小于等于 32768 。<br>　　100% 的数据中， n >= 4 ；<br>　　40% 的数据中， n <= 12 ；<br>　　100% 的数据中， n <= 18 。<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>解题报告：矿泉水<br>【正解】<br>　　本来第二题是本套题的最难题的 ~ 不过鉴于昨天你们展示了惊人的 “ 水 ” 平，所以特地应 Mr.Xie 的要求把题目换过来了。<br>　　这个题目也没有什么好说的，就是搜索，而且是老题了。<br>　　一句话题解就是：每一次找一对桶，然后深搜，直到找到 n div 2 对桶，求值，递归终结 。<br>【小结】<br>　　这个题目一般可以拿 80 分左右 ……</p> 
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
<tr><td>4
0 100 5 100
100 0 100 11
5 100 0 100
100 11 100 0</td><td>16</td></tr></table>
