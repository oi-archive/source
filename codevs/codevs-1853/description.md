<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了使得大家高兴，小Q特意出个自认为的简单题（easy）来满足大家，这道简单题是描述如下： 有一个数列A已知对于所有的A[i]都是1~n的自然数，并且知道对于一些A[i]不能取哪些值，我们定义一个数列的积为该数列所有元素的乘积，要求你求出所有可能的数列的积的和 mod 1000000007的值，是不是很简单呢？呵呵！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个整数n,m,k分别表示数列元素的取值范围，数列元素个数，以及已知的限制条数。</p>
<p>接下来k行，每行两个正整数x,y表示A[x]的值不能是y。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数表示所有可能的数列的积的和对<strong>1000000007</strong><strong>取模</strong>后的结果。如果一个合法的数列都没有，答案输出0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 4 5</p>
<p>1 1</p>
<p>1 1</p>
<p>2 2</p>
<p>2 3</p>
<p>4 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>90</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>A[1]不能取1</p>
<p>A[2]不能去2、3</p>
<p>A[4]不能取3</p>
<p>所以可能的数列有以下12种</p>
<p>数列      积</p>
<p>2 1 1 1     2</p>
<p>2 1 1 2     4</p>
<p>2 1 2 1     4</p>
<p>2 1 2 2     8</p>
<p>2 1 3 1     6</p>
<p>2 1 3 2     12</p>
<p>3 1 1 1     3</p>
<p>3 1 1 2     6</p>
<p>3 1 2 1     6</p>
<p>3 1 2 2     12</p>
<p>3 1 3 1     9</p>
<p>3 1 3 2     18</p>
<p> </p>
<p>30%的数据n&lt;=4,m&lt;=10,k&lt;=10</p>
<p>另有20%的数据k=0</p>
<p>70%的数据n&lt;=1000,m&lt;=1000,k&lt;=1000</p>
<p>100%的数据 n&lt;=10<sup>9</sup>,m&lt;=10<sup>9</sup>,k&lt;=10<sup>5</sup>,1&lt;=y&lt;=n,1&lt;=x&lt;=m</p>
</div>
</div>