
# Description

<div class="content"><div style="text-indent: 21pt">三核苷酸是组成DNA序列的基本片段。具体来说，核苷酸一共有4种，分别用’A’，’G’，’C’，’T’来表示。而三核苷酸就是由3个核苷酸排列而成的DNA片段。三核苷酸一共有64种，分别是’AAA’，’AAG’，…，’GGG’。给定一个长度为L的DNA序列，一共可以分辨出（L-2）个三核苷酸。现在我们想用一些统计学的方法来进行一些分析，步骤如下：</div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span>1.<span style="font: 7pt &#39;Times New Roman&#39;">       </span></span>对于这（L-2）个三核苷酸，我们从左到右给予编号，分别为1到L-2。</div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span>2.<span style="font: 7pt &#39;Times New Roman&#39;">       </span></span>从这（L-2）个三核苷酸挑选一对出来，一共有(L-2)*(L-3)/2种可能。如果某一对三核苷酸是一样的，我们就记录他们之间的距离。他们之间的距离定义为他们的编号之差。</div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span>3.<span style="font: 7pt &#39;Times New Roman&#39;">       </span></span>根据我们所记录的“样本数据”，我们现在需要计算样本数据的方差。方差的计算公式是S2=[(x<sub>1</sub>-X)<sup> 2</sup>+(x<sub>2</sub>-X)<sup> 2</sup>+…+(x<sub>n</sub>-X)<sup>2</sup>]/n, X=(x<sub>1</sub>+x<sub>2</sub>+…+x<sub>n</sub>)/n。如果样本的大小n=0，那么我们认为S2=X=0。</div>
<div style="margin: 0cm 0cm 0pt 21pt"> </div>
<div style="margin: 0cm 0cm 0pt 21pt">例如，我们要统计DNA序列’ATATATA’：</div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span>1.<span style="font: 7pt &#39;Times New Roman&#39;">       </span></span>为三核苷酸编号. L<sub>1</sub>: ATA, L<sub>2</sub>:TAT, L<sub>3</sub>:ATA, L<sub>4</sub>:TAT, L<sub>5</sub>:ATA.</div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span>2.<span style="font: 7pt &#39;Times New Roman&#39;">       </span></span>(L<sub>1</sub>,L<sub>3</sub>)=2, (L<sub>1</sub>,L<sub>5</sub>)=4, (L<sub>3</sub>,L<sub>5</sub>)=2, (L<sub>2</sub>,L<sub>4</sub>)=2. 所以样本数据是2,4,2,2.</div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span>3.<span style="font: 7pt &#39;Times New Roman&#39;">       </span></span>样本数据平均值X=(2+4+2+2)/4=2.5.</div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 18pt">方差S2=[(2-2.5)<sup>2</sup>+(4-2.5)<sup> 2</sup>+(2-2.5)<sup>2</sup>+(2-2.5)<sup>2</sup>]/4=0.75.</div>
<div><span>       </span>给定一个DNA序列，请你计算出它的方差。</div></div>

# Input

<div class="content"><div style="text-indent: 21pt">输入包含多组测试数据。第一行包含一个正整数T，表示测试数据数目。每组数据包含一个由’A’，’G’，’C’，’T’组成的字符串，代表要统计的DNA序列。DNA序列的长度大于等于3且不会超过100000。</div>
<div style="text-indent: 21pt"> </div></div>

# Output

<div class="content"><div style="line-height: 115%"> </div>
<div style="text-indent: 21pt">对每组测试数据，输出一行答案，为一个保留6位精度的实数，代表S2的值。如果你的答案和标准答案的“相对误差”小于1e-8，你的答案会被视为正确的答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
ATATATA<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.750000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

