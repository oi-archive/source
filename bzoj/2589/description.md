
# Description

<div class="content"><div><span style="font-size: medium">给定一棵N个节点的树，每个点有一个权值，对于M个询问(u,v)，你需要回答u xor lastans和v这两个节点间有多少种不同的点权。其中lastans是上一个询问的答案，初始为0，即第一个询问的u是明文。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<p><span style="font-size: medium"><!-- --></span><style type="text/css"></style></p></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行两个整数N,M。</span></div>
<div><span style="font-size: medium">第二行有N个整数，其中第i个整数表示点i的权值。</span></div>
<div><span style="font-size: medium">后面N-1行每行两个整数(x,y)，表示点x到点y有一条边。</span></div>
<div><span style="font-size: medium">最后M行每行两个整数(u,v)，表示一组询问。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<p><span style="font-size: medium"><!--StartFragment --></span></p>
<div><span style="font-size: medium">数据范围是N&lt;=40000 M&lt;=100000 点权在int范围内  </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">M行，表示每个询问的答案。</span></div>
<div><span style="font-size: medium"><br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8 2<br/>
105 2 9 3 8 5 7 7<br/>
1 2<br/>
1 3<br/>
1 4<br/>
3 5<br/>
3 6<br/>
3 7<br/>
4 8<br/>
2 5<br/>
3 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
4</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium">暴力自重。。。</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢seter">鸣谢seter</a></p></div>

