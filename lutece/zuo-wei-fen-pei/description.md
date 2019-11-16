
# Content

![title](/source/lutece/zuo-wei-fen-pei/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyNy8yMDE3MTEyMTEyNDQ0MDE1ODYucG5n.png)

如图所示，电子科大食堂的桌子均为四人桌。有$N$对异性情侣，$P$名单身男性，$Q$名单身女性需要在食堂里就餐，每个人需要占据一个座位。一对情侣必须坐在同一张桌上，且不能容忍同一桌自己对象旁边的座位或对面的座位出现其他异性。单身男性和单身女性则没有这个要求，问至少需要多少张桌子来满足这$2*N+P+Q$人的就餐要求。

# Standard Input

一行，三个整数$N,P,Q(0<=N<=1000,0<=P<=10000,0<=Q<=100)$，分别代表异性情侣、单身男性和单身女性的数量。

# Standard Output

一行，输出能够满足所有人就餐要求的最少桌子数。

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
<tr><td>1 1 1</td><td>1</td></tr><tr><td>2 3 2</td><td>3</td></tr></table>


# Constraints



# Note

样例$1$，$1$张桌子可以满足所有人的就餐需求。左图为一种合法的安排方式，右图的安排方式则不合法。

![title](/source/lutece/zuo-wei-fen-pei/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyNy8yMDE3MTEyMTEzMTQwODY3OTkucG5n.png)

样例$2$，一共有$2*2+3+2=9$人需要用餐，$2$张桌子显然无法满足所有人的就餐需求，$3$张桌子则可以，下图为一种合法的安排方式。

![title](/source/lutece/zuo-wei-fen-pei/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgyNy8yMDE3MTEyMTEyNTkzOTg0ODgucG5n.png)

# Source


