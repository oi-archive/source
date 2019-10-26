
# Content

平面上有无限个格子，排成一行。小羽将格子由$1$开始从左到右依次编号。

小羽将所有编号为奇数的格子涂为红色，编号为偶数的格子涂为绿色。

![title](/source/lutece/xiao-yu-tu-se/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyNi8yMDE3MTEyMDIwNTEwMzIwMjQucG5n.png)

试问你是否存在一个区间$[L,R]$$(1<=L<=R)$，使得该区间内红色格子的数量为$r$，绿色格子的数量为$g$.

# Standard Input

一行两个整数$r,g(0<=r,g<=100)$，分别代表红色格子和绿色格子的数量。

# Standard Output

如果存在一个区间$[L,R]$满足红色格子的数量为$r$且绿色格子的数量为$g$，请输出“$YES$”；否则，请输出“$NO$”.

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
<tr><td>2 3</td><td>YES</td></tr><tr><td>3 1</td><td>NO</td></tr></table>


# Constraints



# Note

样例$1$，取$L=2$，$R=6$，区间$[2,6]$内$3$、$5$号格子为红色，$2$、$4$、$6$号格子为绿色。满足红色格子数量为$2$，绿色格子数量为$3$的条件，故输出“$YES$”.

样例$2$，不存在一段区间使得红色格子数量为$3$，绿色格子数量为$1$，故输出“$NO$”.

# Source


