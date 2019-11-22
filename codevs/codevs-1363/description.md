<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       有<em>N</em>个村庄坐落在一条直线上，第<em>i</em>(<em>i</em>&gt;1)个村庄距离第1个村庄的距离为<em>D<sub>i</sub></em>。需要在这些村庄中建立不超过<em>K</em>个通讯基站，在第<em>i</em>个村庄建立基站的费用为<em>C<sub>i</sub></em>。如果在距离第<em>i</em>个村庄不超过<em>S<sub>i</sub></em>的范围内建立了一个通讯基站，那么就成它被覆盖了。如果第<em>i</em>个村庄没有被覆盖，则需要向他们补偿，费用为<em>W<sub>i</sub></em>。现在的问题是，选择基站的位置，使得总费用最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件的第一行包含两个整数<em>N</em>,<em>K</em>，含义如上所述。</p>
<p>       第二行包含<em><span style="text-decoration: underline;">N</span></em><span style="text-decoration: underline;">-1</span>个整数，分别表示<em>D</em><sub>2</sub>,<em>D</em><sub>3</sub>,…,<em>D<sub>N</sub></em> ，这<em>N</em>-1个数是<span style="text-decoration: underline;">递增</span>的。</p>
<p>       第三行包含<em>N</em>个整数，表示<em>C</em><sub>1</sub>,<em>C</em><sub>2</sub>,…<em>C<sub>N</sub></em>。</p>
<p>       第四行包含<em>N</em>个整数，表示<em>S</em><sub>1</sub>,<em>S</em><sub>2</sub>,…,<em>S<sub>N</sub></em>。</p>
<p>       第五行包含<em>N</em>个整数，表示<em>W</em><sub>1</sub>,<em>W</em><sub>2</sub>,…,<em>W<sub>N</sub></em>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中仅包含一个整数，表示最小的总费用。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2</p>
<p>1 2</p>
<p>2 3 2</p>
<p>1 1 0</p>
<p>10 20 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>       4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>40%的数据中，<em>N</em>&lt;=500；</p>
<p>100%的数据中，K&lt;=N，K&lt;=100，N&lt;=20,000，D<sub>i</sub>&lt;=1000000000，C<sub>i</sub>&lt;=10000，S<sub>i</sub>&lt;=1000000000，W<sub>i</sub>&lt;=10000。</p>
</div>
</div>