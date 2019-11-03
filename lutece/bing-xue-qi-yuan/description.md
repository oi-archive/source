
# Content

艾莎女王又开始用冰雪魔法盖宫殿了。

她决定先造一堵墙，于是释放魔法让形为直角梯形的冰砖从天而降，定入冻土之中。

现在你将回答女王的询问：某段冻土上冰砖的面积。

注：多块冰砖之间会互相重叠，重叠部分要多次计算。

# Standard Input

第一行一个整数 $n$，表示有 $n$ 个冰砖先后定入了冻土之中。

冻土上刚开始并没有冰砖。

接下来 $n$ 行，每行六个整数，$x_{1i},h_{1i},x_{2i},h_{2i},l_i,r_i$。

表示一次如图所示的冰砖下落，并询问在这之后，落在 $[l_i,r_i]$ 内冰砖的总面积。

$2 \leq n \leq 100000,-10^8 \leq l_i<r_i \leq 10^8,-10^8 \leq x_{1i}<x_{2i} \leq 10^8, 0 \leq h_{1i},h_{2i} \leq 10000,x_{2i}-x_{1i} \leq 10^5$

![title](/source/lutece/bing-xue-qi-yuan/img/aHR0cHM6Ly9oZXJhbm8uZ2l0aHViLmlvL2ltYWdlcy9MdXRlY2UvODQzLnBuZw==.png)

# Standard Output

输出 $n$ 行，每行输出一个浮点数，作为对该询问的回答。误差小于 $10^{-6}$ 的回答都被当作正确回答。

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
1 1 3 2 -5 5
2 2 4 1 2 3</td><td>3.0000000
3.50000000</td></tr></table>


# Constraints



# Note

如图是对样例输入的解释。

![title](/source/lutece/bing-xue-qi-yuan/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODQzLzIwMTQwNDIwMDEzMDA4NDc4NS5wbmc=.png)

重叠部分需多次计算。

# Source


