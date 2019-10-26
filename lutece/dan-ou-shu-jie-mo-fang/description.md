
# Content

奇数阶魔方矩阵。规律如下：
1. 首先，将数$1$置于第一行中间的方格里，然后将相继的数按自然顺序置入右上角的方格内
2. 当前行若是第一行，下一个数应置入最下行右邻列的方格里，就像把最下行移到了第一行的上边似的
3. 当前列是最右列时，下一个数应置入第一列的上邻行的方格里，就像把第一列移到最右列的右边似的
4. 当右上方格已经填有数字或者当前方格在正方形的右上角时，下一个数应置入该方格正下方的相邻方格内

而要构造单偶数阶（$n=2(2m+1)$魔方，可以先将正方形分成四个大小相等的小正方形$A$,$B$,$C$,$D$。记$u=\frac{n}{2}$，用上面的方法，将$1$到$u^2$的正整数在$A$里排成一个魔方，再将$u^2+1$到$2u^2$，$2u^2+1$到$3u^2$，$3u^2+1$到$4u^2$分别在$B$,$C$,$D$里排成魔方。将$A$的正中间行里从第二列起的$m$个方格、其他行里最靠左边的$m$个方格里的数字与$D$中相应的方格中的数字相互交换。然后再将$C$的最右边的$m-1$列的每个方格中的数字与$B$中相应的方格中的数字相互交换。这样就形成了一个单偶数阶魔方。下面各图给出了构造方法与步骤。

![title](/source/lutece/dan-ou-shu-jie-mo-fang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTc2LzIwMTQwOTE5MTgyNTAwMDkxOC5naWY=.gif)

![title](/source/lutece/dan-ou-shu-jie-mo-fang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTc2LzIwMTQwOTE5MTgyNTA2MTkzOS5naWY=.gif)

![title](/source/lutece/dan-ou-shu-jie-mo-fang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTc2LzIwMTQwOTE5MTgyNTExMTQyMTAuZ2lm.gif)

# Standard Input

本题有多组输入数据。第一行是输入数组的组数$T$，每组数据占一行，只一个单偶数$n$。$1\le T\le 10$，$1\le n<100$。

# Standard Output

对应每组数据，应输出一个构造好的魔方，每个元素后应有一个空格，两组输出数据间应有一个空行。

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
<tr><td>1
6</td><td>35 1 6 26 19 24 
3 32 7 21 23 25 
31 9 2 22 27 20 
8 28 33 17 10 15 
30 5 34 12 14 16 
4 36 29 13 18 11</td></tr></table>


# Constraints



# Note



# Source


