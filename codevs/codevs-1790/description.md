<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Pòlya 获得了一个奇妙的口袋，上面写着人类难以理解的符号。Pòlya 看得入 了迷，冥思苦想，发现了一个神奇的模型（被后人称为 Pòlya 模型)。为了生动 地讲授这个神奇的模型，他带着学生们做了一个虚拟游戏： <br>游戏开始时，袋中装入 a1个颜色为 1 的球，a2个颜色为 2 的球，…，at 个颜色为 t 的球，其中ai是正整数。 <br>游戏开始后，每次严格进行如下的操作： <br>从袋中随机的抽出一个小球（袋中所有小球被抽中的概率相等）， Pòlya 独自观察这个小球的颜色后将其放回 ，然后再把 d 个与其颜色相同 的小球放到口袋中。 <br>设 ci表示第 i 次抽出的小球的颜色  (<span style="">1</span><span style="">≤</span><span style="">c i</span><span style="">≤ </span><span style=""> </span><span style="">t </span><span style="">)</span><span style="">，一个游戏过程将会产生一个颜 色序列(c1,c2,…,cn,…)。 Pòlya 把游戏开始时 t 种颜色的小球每一种的个数 a1,a2,…,at 告诉了所有学 生。然后他问学生：一次游戏过程产生的颜色序列满足下列条件的概率有多大？</span></p>
<p><span style="">其中 0&lt;x1&lt;x2&lt;…&lt;xn ， 1≤yi≤t 。换句话说，已知(t , n , d , a1,a2,…,at , x1,y1,x2,y2,...,xn,yn)，你要回答有多大的可能性会发生下面的事件：“对所有 k,1≤k≤n，第 xk次抽出的球的颜色为 yk”。 </span></p>

<img src="/source/codevs/codevs-1790/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzkwL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NTc3MzE5Ni40NzAuNTM3MDg4OTE4NzA1LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有三个正整数 t，n，d ；<br>第二行有 t 个正整数 a1,a2,…,at，表示游戏开 始时口袋里 t 种颜色的球，每种球的个数。 <br>以下 n 行，每行有两个正整数 xi,yi，表示第 xi次抽出颜色为的 yi球。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>要求用分数形式输出（显然此概率为有理数）。输出文件包含一行，格式为： 分子/分母。同时要求输出最简形式（分子分母互质）。特别的，概率为 0 应输出<span style="font-size: 10px;">0/1，概率为 1 应输出 1/1。</span></p>
<p>&nbsp;</p>
<p><span style="font-size: 10px;"><br /></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>样例 1 的输入</span></p>
<p><span>2 3 1</span></p>
<p><span>1 1</span></p>
<p><span>1 1</span></p>
<p><span>2 2</span></p>
<p><span>3 1 </span></p>
<p>样例 2 的输入</p>
<p>3 1 2</p>
<p>1 1 1</p>
<p>5 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例 1 的输出  1/12 </p>
<p>样例 2 的输出  1/3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤t,n≤1000, 1≤ak ,d≤10, 1≤x1&lt;x2&lt;…&lt;xn≤10000, 1≤yk≤t</p>
<p>【样例 1 说明】 <br>初始时，两种颜色球数分别为(1, 1)，取出色号为 1 的球的概率为 1/2；第二 次取球之前，两种颜色球数分别为(2, 1)，取出色号为 2 的球的概率为 1/3；第三 次取球之前，两种颜色球数分别为(2, 2)，取出色号为 1 的球的概率为 1/2，所以 三次取球的总概率为 1/12。</p>
</div>
</div>