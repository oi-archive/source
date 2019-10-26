
# Content

饺子发现身边危机四伏！有$n$个人站在一维平面上，每个人的坐标为$A_i$，能量值为$B_i$。饺子有$c$种方法可以推测出有多少人想吃饺子，请你求出每种方法可以得出的想吃饺子的人数。

# Standard Input

第一行两个值 $n（n\le 10^5), c(c\le 10)$  
接下来$n$行每行两个值$A_i,B_i(1\le A_i\le 10^9,1\le B_i\le 10^4,A_i\le A_j$ $if$ $i<j)$  
接下来$c$行，每行包含三个数$K,function,length$  
其中  
$K$可能为`gt`或者`lt`，代表大于或者小于  
$function$可能为`min`，`max`或者`avg`，代表最小，最大或者平均  
$length$是一个整数$(1\le length\le 10^9)$  
$K,function,length$的意思为对于第$i$号人，如果$B_i$ $K$于$[A_i-length,A_i)$范围内的所有人能量值的$function$值，说明该人想吃饺子，**特别的如果范围内一个人也没有，则这个人不想吃饺子**。

# Standard Output

对于每种方法，输出想吃饺子的人数

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
<tr><td>10 2
60 30
120 28
180 35
240 34
300 40
360 31
420 28
480 2
540 42
600 30
gt avg 7200
lt min 300</td><td>4
2</td></tr></table>


# Constraints



# Note



# Source


