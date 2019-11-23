<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: Fixedsys;">隔壁老王为了飞去隔壁，骑着会下蛋的</span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys; text-decoration: none;">鸡</span><span style="font-family: Fixedsys;">去天上灰（很2B……）。在高空中突然，他发现他的</span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys;">鸡下蛋了（可以吃么~），然后蛋掉到地上，碎掉了（好可惜，没有蛋吃了……）</span><br style="font-family: Fixedsys;"><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">隔壁老王很生气，他想知道</span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys;">鸡蛋的硬度，于是开始做实验，想知道在多高的空中飞行，</span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys;">鸡下蛋落地，蛋不会碎掉……</span><br style="font-family: Fixedsys;"><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">隔壁老王花了很大功夫，骑着</span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys;">鸡飞在不同的高度，往下丢公鸡的蛋（都是平时生的，圣诞老人好残忍）……</span></p><p><span style="font-family: Fixedsys; text-decoration: underline;">———————————以上内容根本题没有任何关系,下面开始正文———————————</span><br></p><p><span style="font-family: Fixedsys;"><span style="font-family: Fixedsys;"></span></span></p><hr><p><span style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">给定2个数字，一个是隔壁老王</span>在天上的高度H，一个是</span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys;">鸡蛋的个数K……</span></p><p><span style="font-family: Fixedsys;"><br style="font-family: Fixedsys;">如果</span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">鸡蛋的硬度是N，那么</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">当</span></span><span style="font-family: Fixedsys; text-decoration: line-through;">公</span><span style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">鸡蛋从N层楼及以下楼层落下时是不会碎的(因为结实)，但是第N+1层楼和以上的楼层掉落就摔坏了（当然，公鸡蛋的数量就少了一个）如果公鸡蛋没有摔坏掉，那还可以继续使用。</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">（如果只有一个蛋的话，那么可以从第一层慢慢实验……）</span><br style="font-family: Fixedsys;"><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">例如：从第一层一层一层的实验，如果公鸡蛋从1楼掉下就坏了，N=1；</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">如果公鸡蛋从第E楼摔坏了，N=E。</span><br style="font-family: Fixedsys;"><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">这里假设所有的公鸡蛋都具有相同的硬度。给定公鸡蛋个数 K 和楼层高度 H，（H,K&lt;=1000）,已知蛋的硬度不超过 H+1，求最坏情况下，用最牛 B 的方法，确定 N 所需的最少实验次数。</span><br style="font-family: Fixedsys;"><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">例如，如果只有一个蛋，唯一的方法就是把它先从 1 楼扔下去，再从 2 楼……直到蛋碎掉，这样需要扔 H 次才能确定蛋的硬度。然而如果蛋的个数大于 1，显然有更好的方法……</span></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Fixedsys;">两个自然数K和H(0&lt;=K,H&lt;=1000)</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(50, 101, 109); font-family: Fixedsys; font-size: 14px; line-height: 18px; background-color: rgb(255, 255, 255);">一个数，就是要多少次得到蛋硬度</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>每个数据点1s<br></p>
</div>
</div>