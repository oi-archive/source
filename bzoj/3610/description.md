
# Description

<div class="content"><div>Alice 和 Marisa 都住在一个巨大的由 N 个路口与 M 条单向小道构成的森林中。Marisa 非常喜</div>
<div>欢到 Alice 家里去玩，但是 Alice 并不喜欢这位鲁莽的来客。Alice 非常擅长观察， 因此每当她发</div>
<div>现 Marisa 走了一条与之前完全相同的路径来到她家时，她就会装作不在家， Marisa 就只好败兴而</div>
<div>归。Marisa 发现了这个秘密，因此她决定每次走不同的路径到 Alice 家。</div>
<div>   Marisa 体力有限，她不想走超过 K 条边到达 Alice 家，并且，每当她走 t（t≤K）条边 到达 </div>
<div>Alice 家时，她需要付出 t2的体力。Marisa 想知道，在 Alice 无论如何都不想接见她 之前（即 </div>
<div>Marisa 无法走一条长度不超过 K 的与之前不同的路径），她会消耗多少体力。</div>
<div>   现在 Marisa 拿到了一张森林的地图，但因为 Marisa 非常笨，她并不知道自己的家和 Alice 的</div>
<div>家在哪一个路口，因此她会给询问你 Q 次，每次询问假如 Marisa 的家的位置在 S 而 Alice 的家</div>
<div>的位置在 T 时的答案。</div>
<div>    一条路径 A 的定义是指一个长度为 P（P 可以为任意正整数或零）的边的序列 Am0,Am1,Am2,…</div>
<div>,AmT-1，其中对于任意 1≤i＜P，有 Ami-1的结束节点是 Ami的起始节点。 </div>
<div>   两条路径 A 和 B 完全相同是指两条路径的长度均为 T 并且对任意 0≤i＜P，有 Ami=Bmi。</div></div>

# Input

<div class="content"><p>输入数据第一行包含四个整数 N,M,K,Q，含义如题所述。 </p>
<div>
<div> 接下来 M 行，每行两个整数 X,Y，表示从第 X 个路口到第 Y 个路口有一条单向小道。</div>
<div>路 口的标号为 1,2,3,…,N，在输入数据第 i+1 行的边的标号为 i。 </div>
<div> 接下来 Q 行，每行两个整数 S 和 T，含义如题所述。 </div>
</div></div>

# Output

<div class="content"><div>对于每个询问，输出一行，表示这次询问的答案。由于 Marisa 接受不了非常大的数， 你只需</div>
<div>
<div>要输出答案模 1,000,000,007 的值。 </div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">#1<br/>
2 0 1 1<br/>
1 2<br/>
<br/>
#2<br/>
2 2 2 1<br/>
1 2<br/>
2 1<br/>
1 1<br/>
<br/>
#3<br/>
2 2 100 1<br/>
1 2<br/>
2 1<br/>
1 2<br/>
<br/>
<br/>
#4<br/>
2 3 100 2<br/>
1 2<br/>
1 2<br/>
2 1<br/>
2 2<br/>
2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">#1<br/>
0<br/>
<br/>
#2<br/>
4<br/>
<br/>
#3<br/>
166650<br/>
<br/>
#4<br/>
632506153<br/>
518794755</span></div>

# Hint

<div class="content"><p></p><p> 对于 100%的数据，2≤N≤100，0≤M≤100,000，0≤K≤1,000,000,000，0≤Q≤10,000， 1≤X，Y，S，T≤N</p><br/>
<div>样例一解释 从 S 到 T 不存在路径  </div><br/>
<div>样例二解释 Marisa 可以重复经过一个路口，即使这个路口就是 Alice 的家或 Marisa 的家 </div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

