
# Description

<div class="content"><p>　　给定一张N个顶点M条边的无向图(顶点编号为1,2,…,n)，每条边上带有权值。所有权值都可以分解成2^a*3^b<br/>
的形式。现在有q个询问，每次询问给定四个参数u、v、a和b，请你求出是否存在一条顶点u到v之间的路径，使得<br/>
路径依次经过的边上的权值的最小公倍数为2^a*3^b。注意：路径可以不是简单路径。下面是一些可能有用的定义<br/>
：最小公倍数：K个数a<sub>1</sub>,a<sub>2</sub>,…,a<sub>k</sub>的最小公倍数是能被每个a<sub>i</sub>整除的最小正整数。路径：路径P:P<sub>1</sub>,P<sub>2</sub>,…,P<sub>k</sub>是顶<br/>
点序列，满足对于任意1&lt;=i&lt;k，节点P<sub>i</sub>和P<sub>i+1</sub>之间都有边相连。简单路径：如果路径P:P<sub>1</sub>,P<sub>2</sub>,…,P<sub>k</sub>中，对于任意1<br/>
&lt;=s≠t&lt;=k都有Ps≠Pt，那么称路径为简单路径。</p></div>

# Input

<div class="content"><p>　　输入文件的第一行包含两个整数N和M，分别代表图的顶点数和边数。接下来M行，每行包含四个整数u、v、a、<br/>
b代表一条顶点u和v之间、权值为2^a*3^b的边。接下来一行包含一个整数q，代表询问数。接下来q行，每行包含四<br/>
个整数u、v、a和b，代表一次询问。询问内容请参见问题描述。1&lt;=n,q&lt;=50000、1&lt;=m&lt;=100000、0&lt;=a,b&lt;=10^9</p></div>

# Output

<div class="content"><p>　　对于每次询问，如果存在满足条件的路径，则输出一行Yes，否则输出一行 No（注意：第一个字母大写，其余<br/>
字母小写） 。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 <br/>
1 2 1 3 <br/>
1 3 1 2 <br/>
1 4 2 1 <br/>
2 4 3 2 <br/>
3 4 2 2 <br/>
5 <br/>
1 4 3 3 <br/>
4 2 2 3 <br/>
1 3 2 2 <br/>
2 3 2 2 <br/>
1 3 4 4 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes <br/>
Yes <br/>
Yes <br/>
No <br/>
No </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

