
# Description

<div class="content"><div>方格纸与草稿纸一样，都是算法竞赛中不可或缺的重要工具。身经百战的小Q自然也会随身带着方格纸。小Q的方格</div>
<div>纸有n行m列，一共n*m个方格，从上到下依次标记为第1,2,...,n行，从左到右依次标记为第1,2,...,m列，方便起</div>
<div>见，小Q称第i行第j列的方格为(i,j)。小Q在方格纸中填满了数字，每个格子中都恰好有一个整数a_{i,j}。小Q不</div>
<div>喜欢手算，因此每当他不想计算时，他就会让你帮忙计算。小Q一共会给出q个询问，每次给定一个方格(x,y)和一</div>
<div>个整数k(1&lt;=k&lt;=min(x,y))，你需要回答由(x,y),(x-k+1,y),(x,y-k+1)三个格子构成的三角形边上以及内部的所有</div>
<div>格子的a的和。</div></div>

# Input

<div class="content"><div>第一行包含6个正整数n,m,q,A,B,C(1&lt;=n,m&lt;=3000,1&lt;=q&lt;=3000000,1&lt;=A,B,C&lt;=1000000)</div>
<div>其中n,m表示方格纸的尺寸，q表示询问个数。</div>
<div>为了防止输入数据过大，a和询问将由以下代码生成：</div>
<div>unsigned int A,B,C;</div>
<div>inline unsigned int rng61(){</div>
<div>    A ^= A &lt;&lt; 16;</div>
<div>    A ^= A &gt;&gt; 5;</div>
<div>    A ^= A &lt;&lt; 1;</div>
<div>    unsigned int t = A;</div>
<div>    A = B;</div>
<div>    B = C;</div>
<div>    C ^= t ^ A;</div>
<div>    return C;</div>
<div>}</div>
<div>int main(){</div>
<div>    scanf(&#34;%d%d%d%u%u%u&#34;, &amp;n, &amp;m, &amp;q, &amp;A, &amp;B, &amp;C);</div>
<div>    for(i = 1; i &lt;= n; i++)</div>
<div>        for(j = 1; j &lt;= m; j++)</div>
<div>            a[i][j] = rng61();</div>
<div>    for(i = 1; i &lt;= q; i++){</div>
<div>        x = rng61() % n + 1;</div>
<div>        y = rng61() % m + 1;</div>
<div>        k = rng61() % min(x, y) + 1;</div>
<div>    }</div>
<div>}</div></div>

# Output

<div class="content"><p>为了防止输出数据过大，设f_i表示第i个询问的答案，则你需要输出一行一个整数，即：</p>
<div>(sum_{i=1}^q 233^{q-i}*f_i) mod 2^{32}</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 5 2 3 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">3350931807<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

