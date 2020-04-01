
# Description

<div class="content"><div>Apple很喜欢吃巧克力，但它是一头挑剔的猪，有的品种的巧克力并不能满足它的胃口。如果主人给它的巧克力它</div>
<div>不喜欢吃，它就会很不开心。主人并不知道，什么样的巧克力Apple喜欢吃，但她知道巧克力的可可含量是巧克力</div>
<div>口感的重要因素，因此她决定根据巧克力的可可含量来判断什么样的巧克力拿给Apple吃，什么样的巧克力不拿给A</div>
<div>pple吃。假设一块巧克力的可可含量有1-N种不同的计量，则她认为可可含量在[a，b]的范围内的巧克力是好吃的</div>
<div>。不过她不知道的这个范围到底是多少，需要你来帮忙确定这个范围，使得她可以让Apple吃到最多的喜欢吃的巧</div>
<div>克力。设posi是可可脂含量为i，且Apple认为是好吃的巧克力的数量，negi是可可脂含量为i，且apple认为是不好</div>
<div>吃的巧克力的数量。这两个序列由以下方法生成：posi=a[i*2-1]negi=a[i*2]其中a[i]=(a[i-1]*p1+p2)modM(i&gt;1)</div>
<div>a[1]=a0设</div>
<div>TP(truepositive)是Apple认为好吃的、且被主人认为是好吃的巧克力数量。</div>
<div>TN(truenegative)是Apple认为不好吃的、且被主人认为是不好吃的巧克力数量。</div>
<div>FP(falsepositive)是Apple认为不好吃的、且被主人认为是好吃的巧克力数量。</div>
<div>FN(falsenegative)是Apple认为好吃的、且被主人认为是不好吃的巧克力数量。</div>
<div>设r为被正确判断为好吃的巧克力数占所有好吃的巧克力的比率，p为被正确判断为好吃的巧克力占所有被判定为好</div>
<div>吃的巧克力数的比率。则r=TP/(TP+FN)p=TP/(TP+FP)请你帮助Apple求出一个范围，使得f=2pr/(p+r)最大。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入由若干行组成，每行是一组数据：N，a0，p1，p2，M，中间用空格分开。</div>
<div>(1&lt;=N&lt;=1000000，a0，p1，p2&lt;M&lt;=20)输入以一个0结束，数据组数不超过1000。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>每组数据输出一行，为f的最大值（四舍五入保留6位小数），输入保证至少有一块Apple</div>
<div>认为好吃的巧克力。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 4 1 5<br/>
12 9 6 6 11<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.800000<br/>
0.683938</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

