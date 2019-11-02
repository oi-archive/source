<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个长度为n的数列a<sub>1</sub>,a<sub>2</sub>,...,a<sub>n</sub>。<br></p><p>支持两种操作：</p><p>1 l r：将ar移动到al前面。也就是：</p><p>        ...,a<sub>l-1</sub>,a<sub>l</sub>,a<sub>l+1</sub>,...a<sub>r</sub>,a<sub>r+1</sub>,...-&gt;...,a<sub>l-1</sub>,a<sub>r</sub>,a<sub>l</sub>,a<sub>l+1</sub>,...,a1<span style="">r-1</span>,a<sub>r+1</sub>,...</p><p>        这次操作后数列将重新从1到n进行编号。<br></p><p>2 l r k：求a<sub>l</sub>,a<sub>l+1</sub>,...,a<sub>r</sub>中有多少个k。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示数列长度。</p><p>下一行n个整数，表示数列。</p><p>下一行一个整数m，表示操作次数。</p><p>接下来m行，每行一个操作，格式见题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个2操作，输出一行一个数，表示答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p><p>6 6 2 7 4 2 5</p><p>7</p><p>1 3 6</p><p>2 2 4 2</p><p>2 4 6 2</p><p>2 3 3 6</p><p>1 2 6</p><p>1 1 4</p><p>2 1 7 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p>1</p><p>0</p><p>0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于所有数据，满足1<span style="">≤</span>n,m<span style="">≤100000,1<span style="">≤a<sub>i</sub><span style="">≤n,1<span style="">≤l,r,k<span style="">≤n</span></span></span></span></span></p><p><span style="">以下部分互相独立。</span></p><p><span style="">20%的数据，1<span style="">≤n,m<span style="">≤1000</span></span></span></p><p><span style="">20%的数据，1<span style="">≤n<span style="">≤3000</span></span></span></p><p><span style="">20%的数据，1<span style="">≤n,m<span style="">≤50000</span></span></span></p><p><span style="">20%的数据，所有1操作都在2操作之前</span><span style=""></span></p>
</div>
</div>