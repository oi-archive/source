<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　给定人的三个具有n对等位基因的基因序列(简化版)，代表一对父母和一个孩子的部分基因，保证相同位置的基因是等位基因。<br>　　父母的部分显性基因未能详细测出，但是保证孩子的基因已经完全测出，求出父母基因结合产生孩子基因的概率，用分数表示。<strong>对于概率为0的情况，请您输出0/0，这很重要！</strong><br>　　题目保证遵循父母的遗传遵循自由组合定律(简要的说是遵循乘法原理)，<strong>不存在基因致死情况</strong>。<br> <br>　　这种简化版的基因序列包含六种情况，分别对应0~5这六个数字：<br>　　　　0 代表 显性纯合子(即AA、BB、CC等)<br>　　　　1 代表 显性杂合子(即Aa、Bb、Cc等)<br>　　　　2 代表 隐性基因(即aa、bb、cc等)<br>　　　　3 代表 显性基因(即A_、B_、C_等)，表示该位置的基因至少有一个显性配子，即显性纯合子(AA)与显性杂合子(Aa)的概率均为1/2<br>　　　　4 代表 显性配子(即A、B、C等)<br>　　　　5 代表 隐性配子(即a、b、c等)<br>　　其中3不会出现在孩子的基因中，而4和5仅在性染色体上出现，保证父母其中一方出现4和5的位置，对应的另一方该位置必然为0~3(其实就是保证没有搞基的 - - )。<br><strong>　　仅存在伴X染色体遗传，即基因在X染色体(性染色体)上，而且由于显隐性基因仅在X染色体上，所以存在交叉遗传。由于不存在雌雄同体，所以父亲和儿子的性染色体部分必然是4或5，母亲和女儿的性染色体部分必然是0-3(女儿没有3)。孩子已经出生，所以生男生女被认为是确定的。</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　每个测试点包含多组询问。<br>　　第一行是一个正整数Q，代表接下来有Q组询问。<br>　　接下来Q行，每行一个正整数n和三个由0~3或4~5组成的数字串，空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　共Q行，每行一个分数。</span></p>
<p><span><br /></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】<br>2<br>3 333 333 111<br>4 0123 3210 2222</p>
<p> </p>
<p>【样例输入2】</p>
<p>3<br>2 33 12 21<br>3 232 544 201<br>4 3333 4545 4444</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】<br>27/512<br>0/0</p>
<p> </p>
<p>【样例输出2】<br>3/32<br>3/4<br>81/256</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】</p>
<p>在第一个样例中：<br>　　第一组询问为(A_)(B_)(C_)和(A_)(B_)(C_)生出(Aa)(Bb)(Cc)，概率为(3/8)<sup>3</sup> = 27/512，所以应当输出27/512；<br>　　第二组询问为(AA)(Bb)(cc)(D_)和(A_)(bb)(Cc)(DD)生出(aa)(bb)(cc)(dd)，从第一对等位基因(AA)与(A_)看出不可能产生这种基因型，所以应当输出0/0。<br> <br>在第二个样例中：<br>　　第一组询问为(A_)(B_)和(Aa)(bb)生出(aa)(Bb)，概率为(1/8) * (3/4) = 3/32，所以应当输出3/32；<br>　　第二组询问为(X<sup>aa</sup>)(X<sup>B_</sup>)(X<sup>cc</sup>)和(X<sup>a</sup>Y)(X<sup>B</sup>Y)(X<sup>C</sup>Y)生出女孩(X<sup>aa</sup>)(X<sup>BB</sup>)(X<sup>Cc</sup>)，概率为1 * (3/4) * 1 = 3/4，所以应当输出3/4；<br>　　第三组询问为(X<sup>A_</sup>)(X<sup>B_</sup>)(X<sup>C_</sup>)(X<sup>D_</sup>)和(X<sup>A</sup>Y)(X<sup>b</sup>Y)(X<sup>C</sup>Y)(X<sup>d</sup>Y)生出男孩(X<sup>A</sup>Y)(X<sup>B</sup>Y)(X<sup>C</sup>Y)(X<sup>D</sup>Y)，概率与父亲无关，为(3/4)<sup>4</sup> = 81/256，所以应当输出81/256。<br> <br>　　解释：每对括号里为一个基因型，其中XY为性染色体。</p>
<p>【数据范围与约定】</p>
<p>　　对于100%的数据， 1 ≤ Q ≤ 20，1 ≤ n ≤ 520，<strong>给出的亲本可能是先父后母，也可能是先母后父，可以既存在常染色体遗传，又存在伴X染色体遗传</strong>。</p>
<p> </p>
<p>【来源】</p>
<p>　　2013年3月23日白色情人节欢乐赛Day1T1。</p>
</div>
</div>