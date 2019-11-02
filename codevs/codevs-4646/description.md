<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定n个数和依次q个操作，每次操作有三个参数：x,y,k。若x=0，表示将第y(1&lt;=y&lt;=n)个数的值增加k；否则表示询问第x个数到第y(1&lt;=x&lt;=y&lt;=n)个数中第k小的值是多少。<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个正整数n。</p><p>第二行是n个正整数，第i个正整数表示第i个数的初始值。</p><p>第三行是一个正整数q。</p><p>接下来q行，每行三个整数x,y,k，表示一个操作的三个参数。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若干行，对于每次x不为0，一行一个正整数，表示你的答案。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p><p>1 4 4 2 5 6</p><p>10</p><p>2 4 2</p><p>3 6 4</p><p>0 2 -3</p><p>1 3 2</p><p>2 5 2</p><p>0 5 -4</p><p>3 6 3</p><p>0 3 2</p><p>2 5 3</p><p>1 6 4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p><p>6</p><p>1</p><p>2</p><p>4</p><p>2</p><p>2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>共有10个测试点，对于第i个点，n=q=f(i)：</p><p>i f(i)</p><p>1 1000</p><p>2 3000</p><p>3 4000</p><p>4 5000</p><p>5 10000</p><p>6 20000</p><p>7 30000</p><p>8 40000</p><p>9 50000</p><p>10 60000</p><p>数据保证任何时候，这n个数的值都是不大于n的正整数。</p><p>本题空间限制比较大，为256M。</p><p><br></p>
</div>
</div>