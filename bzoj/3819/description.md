
# Description

<div class="content"><div>药剂师 Luo 是液态爆炸物方面的专家，在他的实验室里有 n 类液态药剂，每一类液态药剂都有很多副，这些药剂由四种化学元素组成, 这里依次称之为 alpha, beta, gamma, delta, 每一类药剂都只由这四种液态化学元素组成，这里我们认为第 i 类药剂依次含有的这四种元素 ai，bi，ci，di 克.</div>
<div>药剂师 Luo 经常收到两类客户要求:</div>
<div>第一类是要求混合一副药剂, 依次含有 A, B, C, D 克的 alpha, beta, gamma, delta 元素。</div>
<div>第二类是要求配制出能在特定环境下爆炸的药剂，环境参数为 A, B, C, D，如果一副药剂含有 a, b, c, d 克指定元素，那么当 A⋅a+B⋅b+C⋅c+D⋅d≥0 时，该药剂可以在此环境下引爆。</div>
<div>当药剂师 Luo 在混合两副药剂的时候，他可以从两副药剂中称出任意克然后进行混合。</div>
<div>显然有一些要求药剂师 Luo 是不可能完成的，Luo 需要你来帮忙计算这个要求是否可以完成。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数 N, 表示 Luo 有的药剂种类。</div>
<div>接下来 N 行, 每行 4 个数 ai, bi, ci, di，代表了这个药剂四种元素的含量。</div>
<div>接下来一行一个数 M, 代表客户请求数。</div>
<div>接下来 M 行每行五个数 q,A,B,C,D。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一共 M 行，依次代表每个请求是否可以完成，如果可以完成则输出 “Y”，否则输出 “N”。 (不包含引号)</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 0 0 0<br/>
0 1 0 0<br/>
0 0 1 0<br/>
0 0 0 1<br/>
4<br/>
1 1 2 3 4<br/>
1 2 1 3 4<br/>
2 1 1 1 1<br/>
2 -1 -1 -1 -1</span></div>

# Sample Output

<div class="content"><span class="sampledata">Y<br/>
Y<br/>
Y<br/>
N</span></div>

# Hint

<div class="content"><p></p><div>对于 100% 的数据 4≤N≤50000,M≤100000。</div><br/>
<div></div><br/>
<div>ai,bi,ci,di,A,B,C,D 的绝对值小于 10^9。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年国家集训队测试">2015年国家集训队测试</a></p></div>

