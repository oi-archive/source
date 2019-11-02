# 

 
 # 题目描述 
<p>
在完成了古越州圆盘密码的研究之后，考古学家小布来到了南美大陆的西部。相传很久以前在这片土地上生活着两个部落，一个部落崇拜闪电，另一个部落崇拜高山，他们分别用闪电和山峰的形状作为各自部落的图腾。<br>小布的团队在山洞里发现了一幅巨大的壁画，壁画上被标记出了N个点，经测量发现这N个点的水平位置和竖直位置是两两不同的。小布认为这幅壁画所包含的信息仅与这N个点的相对位置有关，因此不妨设坐标分别为(1, y1) , (2, y2), ..., (n, yn)，其中y1~yn是1~N的一个排列。<br>小布的团队打算研究在这幅壁画中包含着多少个图腾，其中闪电图腾的定义图示如下（图腾的形式只与4个纵坐标值的相对大小排列顺序有关）：<br><img border="0" src="/source/joyoi/tyvj-3594/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzU5NC9wcm9ibGVtc19pbWFnZXMvMjQ0My8xMTQ1XzEuanBn.jpg"><br><br>崇拜高山的部落有两个氏族，因而山峰图腾有如下两种形式，左边为A类，右边为B类（同样，图腾的形式也都只与4个纵坐标值的大小排列顺序有关）：<br><br><img border="0" src="/source/joyoi/tyvj-3594/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzU5NC9wcm9ibGVtc19pbWFnZXMvMjQ0My8xMTQ1XzIuanBn.jpg"><br>     <br>小布的团队希望知道，这N个点中两个部落图腾数目的差值。因此在本题中，你需要帮助小布的团队编写一个程序，计算闪电图腾数目减去山峰图腾数目的值，由于该值可能绝对值较大，本题中只需输出该值对16777216的余数（注意余数必为正值，例如-1对16777216的余数为16777215）。<br></p> 

 
 # 输入格式 
<p>
第一行包含一个整数N，为点的数目。<br>接下来一行包含N个整数，分别为y1, y2, …, yn。保证y1, y2, …, yn是1~N的一个排列。<br></p> 

 
 # 输出格式 
<p>
仅包含一个数，表示闪电图腾数目与山峰图腾数目的差值对16777216的余数。<br></p> 

 
 # 提示 
<p>
样例一中共有1个闪电图腾（1324）和1个B类山峰图腾（1532）。<br>样例二中仅有一个A类山峰图腾（1243），故差值为-1，答案为16777215。<br>【数据规模】<br>对于10%的数据，N  ≤ 600；<br>对于40%的数据，N  ≤ 5000；<br>对于100%的数据，N ≤ 200000。<br></p> 
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
<tr><td>【样例输入一】
       5
       1 5 3 2 4
【样例输入二】
       4
       1 2 4 3
</td><td>
【样例输出一】
0

【样例输出二】
16777215
</td></tr></table>
