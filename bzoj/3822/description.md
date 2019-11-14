
# Description

<div class="content"><div>巨酱和主席是一对好朋友。他们都很喜欢读书，经常一起阅读相关领域书籍，进行系统的学习。一天主席列出了一份列表，里面共 p 本书，其中不乏《约翰克里斯多夫》，《名人传》等名著。作为一名在文学上有很高修养的知名青年，巨酱打算用尽量少的时间把这份列表中的所有书籍都读完。</div>
<div>作为一名文化人，巨酱阅读书籍的方式也与一般人不同。他使用一种叫做“批量阅读”的阅读方式。首先他根据自己的喜好，对每本书给出了个参数 x,y，其中 i 本书的两个参数为 xi,yi。当然，由于巨酱独特的口味，可能有两本不同的书，它们的 x、y 参数均相同。而每次阅读的时候，他会设置三个系数 a, b, c，所有满足 ax+by≤c 的书籍都可以通过这次“批量阅读”读完，这次批量阅读总共需要 w 的时间。</div>
<div>现在，巨酱有 n 种 “批量阅读”的方案，第 i 种“批量阅读”三个参数为 ai,bi,ci，需要的时间为 wi。现在巨酱打算从这 n 种“批量阅读”中选出若干，使得巨酱可以用尽量少的时间读完所有的书。现在我们想知道，巨酱最少用多少时间？</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数 n,p，分别表示“批量阅读”的方案数以及书的数量。</div>
<div>接下来 n 行，每行四个整数，其中第 i 行包含四个整数 ai,bi,ci,wi，表示第 i 种“批量阅读”的方案。</div>
<div>接下来 p 行，每行两个整数，其中第 i 行包含两个整数 xi,yi，表示第 i 本书的参数。</div>
<p></p></div>

# Output

<div class="content"><div>一行一个整数，表示最少需要的时间。若无论如何也无法读完全部书籍，则输出 −1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
-1 0 0 10<br/>
-1 -1 -1 2<br/>
-1 1 -1 2<br/>
-1 -2 -1 1<br/>
0 2<br/>
0 -2<br/>
1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
对于 100% 的测试数据：对于任何一种“批量阅读”方案，其 ai 与 bi 不会同时为 0。且不存在 i, j （i 不等于 j）使得 ai*bj=aj*bi。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年国家集训队测试">2015年国家集训队测试</a></p></div>

