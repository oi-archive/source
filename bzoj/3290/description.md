
# Description

<div class="content"><div>【题目背景】</div>
<div>Theresa是个爱思考的女孩……</div>
<div>【问题描述】</div>
<div>这是个复杂的世界。人类社会，自然界，还有地球之外的银河……</div>
<div>每一天日出日落，人来人往，步履匆匆。究竟是为什么呢？那支配着一切的至高无上的法则又是否存在呢？Theres</div>
<div>a知道，这个问题并不是一朝一夕就可以解答的，只有在仔细、深入的观察和思考以后，才有可能将所有支离破碎</div>
<div>的线索联系起来，从而隐约窥见真实的答案。于是，Theresa经常思考生活中遇到的大大小小的问题。为什么港台</div>
<div>出版的书籍里印刷的汉字她一个也不认识呢？为什么隔夜的白开水中富含一氧化二氢呢？为什么每年都有一段时间</div>
<div>Gmail邮箱上不去呢？……为了更加系统、科学地分析这些问题，Theresa决定向你求助。长话短说，Theresa想请</div>
<div>你帮助她实现一个数据结构。这个数据结构的功能是在空间直角坐标系中维护一个点的集合，并支持以下三类操作</div>
<div>：</div>
<div>1.ADD x y z          加入一个新的点，点的坐标为(x, y, z)。</div>
<div>2.QUERY x y z r      查询在正方体(x, y, z) - (x+r, y+r, z+r)内部的点的数目。</div>
<div>3.CANCEL             撤销最近的一次ADD操作。</div>
<div>其中x,y,z,r均为给出的整数。QUERY操作中，(x,y,z)为正方体的一个顶点的坐标，r为正方体的边长。在正方体边</div>
<div>界上的点也算在正方体内部。这个问题可能过于困难，所以Theresa并不强迫你实现一个高效的数据结构。然而，</div>
<div>你必须对每一次QUERY操作给出正确的答案。</div></div>

# Input

<div class="content"><div>
<div>第一行包含一个整数N，表示最初的点集有N个点。</div>
<div>接下来N行，每行包含三个整数xi、yi、zi，依次表示每个点的坐标。</div>
<div>第N+2行包含一个整数Q，表示将有Q次操作。</div>
<div>接下来Q行，每行表示一次操作，格式如题目描述。</div>
<div>1 ≤ N + Q ≤ 100 000， 0 ≤ x, y, z, r ≤ 10^7。</div>
<div>r 为正整数。所有的CANCEL操作均为有效操作。不同的点的坐标可能重合。</div>
</div></div>

# Output

<div class="content"><div>输出若干行，每行一个整数，依次表示每次查询操作的答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 2 3<br/>
1 1 3<br/>
7<br/>
ADD 0 4 3<br/>
QUERY 0 0 0 4<br/>
ADD 1 1 5<br/>
QUERY 1 1 2 3<br/>
QUERY 0 2 2 1<br/>
CANCEL<br/>
QUERY 1 1 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
3<br/>
1<br/>
2<br/>
样例说明<br/>
第1次查询正方体(0,0,0)-(4,4,4)，内部包含点(1,2,3)，(1,1,3)，(0,4,3)。<br/>
第2次查询正方体(1,1,2)-(4,4,5)，内部包含点(1,2,3)，(1,1,3)，(1,1,5)。<br/>
第3次查询正方体(0,2,2)-(1,3,3)，内部包含点(1,2,3)。<br/>
第4次查询正方体(1,1,2)-(4,4,5)，内部包含点(1,2,3)，(1,1,3)。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

