
# Description

<div class="content"><div>简单路径是指没有重复经过同一个点的路径。</div>
<div>给定一个n个点，m条边的简单无向图，问是否能找到两个不同的点S和T，满足S和T之间存在至少三条不同的简单路径。</div>
<div>这三条简单路经之间也不能有重复的边。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入数据的第一行包含一个正整数Case(1&lt;=Case&lt;=100000)，表示测试数据的组数。</div>
<div>每组数据第一行包含两个正整数n,m(1&lt;=n,m&lt;=100000)，分别表示点数和边数。</div>
<div>接下来m行，每行两个正整数u_i,v_i(1&lt;=u_i&lt;v_i&lt;=n)，表示一条无向边。</div>
<div>输入数据保证不存在重边和自环，且sum n,sum m&lt;=100000。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，若无解，输出-1，否则第一行输出两个正整数S和T。</div>
<div>接下来3行描述3条S到T的路径，每行先输出一个正整数t，表示路径上的点数，然后依次从S输出到T路径上的每个点。</div>
<div>若有多组解，输出任意一组。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
6 6<br/>
3 6<br/>
3 4<br/>
1 4<br/>
1 2<br/>
1 3<br/>
2 3<br/>
3 1<br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 3<br/>
3 1 2 3<br/>
2 1 3<br/>
3 1 4 3<br/>
-1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供翻译及SPJ">鸣谢Claris提供翻译及SPJ</a></p></div>

