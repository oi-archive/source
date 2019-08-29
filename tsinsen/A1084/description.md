<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　离散傅立叶变换在信号处理中扮演者重要的角色。利用傅立叶变换，可以实现信号在时域和频域之间的转换。<br/>
　　对于一个给定的长度为n=2<sup>m</sup> (m为整数) 的复数序列X<sub>0</sub>, X<sub>1</sub>, …, X<sub>n-1</sub>，离散傅立叶变换将得到另一个长度为n的复数序列Y<sub>0</sub>, Y<sub>1</sub>, …, Y<sub>n-1</sub>。其中<br/>
　　Y<sub>i</sub>=X<sub>0</sub>+X<sub>1</sub>w<sup>i</sup>+ X<sub>2</sub>w<sup>2i</sup>+ X<sub>3</sub>w<sup>3i</sup>+…+ X<sub>n-1</sub>w<sup>(n-1)i</sup><br/>
　　其中w=e<sup>2</sup><sup>πI/n</sup>=cos(2π/n)+I sin(2π/n)，称为旋转因子，其中I为虚数单位，I<sup>2</sup>= –1。<br/>
　　给定输入序列X，请输出傅立叶变换后的输出序列。<br/>
<br/>
　　由于所有的复数C都可以表示成C=a+Ib的形式，即由实部和虚部的和表示，所以C可以用一个二元组(a, b)来表示，用这种方法w可表示为(cos(2π/n), sin(2π/n))。复数的计算规则如下：<br/>
　　(a<sub>1</sub>, b<sub>1</sub>)+(a<sub>2</sub>, b<sub>2</sub>)=(a<sub>1</sub>+a<sub>2</sub>, b<sub>1</sub>+b<sub>2</sub>)<br/>
　　(a<sub>1</sub>, b<sub>1</sub>)(a<sub>2</sub>, b<sub>2</sub>)=(a<sub>1</sub>, b<sub>1</sub>)*(a<sub>2</sub>, b<sub>2</sub>)=(a<sub>1</sub>*a<sub>2</sub>-b<sub>1</sub>*b<sub>2</sub>, a<sub>1</sub>*b<sub>2</sub>+a<sub>2</sub>*b<sub>1</sub>)<br/>
<br/>
　　对于本题，你可以按照上面的公式直接计算，也可以按下面的方法计算。使用上面的公式的复杂度为O(n<sup>2</sup>)，可以得到一半的分数，而下面的方法的复杂度为O(n log n)，可以得到全部的分数。如果要使用上面的公式直接计算，请跳过下面的算法描述部分。</div>
# 算法描述

<div class="pdcont">　　注意到上式中w=e<sup>2</sup><sup>πI/n</sup>=cos(2π/n)+I sin(2π/n)，所以w<sup>n+k</sup>=w<sup>k</sup>，这个公式将在下面的计算用用到。<sub></sub><br/>
　　对上面的公式进行变形，得到：<br/>
　　Y<sub>i</sub><br/>
　　=X<sub>0</sub> + X<sub>1</sub>w<sup>i</sup> + X<sub>2</sub>w<sup>2i</sup> + X<sub>3</sub>w<sup>3i</sup> +…+ X<sub>n-1</sub>w<sup>(n-1)i</sup><br/>
　　=X<sub>0</sub> + X<sub>2</sub>w<sup>2i</sup> + X<sub>4</sub>w<sup>4i</sup> +…+ X<sub>n-2</sub>w<sup>(n-2)i</sup> + w<sup>i</sup>(X<sub>1</sub> + X<sub>3</sub>w<sup>2i</sup> + X<sub>5</sub>w<sup>4i</sup> +…+ X<sub>n-1</sub>w<sup>(n-2)i</sup>)<br/>
　　=(X<sub>0</sub> + X<sub>2</sub>φ<sup>i</sup> + X<sub>4</sub>φ<sup>2</sup><sup>i</sup> +…+ X<sub>n-2</sub>φ<sup>(n/2-1)i</sup>) + w<sup>i</sup>(X<sub>1</sub> + X<sub>3</sub>φ<sup>i</sup> + X<sub>5</sub>φ<sup>2</sup><sup>i</sup> +…+ X<sub>n-1</sub>φ<sup>(n/2-1)i</sup>)<br/>
　　其中φ=w<sup>2</sup>。利用这个公式可得<br/>
　　Y<sub>i+n/2</sub>=(X<sub>0</sub> + X<sub>2</sub>φ<sup>i+n/2</sup> + X<sub>4</sub>φ<sup>2(</sup><sup>i+n/2)</sup> +…+ X<sub>n-2</sub>φ<sup>(n/2-1)</sup><sup> (i+n/2)</sup>) + w<sup>i</sup>(X<sub>1</sub> + X<sub>3</sub>φ<sup>(</sup><sup>i+n/2)</sup> + X<sub>5</sub>φ<sup>2(</sup><sup>i+n/2)</sup> +…+ X<sub>n-1</sub>φ<sup>(n/2-1)</sup><sup> (i+n/2)</sup>)<br/>
　　其中φ<sup>i+n/2</sup>=w<sup>2i+n</sup>=w<sup>2i</sup>=φ<sup>i</sup>。<br/>
　　所以当i&lt;n/2时，令p<sub>i</sub>=X<sub>0</sub> + X<sub>2</sub>φ<sup>i</sup> + X<sub>4</sub>φ<sup>2</sup><sup>i</sup> +…+ X<sub>n-2</sub>φ<sup>(n/2-1)i</sup>，q<sub>i</sub>= X<sub>1</sub> + X<sub>3</sub>φ<sup>i</sup> + X<sub>5</sub>φ<sup>2</sup><sup>i</sup> +…+ X<sub>n-1</sub>φ<sup>(n/2-1)i</sup>，则Y<sub>i</sub>=p<sub>i</sub>+w<sup>i</sup>q<sub>i</sub>，Y<sub>i+n/2</sub>= p<sub>i</sub>+w<sup>i+n/2</sup>q<sub>i</sub>。<br/>
　　利用上面的公式，我们可以得到一种快速计算旋转因子为w的傅立叶变换的方法如下（快速傅立叶变换）：<br/>
　　算法Y=Fourier(X, n, w)<br/>
　　参数：X={X<sub>i</sub>}为待变换的序列，n为序列的长度（2的整数次幂），w为旋转因子<br/>
　　结果：X的傅立叶变换Y={Y<sub>i</sub>}<br/>
　　1.      计算{X<sub>0</sub>, X<sub>2</sub>, X<sub>4</sub>, …, X<sub>n-2</sub>}在旋转因子为φ=w<sup>2</sup>时的傅立叶变换序列{p<sub>i</sub>}<br/>
　　2.      计算{ X<sub>1</sub>, X<sub>3</sub>, X<sub>5</sub>, …, X<sub>n-1</sub>}在旋转因子为φ=w<sup>2</sup>时的傅立叶变换序列{q<sub>i</sub>}<br/>
　　3.      对于0&lt;=i&lt;n，计算Y<sub>i</sub>=p<sub>i</sub>+w<sup>i</sup>q<sub>i</sub>。其中w<sup>0</sup>=(1, 0)，w<sup>i</sup>=w<sup>i-1</sup>*w，你要设置一个临时变量进行累乘而不能每次重新计算w<sup>i</sup>。<br/>
　　使用这种方法，即可在O(n log n)的时间内计算傅立叶变换。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个整数n，表示待变换的序列的长度，n是2的整数次幂。n&lt;=16384。<br/>
　　接下来n行，每行2个实数a, b表示序列中的一个元素为(a, b)。</div>
# 输出格式

<div class="pdcont">　　输出n行，每行两个实数，表示经过变换后的序列。为了防止运算时的误差影响结果的输出，请将结果中的每一个实数除以n后保留两位小数。</div>
# 样例输入

<div class="pddata">4<br/>
1.0 0.0<br/>
1.0 0.0<br/>
0.0 0.0<br/>
0.0 0.0</div>
# 样例输出

<div class="pddata">0.50 0.00<br/>
0.25 0.25<br/>
0.00 0.00<br/>
0.25 -0.25</div>

</div>