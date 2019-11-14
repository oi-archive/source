
# Content

人赢邱老师和任何男生比，都是不虚的。有一天，邱老师带妹子(们)来到了一个$N$行$M$列平面的小行星。对于每一个着陆地点，邱老师总喜欢带着妹子这样走：假设着陆地点为$(r_0, c_0)$，那么他们下一步只能选择相邻格点，向四周走，即$(r_0–1, c_0)$, $(r_0 + 1, c_0)$, $(r_0, c_0–1)$或$(r_0, c_0 + 1)$。之后的路程必须严格按照**右转**-**前进**-**左转**-**前进**-**右转**......的道路前行。但是由于邱老师很心疼妹子，所以崎岖的山脉不可以到达。当不能前进时必须要原路返回。如下图。

<center>![妹子还是邱老师会泡](/source/lutece/qiu-lao-shi-jiang-lin-xiao-xing-xing/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA4Ni8yMDE1MDQyMzE5MDY1ODUzNTM2LmpwZw==.jpg)</center></br>


问，邱老师在哪里着陆可以游历这颗星球最多的土地，输出可能访问到的最多的格点数。

# Standard Input

第一行一个整数$T$, $0< T\le 20$，表示输入数据的组数。</br>
对于每组数据，第一行有两个整数$N$和$M$，分别表示行数和列数，$0< N,M\le 1000$</br>
下面$N$行，每行$M$个字符($0$或$1$)。</br>
$1$代表可到达的地方，$0$代表山脉(不可到达的地方)。

# Standard Output

对于每一组数据，输出一个整数后换行，表示选择某点着陆后，可能访问到的最多的格点数。

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
<tr><td>2
4 3
111
111
111
111
3 3
111
101
111</td><td>10
4
</td></tr></table>


# Constraints



# Note



# Source


