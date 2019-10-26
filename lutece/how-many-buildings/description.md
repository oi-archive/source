
# Content

Kenny在仰望星空，思考怎么拿奥斯卡奖的时候误入了一座奇怪的城市，他很兴奋地照了几张照片。结果当他把照片印出来才发现他根本数不清照片里有几座楼。于是他想了个办法来试着计算一发：

首先，他把照片竖着切成了$n$条，从左到右排成一排。照片里的楼房都可以看成是一个个矩形框，而照片的下边沿就是地面。一座楼房可能会在连续的好几条照片里面出现，但是每条照片里面显示的是该位置最高的楼房的高度，仅凭Kenny的钛合金眼是分辨不出这个位置到底重叠了几座楼的。

然后，他算出了每条照片里面可见楼房的高度。

最后，他要写个程序，求一求至少原图里有几座楼房。为了宇宙的和平，你来求一发吧。

# Standard Input

有多组测试数据，每组数据包括一个整数$n$($1 \leq n \leq 100,000$)，下一行有$n$个整数，也就是从左到右每条照片里楼的高度（$0$代表照片里没有楼房）。所有的输入数据均非负，小于$1,000,000,000$。

# Standard Output

每组Case，先输出Case数，然后输出答案。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>3
1 2 3
3
1 2 1</td><td>Case 1: 3
Case 2: 2</td></tr></table>


# Constraints



# Note



# Source


