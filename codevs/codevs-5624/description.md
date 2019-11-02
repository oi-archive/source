<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>六十年一次的魔法战争就要开始了，大魔法师准备从附近的魔法场中汲取魔法能量。</p><p>大魔法师有m个魔法物品，编号分别为1,2,...,m。每个物品具有一个魔法值，我们用Xi表示编号为i的物品的魔法值。每个魔法值Xi是不超过n的正整数，可能有多个物品的魔法值相同。</p><p>大魔法师认为，当且仅当四个编号为a,b,c,d的魔法物品满足xa&lt;xb&lt;xc&lt;xd，Xb-Xa=2(Xd-Xc)，并且xb-xa&lt;(xc-xb)/3时，这四个魔法物品形成了一个魔法阵，他称这四个魔法物品分别为这个魔法阵的A物品，B物品，C物品，D物品。</p><p>现在，大魔法师想要知道，对于每个魔法物品，作为某个魔法阵的A物品出现的次数，作为B物品的次数，作为C物品的次数，和作为D物品的次数。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包含两个空格隔开的正整数n和m。</p><p>接下来m行，每行一个正整数，第i+1行的正整数表示Xi，即编号为i的物品的魔法值。</p><p>保证<img src="http://latex.codecogs.com/gif.latex?1 \le n \le 15000">,<img src="http://latex.codecogs.com/gif.latex?1 \le m \le 40000">,<img src="http://latex.codecogs.com/gif.latex?1 \le Xi \le n">。每个Xi是分别在合法范围内等概率随机生成的。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共输出m行，每行四个整数。第i行的四个整数依次表示编号为i的物品作 为A,B,C,D物品分别出现的次数。</p><p>保证标准输出中的每个数都不会超过10^9。</p><p>每行相邻的两个数之间用恰好一个空格隔开。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>15 15<br>1 <br>2 <br>3 <br>4 <br>5<br>6 <br>7 <br>8 <br>9<br>10<br>11<br>12<br>13<br>14<br>15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5 0 0 0<br>4 0 0 0<br>3 5 0 0<br>2 4 0 0<br>1 3 0 0<br>0 2 0 0<br>0 1 0 0<br>0 0 0 0<br>0 0 0 0<br>0 0 1 0<br>0 0 2 1<br>0 0 3 2<br>0 0 4 3<br>0 0 5 4<br>0 0 0 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><img src="/source/codevs/codevs-5624/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01NjI0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2VfMjAxNjExMjYyMDI1MjVfMjI0LnBuZw==.png" title=""></p>
</div>
</div>