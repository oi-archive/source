
# Description

<div class="content"><p>比特哈顿镇有n*n个格点，形成了一个网格图。一开始整张图是完整的。<br/>
有k次操作，每次会删掉图中的一条边(u,v)，你需要回答在删除这条边之后u和v是否仍然连通。</p></div>

# Input

<div class="content"><p>第一行包含两个正整数n,k(2&lt;=n&lt;=1500,1&lt;=k&lt;=2n(n-1))，表示网格图的大小以及操作的个数。<br/>
接下来k行，每行包含两条信息，每条信息包含两个正整数a,b(1&lt;=a,b&lt;=n)以及一个字符c(c=N或者E)。<br/>
如果c=N，表示删除(a,b)到(a,b+1)这条边；如果c=E，表示删除(a,b)到(a+1,b)这条边。<br/>
数据进行了加密，对于每个操作，如果上一个询问回答为TAK或者这是第一个操作，那么只考虑第一条信息，否则只考虑第二条信息。<br/>
数据保证每条边最多被删除一次。</p></div>

# Output

<div class="content"><p>输出k行，对于每个询问，如果仍然连通，输出TAK，否则输出NIE。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
2 1 E 1 2 N<br/>
2 1 N 1 1 N<br/>
3 1 N 2 1 N<br/>
2 2 N 1 1 N</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
TAK<br/>
NIE<br/>
NIE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供试题">鸣谢Claris提供试题</a></p></div>

