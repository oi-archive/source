
# Content

某城市有一个火车站，铁轨铺设如下图。有$n(1 \leq n \leq 1000)$节车厢从A方向驶入车站，按进站顺序编号为$1$~$n$。你的任务是让它们按照某种特定的顺序进入B方向的铁轨并驶出车站。为了重组车厢，你可以借助中转站C。这是一个可以停放任意多节车厢的车站，但由于末端封顶，驶入C的车厢必须按照相反的顺序驶出C。对于每个车厢，一旦从A移入C，就不能再回到A了；一旦从C移入B，就不能回到C了。换句话说，在任意时刻，只有两种选择：A->C和C->B
![Picture1.png)](/source/lutece/huo-che-jin-zhan/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjExNC9QaWN0dXJlMS5wbmc=.png)

# Standard Input

输入有两行

第一行有一个数$n$，代表有$n$节车厢

第二行是$n$个数，分别为$1$~$n$，代表期望你驶出中转站C的顺序

# Standard Output

如果可以，则输出`Yes`，否则，输出`No`。

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
1 2 3 4 5</td><td>Yes</td></tr><tr><td>5
5 4 1 2 3</td><td>No</td></tr><tr><td>6
6 5 4 3 2 1</td><td>Yes</td></tr></table>


# Constraints



# Note



# Source


