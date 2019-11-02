<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       小蛮要过生日了，她决定邀请一些朋友参加她的生日宴会，但又不知道邀请谁好。</p>
<p>       于是小蛮列了一个清单，她有N个朋友，其中有M对朋友相互认识。对于一个朋友来说，如果聚会上他不认识的人太少，他会觉得交不到太多新朋友，于是他就不会参加聚会；相反如果他认识的人太少，他就会觉得很孤独，也不会参加聚会。于是只有当一个朋友认识的人不少于A个，不认识的人不少于B个，他才会参加聚会。</p>
<p>       现在小蛮想知道她最多可以邀请多少人来到她的聚会。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><strong>输入数据包含多组测试数据。</strong></p>
<p>第一行包含一个整数T，表示测试数据的组数。</p>
<p>对于每组测试数据，第一行包含四个整数N、M、A、B，含义如题目所述。</p>
<p>接下来M行，每行两个整数A、B，表示第A个朋友与第B个朋友认识。</p>
<p>输入数据保证同一对朋友不会重复给出。</p>
<p><strong>由于输入数据可能很大，所以建议采用快速的输入方式。</strong></p>
<p><strong><br></strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组测试数据，输出一个整数，表示最多可以邀请到的朋友数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>1 0 0 0</p>
<p>5 7 1 1</p>
<p>2 4</p>
<p>1 3</p>
<p>5 2</p>
<p>3 2</p>
<p>5 4</p>
<p>4 3</p>
<p>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据，N ≤ 1000，M ≤ 3000；</p>
<p>70%的数据，N ≤ 50000；</p>
<p>80%的数据，M ≤ 120000；</p>
<p>100%的数据，N ≤ 100000，M ≤ 500000，T ≤ 3，任意输入整数不超过10<sup>9</sup>。</p>
</div>
</div>