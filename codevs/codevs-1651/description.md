<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明的书架上放了许多书，为了使书架变得整洁，小明决定整理书架，他将所有书按高度大小排列，这样排了之后虽然整齐了许多，但小明发现，书本的宽度不同，导致书架看上去还是有些凌乱。小明把这个凌乱值定义为相邻两本书的宽度差的绝对值的和。</p>
<p>例如有<span style="font-family: 'Times New Roman';">4</span><span style="">本书：</span></p>
<p>1<span style="">×</span><span style="font-family: 'Times New Roman';">2</span></p>
<p>5<span style="">×</span><span style="font-family: 'Times New Roman';">3</span></p>
<p>2<span style="">×</span><span style="font-family: 'Times New Roman';">4</span></p>
<p>3<span style="">×</span><span style="font-family: 'Times New Roman';">1</span></p>
<p>那么小明将其排列整齐后的顺序是：</p>
<p>1<span style="">×</span><span style="font-family: 'Times New Roman';">2</span></p>
<p>2<span style="">×</span><span style="font-family: 'Times New Roman';">4</span></p>
<p>3<span style="">×</span><span style="font-family: 'Times New Roman';">1</span></p>
<p>5<span style="">×</span><span style="font-family: 'Times New Roman';">3</span></p>
<p>凌乱值就是<span style="font-family: 'Times New Roman';">2+3+2</span><span style="">＝</span><span style="font-family: 'Times New Roman';">7</span></p>
<p>于是小明决定拿掉其中的k本书，使凌乱值最小，你能帮他求出这个最小值吗？</p>
<p>已知每本书的高度都不一样。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数字n和k，代表书总共有n本，要求从中去掉k本。（<span style="font-family: 'Times New Roman';">1</span><span style="">≤</span>n≤100,1≤k＜n）</p>
<p>下面的n行，每行两个数字表示一本书的高度和宽度，它们均小于<span style="font-family: 'Times New Roman';">200</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一行一个整数，表示书架的最小凌乱值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1</p>
<p>1 2</p>
<p>2 4</p>
<p>3 1</p>
<p>5 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>【数据范围】</p>
<p>30%<span style="">的数据，</span>n≤<span style="font-family: 'Times New Roman';">20</span></p>
<p>100%<span style="">的数据，</span>n≤<span style="font-family: 'Times New Roman';">10</span>0，k&lt;n</p>
</div>
</div>
</div>