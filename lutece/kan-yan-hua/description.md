
# Content

小a在不开心的时候喜欢看烟花，于是在节日里来到了一个小城镇。一个城镇有n个区域，从左到右1编号为n，每个区域之间距离1个单位距离。这一晚有m个烟火要放，给定放的地点a[i] 、时间t[i]  ,如果小a当时在区域x，那么可以获得b[i] - | a[i]  - x |的开心值。小a每个单位时间可以移动不超过d个单位距离。小a的初始位置没有限制（初始时刻为1），求小a这一晚通过移动能获取到的最大的开心值。

# Standard Input

第一行包含3个整数n, m, d (1≤n≤150000; 1≤m≤300; 1≤d≤n).

接下来m行，每行包含3个整数， a[i] , b[i] , t[i]  (1≤a[i] ≤n; 1≤b[i] ≤10^9; 1≤t[i] ≤10^9）

输入保证t[i]≤t[i+1] (1≤i＜m)

# Standard Output

一个整数，表示最大开心值。

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
<tr><td>10 2 1
1 1000 4
9 1000 4</td><td>1992</td></tr></table>


# Constraints



# Note



# Source


