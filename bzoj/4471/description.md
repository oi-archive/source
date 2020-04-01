
# Description

<div class="content"><p>继NOI2014后，小H又发现了一种新的生成随机数的方法。<br/>
首先，给定三个随机种子P,C1,C2(C1≤C2)生成一个序列{xi}，{xi}满足<br/>
对于任意的i≥0，满足以下递推式X<sub>i+2</sub>=(X<sub>i+1</sub>+X<sub>i</sub>) mod P<br/>
其中x0=C1, x1=C2。<br/>
接着，利用序列{xi}，可以生成一个序列{ai}。序列{ai}的生成方式如下<br/>
对于任意的i≥1，ai=∑xj^2(0≤j≤i) mod P<br/>
然后，给定一个正整数Q，小H会进行Q次下述操作：每次选定两个正整数x, y，将ax和ay互换。<br/>
小H希望检验一下序列{ai}是否是随机的。他还是希望使用NOI2014那道题的方法，生成一个N×M的矩阵，其中N表示行，M表示列。我们记这个矩阵为D，在D的第1行依次放入a<sub>1</sub>~a<sub>M</sub>，第2行放入a<sub>M+1</sub>~a<sub>2M</sub>，以此类推，那么矩阵D的第i行第j列的数Di,j就应该为a<sub>(i-1)*M+j</sub>。然后，类似方格取数，从矩阵的左上角(1,1)走到右下角(N,M)，途中只能向右走或者向下走，这样他经过的方格数就应该是(N+M-1)。然后按照经过的顺序将每个方格的数字提取出来，组成一个序列叫做路径序列。他想知道，自己能得到的字典序最小的路径序列是什么。注意：为了方便，如果当前格向下和向右的方格的数字相同，那么我们认为向下的方格的数字小于向右的方格的数字。</p></div>

# Input

<div class="content"><div>输入的第一行为六个正整数N,M,Q,P,C1,C2。意义见题目描述。</div>
<div>接下来的Q行，每行一个操作：包含两个正整数x, y。</div>
<div>本题一共10个测试点，每个测试点的数据规模大致如下：</div>
<div>N,M≤{5,000, 5,000, 10,000, 20,000, 50,000, 80,000, 100,000, 100,000, 100,000, 100,000}；</div>
<div>Q=100,000；</div>
<div>P,C1,C2≤1,000,000,000。</div>
<div>另外，为了方便，输入数据中不会出现交换a1或aNM的情况。</div>
<div>请注意I/O优化，以免TLE。</div></div>

# Output

<div class="content"><p>输出一行，共(N+M-1)个正整数，表示字典序最小的路径序列。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 2 1000000 0 1<br/>
5 3<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 15 6 104</span></div>

# Hint

<div class="content"><p></p><p>对于样例，生成的序列{ai}为{1, 2, 6, 15, 40, 104}，按输入顺序交换后变为{1, 40, 2, 15, 6, 104}，将其放入2行3列的矩阵，不难看出能够得到的字典序最小的路径序列就是{1, 15, 6, 104}。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Bob">By Bob</a></p></div>

