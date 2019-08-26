
# Description

<div class="content"><div>“即使执政官再圆，也不是我子民的样子！”——西瓜王</div>
<div>xgw为了见到真正的西瓜，来到了小镇著名的水果店“香果屋”。他在这里看到了很多又大又圆的西瓜，他决定带几个西瓜回家。“香果屋”里有n种西瓜，每种西瓜有一个权值x_i,而有钱任性的xgw把每种西瓜都买了一个带回家！！</div>
<div>将西瓜带回家后，xgw自然是要向他们的子民训话。每次他会从中选出一个子集进行训话，每次训话的愉悦度是选出西瓜的权值的最小公倍数乘最大公约数。</div>
<div>他是个任性的国王，他会把每种可以选择的方式都来一遍，当然，每次选择至少选出一个西瓜（也就是不会为空集）。</div>
<div>你需要求的是xgw训话完之后的愉悦值之和。由于答案可能过大，请输答案ans \mod 10^5的值。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数 T, 代表测试数据的组数。</div>
<div>接下来是 T 组测试数据，对每一组测试数据：</div>
<div>第一行包含一个整数 n, 代表元素的个数。</div>
<div>第二行包含 n 个用空格隔开的互不相同的正整数x_i。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对每组测试数据，在新的一行输出答案</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2  <br/>
2  <br/>
2 3  <br/>
3  <br/>
2 4 10  </span></div>

# Sample Output

<div class="content"><span class="sampledata">19  <br/>
228</span></div>

# Hint

<div class="content"><p></p><p>1&lt;=T&lt;=400, 2&lt;=n&lt;=100, 1 &lt;= x_i &lt;= 250</p><br/>
<div>第一组数据：</div><br/>
<div>子集 1 : {2} ==&gt; lcm = 2, gcd = 2, lcm*gcd = 4</div><br/>
<div>子集 2 : {3} ==&gt; lcm = 3, gcd = 3, lcm*gcd = 9</div><br/>
<div>子集 3 : {2,3} ==&gt; lcm = 6, gcd = 1, lcm*gcd = 6</div><br/>
<div>答案 = 4 + 9 + 6 = 19</div><br/>
<div></div><br/>
<div>第二组数据：</div><br/>
<div>子集 1 : {2} ==&gt; lcm = 2, gcd = 2, lcm*gcd = 4</div><br/>
<div>子集 2 : {4} ==&gt; lcm = 4, gcd = 4, lcm*gcd = 16</div><br/>
<div>子集 3 : {10} ==&gt; lcm = 10,gcd = 10 , lcm*gcd = 100</div><br/>
<div>子集 4 : {2,4} ==&gt; lcm = 4, gcd = 2 , lcm*gcd = 8</div><br/>
<div>子集 5 : {4,10} ==&gt; lcm = 20,gcd = 2 , lcm*gcd = 40</div><br/>
<div>子集 6 : {2,10} ==&gt; lcm = 10,gcd = 2 , lcm*gcd = 20</div><br/>
<div>子集 7 : {2,4,10} ==&gt; lcm = 20,gcd = 2 , lcm*gcd = 40</div><br/>
<div></div><br/>
<div>答案 = 4 + 16 + 100 + 8 + 40 + 20 + 40 = 228 </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

