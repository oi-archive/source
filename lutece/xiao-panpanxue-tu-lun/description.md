
# Content

小panpan不会图论，所以图论专题他非常刻苦地学习图论。

今天他认真地学习了萌神的ppt，学习了一下Floyd算法，手持两把锟斤拷的他，
口中疾呼烫烫烫，马上找了到OJ上找了道FLoyd的题:

> $n$个点，$m$边的无向连通图，无重边，无自环，每条边的长度都是1，求任意两点之间的最短距离
> 
>  —— 出题人acerlawson

小panpan想了想，写了段代码交了上去，他得到了AC！

出题人acerlawson看了一下小panpan的程序，发现他写了个错误的Floyd，
他选了`k`个点出来，存在`a[]`数组里，核心代码如下：
```
d[i][j] // i,j之间的最短距离
a[i]    // 小panpan事先选好的点

for (int i = 1; i <= n; i++) {
    for (int j = 1; j <= n; j++) {
        if (i == j)
            d[i][j] = 0;
        else
            d[i][j] = INF;   
    }
}    

for (int i = 1; i <= m; i++) {
    scanf("%d%d", &u, &v);
    d[u][v] = 1;
    d[v][u] = 1;
}

for (int r = 1; r <= k; r++) {
    v = a[r];
    for (int i = 1; i <= n; i++)
        for (int j = 1; j <= n; j++)
            d[i][j] = min(d[i][j], d[i][v] + d[v][j]);
}
```
因为数据**太水了**，所以小panpan得到了AC。
为了让小panpan`WA`掉，acerlawson想要出一组数据卡掉小panpan的代码，但是acerlawson忙于陪妹子，所以他找你帮忙。

给出一个$n$个点$m$条边的**无重边无自环**的**无向连通图**，让小panpan的代码得到`Wrong Answer`。

# Standard Input

第一行为三个整数$n, m, k(3\leq n\leq 400, n-1\leq m\leq \frac{n(n-1)}{2}, 2\leq k\leq n)$，分别表示图的顶点数，边数和小panpan选的点的数量

第二行k个整数$x_1, x_2, ... , x_k$，($1\leq x_i\leq n$)，表示小panpan选的点

# Standard Output

$输出m行，每行两个整数u和v，表示一条无向边(u, v)$

如果有多个解，输出任意可行解

如果无论如何小panpan都能AC，则输出`No`

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
<tr><td>4 3 2
1 2 </td><td>1 3
2 3
2 4</td></tr><tr><td>4 3 4
1 2 3 4</td><td>No</td></tr></table>


# Constraints



# Note



# Source


