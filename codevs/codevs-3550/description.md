<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Karin在战斗之余的闲暇时光里喜欢上B站看鬼畜视频，尤其喜欢发弹幕。她这天对</p><p>一个视频的弹幕产生了兴趣，她记录了每个时间点的弹幕数量，并且可能对一段呈等差数</p><p>列的时间的弹幕数量求最大值；她还可能修改某个时间点的弹幕数量。</p><p>为了不在Yuuna面前暴露出她弱爆了的数学能力， 保持她傲娇的属性， 你需要帮助她。</p><p>精简题意：给定一个序列，支持以下操作：①对一段下标是等差数列的子序列进行求</p><p>最大值操作(参见输入格式)；②单点修改。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个整数n，</p><p>第二行是一个长度为n的整数序列a1...an，</p><p>第三行是一个整数m，</p><p>接下来m行，每行首先有一个整数op，</p><p>然后，若op=0，则之后有两个整数p，v，代表将a[p]的值加上v，</p><p>若op=1，则之后有两个整数x0，d，代表询问</p><p>max{a[x0],a[x0+d],a[x0+2d],...,a[x0+kd]}(x0+kd&lt;=n,x0+(k+1)d&gt;n)。</p><p>数据中可能有多余空格。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每个op=1，单独输出一行，代表该等差子序列的最大值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例1】</p><p>10</p><p>1 6 1 4 9 4 8 2 8 5</p><p>10</p><p>1 3 3</p><p>0 5 4</p><p>0 3 8</p><p>1 2 5</p><p>1 4 8</p><p>1 7 5</p><p>1 3 6</p><p>0 1 2</p><p>1 5 3</p><p>1 4 9</p><p><br></p><p>【输入样例2】</p><p>10</p><p>-9 -6 2 -10 -2 -6 10 6 -4 -2</p><p>10</p><p>1 2 3</p><p>1 6 3</p><p>0 7 8</p><p>0 4 -6</p><p>0 10 -5</p><p>1 10 4</p><p>0 3 -8</p><p>1 2 4</p><p>0 10 -5</p><p>1 1 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】</p><p>8</p><p>8</p><p>4</p><p>8</p><p>9</p><p>13</p><p>4</p><p><br></p><p>【输出样例2】</p><p>6</p><p>-4</p><p>-7</p><p>-6</p><p>18</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p><p>1&lt;=n&lt;=70000，</p><p>1&lt;=m&lt;=70000，</p><p>保证任何时刻abs(a[i])(1&lt;=i&lt;=n)&lt;=2147483647，</p><p>0&lt;=op&lt;=1，</p><p>1&lt;=p&lt;=n，</p><p>abs(v)&lt;=2147483647</p><p>1&lt;=x0&lt;=n,</p><p>1&lt;=d&lt;=n，</p><p>保证涉及的所有数在C++的int内。</p><p>特殊数据：</p><p>测试点 n m 备注</p><p>0 &lt;=2000 &lt;=2000</p><p>1 &lt;=2000 &lt;=2000</p><p>2 &lt;=70000 &lt;=70000 d=1</p><p>3 &lt;=70000 &lt;=70000 d=1</p><p>4 &lt;=70000 &lt;=70000 无修改操作</p><p>5 &lt;=70000 &lt;=70000 无修改操作</p><p>6 &lt;=70000 &lt;=70000</p><p>7 &lt;=70000 &lt;=70000</p><p>8 &lt;=70000 &lt;=70000</p><p>9 &lt;=70000 &lt;=70000</p><p><br></p>
</div>
</div>