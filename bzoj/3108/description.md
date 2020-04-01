
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">给一个n结点m条边的有向图D，可以这样构造图E：给D的每条边u-&gt;v，在E中建立一个点uv，然后对于D中的两条边u-&gt;v和v-&gt;w，在E中从uv向vw连一条有向边。E中不含有其他点和边。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">输入E，你的任务是判断是否存在相应的D。注意，D可以有重边和自环。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行包含测试数据个数T（T&lt;=10）。每组数据前两行为D的边数（即E的点数）m和E的边数k（0&lt;=m&lt;=300）。以下<i>k</i>行每行两个整数x, y，表示E中有一条有向边x-&gt;y。E中的点编号为0~m-1。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">对于每组数据输出一行。如果存在，输出Yes，否则输出No。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2<br/>
1<br/>
0 1<br/>
5<br/>
0<br/>
4<br/>
3<br/>
0 1<br/>
2 1<br/>
2 3<br/>
3<br/>
9<br/>
0 1<br/>
0 2<br/>
1 2<br/>
1 0<br/>
2 0<br/>
2 1<br/>
0 0<br/>
1 1<br/>
2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
Yes<br/>
No<br/>
Yes<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

