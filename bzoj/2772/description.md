
# Description

<div class="content"><div><span style="font-size: medium"><span style="color: black">已知一个无向图，现在有若干个询问请你回答：</span></span></div>
<div><span style="font-size: medium"><span style="color: black">       1</span><span style="color: black">．</span><span style="color: black">A B G1 G2</span><span style="color: black">求从</span><span style="color: black">A</span><span style="color: black">到Ｂ是否能不通过</span><span style="color: black">G1-G2</span><span style="color: black">这条已经存在的边</span></span></div>
<div><span style="font-size: medium"><span style="color: black">       2</span><span style="color: black">．</span><span style="color: black">A B C</span><span style="color: black">求从</span><span style="color: black">A</span><span style="color: black">到</span><span style="color: black">B</span><span style="color: black">能否不通过</span><span style="color: black">C</span><span style="color: black">这个点</span></span></div></div>

# Input

<div class="content"><div><span style="font-size: medium"><span style="color: black">       N M</span><span style="color: black">表示点数和边数</span></span></div>
<div><span style="font-size: medium"><span style="color: black">       </span><span style="color: black">下接</span><span style="color: black">M</span><span style="color: black">行，每行两个数表示一条边</span></span></div>
<div><span style="font-size: medium"><span style="color: black">       </span><span style="color: black">接下来一个数</span><span style="color: black">Q</span><span style="color: black">表示问题总数</span></span></div>
<div><span style="font-size: medium"><span style="color: black">       </span><span style="color: black">下面</span><span style="color: black">Q</span><span style="color: black">行每行开头一个数</span><span style="color: black">k</span><span style="color: black">表示询问的种类，如果是</span><span style="color: black">1</span><span style="color: black">就是第一种询问，后面接四个数表示</span><span style="color: black">A</span><span style="color: black">，</span><span style="color: black">B</span><span style="color: black">，</span><span style="color: black">G1</span><span style="color: black">，</span><span style="color: black">G2</span><span style="color: black">；如果是</span><span style="color: black">2</span><span style="color: black">就是第二种询问，后面接三个数</span><span style="color: black">A,B,C</span><span style="color: black">。</span></span></div>
<div><span style="font-size: medium"><span style="color: black">       </span></span></div>
<div><span style="font-size: medium"><span style="color: black">      </span></span></div></div>

# Output

<div class="content"><p> </p>
<div><span style="font-size: medium"><span style="color: black">       </span><span style="color: black">对于每一个询问如果答案是是则输出一行</span><span style="color: black">yes</span><span style="color: black">否则输出一行</span><span style="color: black">no</span></span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"><span style="color: black">    </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
    13 15<br/>
1 2<br/>
2 3<br/>
3 5<br/>
2 4<br/>
4 6<br/>
2 6<br/>
1 4<br/>
1 7<br/>
7 8<br/>
7 9<br/>
7 10<br/>
8 11<br/>
8 12<br/>
9 12<br/>
12 13<br/>
5<br/>
1 5 13 1 2<br/>
1 6 2 1 4<br/>
1 13 6 7 8<br/>
2 13 6 7<br/>
2 13 6 8<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
yes<br/>
yes<br/>
yes<br/>
no<br/>
yes<br/>
 </span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据Q&lt;=300000，2&lt;=N&lt;=100000，1&lt;=M&lt;=500000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

