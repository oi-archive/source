
# Content

有一台洗牌机，它能以同一种环状方式洗牌，但我们不知道这种方式，还有$13$张牌$A,2,3,4,⋯,10,J,Q,K$（为方便读入，$A→1,J,Q,K→11,12,13$）。如$1→2→8→12→4→3→7→6→13→11→5→10→9$表示在洗一次后，原来的第一张到了现在第二张，原来的第二张到了现在第八张，⋯⋯，**第九张到了现在的第1张**。某天，这台洗牌机出了点毛病，运行一次只能连续洗牌两次，我们知道牌的初始顺序$S_0$和洗牌两次后顺序$S_2$，求洗牌一次后的顺序$S_1$。  
![title](/source/lutece/xi-pai-ji/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgxMS8yMDE3MTEzMDIwNDgzMDMwODI2LmpwZw==.jpg)

# Standard Input

第一行13个数表示初始顺序$S_0$  
第二行13个数表示洗牌两次后顺序$S_2$

# Standard Output

输出13个数表示洗牌一次后顺序$S_1$(请不要在最后一个数后面输出空格 否则可能得到`Presentation Error`的结果)

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
<tr><td>1 2 3 4 5 6 7 8 9 10 11 12 13
10 9 12 8 13 3 4 1 5 11 6 2 7</td><td>9 1 4 12 11 7 3 2 10 5 13 8 6</td></tr></table>


# Constraints



# Note

$1→2→8→12→4→3→7→6→13→11→5→10→9$即为样例的洗牌方式

# Source


