
# Content

数轴上有N枚炸弹，第i个炸弹在整数坐标Xi处，现在要在某个实数坐标x上添加一个爆炸范围为R的炸弹并引爆，在爆炸范围内（坐标在x-R到x+R之间）的炸弹随即也被引爆，爆炸范围为R-1，于是这些炸弹又引爆了在各自爆炸范围内未被引爆的炸弹，爆炸范围为R-2，依此类推，直到爆炸范围减小到0或以下。求最小的实数R，使得存在这样的实数坐标x，使得所有炸弹都被引爆。

# Standard Input

第一行一个整数N(2<=N<=50000)。
接下来N行，第i行为第i个炸弹的坐标Xi(0<=Xi<=1e9)。

# Standard Output

仅一个实数，即最小的满足条件的R。

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
<tr><td>5
8
10
3
11
1</td><td>3.0</td></tr></table>


# Constraints



# Note



# Source


