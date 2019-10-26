
# Content

喵哈哈村的希婆婆有个旺财树，旺财树上挂满了灯泡，因为快到了一年一度的神蛋节了。

我们可以抽象的认为旺财树的灯泡散布在一个三维空间$(X,Y,Z)$中，这个三维空间每一个整点都有一个灯。

假设$(x,y,z)$是灯的坐标，显然点坐标满足$1 <= x <= X$ 且 $1 <= y <= Y$ 且 $1 <= z <= Z$。

注意，初始时，灯都是不亮的。

希婆婆会进行$k$次操作。

我们对一次操作的定义如下：

<1>:在这个三维空间中等概率的随机选择一个整点,我们不妨设这个点为A$(X1,Y1,Z1)$。

<2>:再次在这个三维空间中等概率的随机选择一个整点，我们不妨设这个点为B$(X2,Y2,Z2)$。

<3>:改变在这个三维空间中所有满足下列条件灯的状态（亮变为不亮，不亮变为亮）

即满足$min(X1,X2) <= x <= max(X1,X2)$ & $min(Y1 , Y2) <= y <= max(Y1,Y2)$ & $min(Z1,Z2) <= z <= max(Z1,Z2)$（符号&表示且）条件的灯泡都会改变。

现在给你这个三维空间的大小$X,Y,Z ( X , Y , Z <= 100 且 X , Y ,Z >= 1)$ ,和操作次数 $K (K <= 5 且 K >= 0)$ ，问在$K$次操作后，这个三维空间中灯亮的数学期望。

喵，就是这样。

沈宝宝可是早就知道答案是多少了哦，你知道吗？

# Standard Input

输入数据只有一行，包含有4个整数，X,Y,Z,K.

# Standard Output

输出仅一行，代表K次操作后灯亮的数学期望值。（误差在10-6以内将被忽略）

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
<tr><td>2 2 1 1</td><td>2.250000000</td></tr></table>


# Constraints



# Note

by Xiper

# Source


