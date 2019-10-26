
# Description

<div class="content"><div><span style="font-size: 12pt">工厂的产品要装入圆柱形盒子。所有的盒子都是一样的底，盒子的高是一个2的乘方的非负整数。例如，对一些i＝0，1，2，…其值等于2<sup>i</sup>，数字i（指数）称作盒子的尺寸。所有盒子包含一样的货物，但是它们价值可以不同，早期制作出的货物更便宜。管理者决定，最早的（最便宜的）货物应该首先卖出；在仓库里，货物要装入集装箱，集装箱也是圆柱形的；每个集装箱的直径比盒子的直径要大一点，这样，盒子很容易放进集装箱。集装箱的高度是一个非负的2 的乘方。这个数称为集装箱的尺寸。为了安全的运输需要用盒子装满集装箱，即放进集装箱的盒子的高度总和必须等于这个集装箱的高度。一套集装箱送到仓库，检查仓库中的盒子是否能装满所有的集装箱，如果能，求装入集装箱中货物的最小价值。</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">例如，考虑有5个盒子的仓库，它们的大小及它们中货物的价值如下：</span></div>
<p><divre></divre>
<span style="font-size: 12pt">1 3</span></p>
<pre></pre>
<pre><span style="font-size: 12pt">1 2</span></pre>
<pre><span style="font-size: 12pt">3 5</span></pre>
<pre><span style="font-size: 12pt">2 1</span></pre>
<pre><span style="font-size: 12pt">1 4</span></pre>
<p><span style="font-size: 12pt">尺寸为1和2的2个集装箱能够放入价值为3，4或5的盒子，或者三个总价值为9的盒子，在仓库中，尺寸为5的集装箱不能装满盒子。</span></p>
<div></div>
<div><b><span style="font-size: 12pt">【任务】编写程序：</span></b></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: 12pt">1、</span><span style="font-size: 12pt">读入仓库中货物的描述（大小，价值）和集装箱的描述（提供几个多少尺寸的集装箱）；</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: 12pt">2、</span><span style="font-size: 12pt">检查仓库中的货物能否装入集装箱，若能，求出装入集装箱中货物的最小价值；</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: 12pt">3、</span><span style="font-size: 12pt">将结果输出。</span></div></div>

# Input

<div class="content"><div><span style="font-size: 12pt">第一行有一个整数N，1≤N≤10000，表示仓库中盒子总数；下面N行每行有两个由空格分开的非负整数，它们描述每一个盒子，其中第一个数是盒子的尺寸，第二个数是盒子中货物的价值，尺寸不超过1000，价值不超过10000；下一行有一个整数Q，表示运输到仓库的集装箱数（提供的集装箱个数），再下面的Q行，每行有两个由空格分开的整数，第一个数是集装箱的尺寸，第二个数是该尺寸的集装箱的总数，集装箱的最大数目是5000，集装箱的尺寸不超过10</span></div></div>

# Output

<div class="content"><p><span style="font-size: 12pt">输出只有一行：</span></p>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: 12pt">1、</span><span style="font-size: 12pt">NIE</span><span style="font-size: 12pt">――表示仓库中的盒子不能装满意集装箱；</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: 12pt">2、</span><span style="font-size: 12pt">一个整数――与1中相反的情况，则输出装入集装箱中货物的最小价值。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5                                      <br/>
1 3<br/>
1 2<br/>
3 5<br/>
2 1<br/>
1 4<br/>
2<br/>
1 1<br/>
2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

