
# Description

<div class="content"><div>数集S的ForbiddenSum定义为无法用S的某个子集（可以为空）的和表示的最小的非负整数。</div>
<div>例如，S={1,1,3,7}，则它的子集和中包含0(S’=∅)，1(S’={1})，2(S’={1,1})，3(S’={3})，4(S’={1,3})，5(S&#39; = {1, 1, 3})，但是它无法得到6。因此S的ForbiddenSum为6。</div>
<div>给定一个序列A，你的任务是回答该数列的一些子区间所形成的数集的ForbiddenSum是多少。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入数据的第一行包含一个整数N，表示序列的长度。</div>
<div>
<div>接下来一行包含N个数，表示给定的序列A（从1标号）。</div>
<div>接下来一行包含一个整数M，表示询问的组数。</div>
<div>接下来M行，每行一对整数，表示一组询问。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每组询问，输出一行表示对应的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 4 9 10<br/>
5<br/>
1 1<br/>
1 2<br/>
1 3<br/>
1 4<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
4<br/>
8<br/>
8<br/>
8</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1≤N,M≤100000,1≤A_i≤10^9，1≤A_1+A_2+…+A_N≤10^9。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By yts1999">By yts1999</a></p></div>

