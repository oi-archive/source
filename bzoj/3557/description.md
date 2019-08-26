
# Description

<div class="content"><div>露露、花花和萱萱最近对计算机中的随机数产生了兴趣。为大家所熟知的是，有计算机生成的随机数序列并非真正的随机数，</div>
<div>而是由一定法则生成的伪随机数。 </div>
<div>某一天，露露了解了一种生成随机数的方法，成为Mersenne twister。给定初始参数m∈Z+，x∈Z+∩[0,2m)和初值M0∈Z+∩[0,2m)，</div>
<div>它通过下列递推式构造伪随机数列{Mn}: </div>
<div><img src="source/bzoj/3557/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS8yODQ5LmpwZw==.jpg" width="621" height="89" alt=""/></div>
<div> 其中XOR是二进制异或运算（C/C++中的^运算）。而参数x的选取若使得该数列在长度趋于无穷时，近似等概率地在Z+∩(0,2m)中取值，</div>
<div>就称x为好的。例如，在m&gt;1时x=0就显然不是好的。 </div>
<div>在露露向伙伴们介绍了Mersenne twister之后，花花想用这一些经典的随机性测试来检验它的随机性强度。为此，花花使用计算机计算</div>
<div>了一些Mk。 </div>
<div>但细心的萱萱注意到，花花在某次使用二进制输入k时，在末尾多输入了l个0,。她正想告诉花花这个疏忽，然而花花已经计算并记录了</div>
<div>错误的Mk而没有记录k的值。虽然这其实不是什么致命的问题，但是在萱萱告诉花花她这个疏漏时，作为完美主义者的花花还是恳求萱萱</div>
<div>帮她修正Mk的值。萱萱便把这个任务交给了她的AI——你。 </div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数m， </div>
<div>第二行为二进制表示的x（共m个数，从低位到高位排列） </div>
<div>第三行为二进制表示的M0（排列方式同x）， </div>
<div>第四行包含一个整数type。 </div>
<div>接下来分为两种可能的情况： </div>
<div>1.type=0（萱萱记下了花花的输入）：则第五行包含一个整数，表示萱萱记下来的正确的k值。 </div>
<div>2.type=1（萱萱未能记下花花的输入）：则第五行为l，第六行输入花花计算出错误的二进制表示的Mk。 </div></div>

# Output

<div class="content"><p>仅一行，为m位的01串，表示你求得的正确Mk（同样要求从低位到高位）。 </p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1 1 1 0 0 1 1 1 0 0 <br/>
1 1 1 0 0 0 0 0 1 1 <br/>
0<br/>
100</span></div>

# Sample Output

<div class="content"><span class="sampledata">0101111001</span></div>

# Hint

<div class="content"><p></p><p> M&lt;=1000000  K&lt;=10^6</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

