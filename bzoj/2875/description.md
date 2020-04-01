
# Description

<div class="content"><p>栋栋最近迷上了随机算法，而随机数是生成随机算法的基础。栋栋准备使用线性同余法（Linear Congruential Me</p>
<div>thod）来生成一个随机数列，这种方法需要设置四个非负整数参数m,a,c,X[0],按照下面的公式生成出一系列随机</div>
<div>数X[n]X[n+1]=(aX[n]+c)mod m其中mod m表示前面的数除以m的余数。从这个式子可以看出，这个序列的下一个数</div>
<div>总是由上一个数生成的。用这种方法生成的序列具有随机序列的性质，因此这种方法被广泛地使用，包括常用的C+</div>
<div>+和Pascal的产生随机数的库函数使用的也是这种方法。栋栋知道这样产生的序列具有良好的随机性，不过心急的</div>
<div>他仍然想尽快知道X[n]是多少。由于栋栋需要的随机数是0,1,...,g-1之间的，他需要将X[n]除以g取余得到他想要</div>
<div>的数，即X[n] mod g，你只需要告诉栋栋他想要的数X[n] mod g是多少就可以了。</div>
<div></div></div>

# Input

<div class="content"><div>6个用空格分割的整数m,a,c,X[0],n和g，其中a,c,X[0]是非负整数，m,n,g是正整数。</div>
<div>g&lt;=10^8</div>
<div>对于所有数据,n&gt;=1,m&gt;=1,a&gt;=0,c&gt;=0,X[0]&gt;=0,g&gt;=1。</div>
<div></div></div>

# Output

<div class="content"><div>输出一个数，即X[n] mod g</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">11 8 7 1 5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
【样例说明】<br/>
计算得X[n]=X[5]=8,故(X[n] mod g) = (8 mod 3) = 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

