
# Description

<div class="content"><p><span style="font-size: medium">计算神经学作为新兴的交叉学科近些年来一直是学术界的热点。一种叫做SHOI 的神经组织因为其和近日发现的化合物 SHTSC 的密切联系引起了人们的极大关注。<br/>
SHOI 组织由若干个 SHOI 细胞构成,SHOI 细胞之间形成严密的树形结构。<br/>
每个 SHOI 细胞都有且只有一个输出端,被称为轴突,除了一个特殊的、被称为根细胞的 SHOI 细胞的输出作为整个组织的输出以外,其余细胞的轴突均连向其上级 SHOI 细胞;并且有且只有三个接收端,被称为树突,从其下级细胞或者其它神经组织那里接收信息。SHOI 细胞的信号机制较为简单,仅有 0 和 1 两种。每个 SHOI 细胞根据三个输入端中 0 和 1 信号的多寡输出较多的那一种。<br/>
现在给出了一段 SHOI 组织的信息,以及外部神经组织的输入变化情况。请你模拟 SHOI 组织的输出结果。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行一个整数:n。表示 SHOI 组织的总细胞个数。SHOI 细胞由 1~n 编号,编号为 1 的是根细胞。<br/>
从第二行开始的 n 行,每行三个整数 x1, x2, x3,分别表示编号为 1~n 的 SHOI 细胞的树突连接。1&lt;xi≤n 表示连向编号为 xi 的细胞的轴突, n&lt;xi≤3n+1 表示连向编号为 xi 的外界输入。输入数据保证给出的 SHOI 组织是合法的且所有的 xi 两两不同。<br/>
接下来一行 2n+1 个 0/1 的整数,表示初始时的外界输入。<br/>
第 n+3 行有一个整数:q,表示总操作数。<br/>
之后 q 行每行一个整数 x,表示编号为 x 的外界输入发生了变化。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出 q 行每行一个整数,对应第 i 次外界输入变化后的根细胞的输出。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
2 3 4 <br/>
5 6 7 <br/>
8 9 10 <br/>
0 0 0 0 1 1 1 <br/>
5 <br/>
4 <br/>
4 <br/>
5 <br/>
6 <br/>
8 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
0<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于 100%的数据,n≤500000,q≤500000。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

