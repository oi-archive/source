
# Description

<div class="content"><div>输入5个整数a,b,n,k,p。</div>
<div>定义</div>
<div>g(0)=a,g(1)=b,g(i)=3g(i−1)−g(i−2)(i≥2)</div>
<div>换句话说g(n)相当于以a,b为初始值的一个线性递推数列。</div>
<div>f(n,0)=n,f(n,k)=f(g(n),k−1)(k≥1)</div>
<div>换句话说f(n,k)相当于把k个g函数嵌套使用 。</div>
<div>请输出f(n,k)modp的结果。</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行一个整数t表示数据组数。</div>
<div>接下来t组数据，每组数据为一行五个整数a,b,n,k,p，含义见题。</div>
<div>0≤a,b&lt;p，1≤t≤1000,1≤n,p≤10^9,1≤k≤100。</div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，输出一个整数表示答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
0 1 2 2 1000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

