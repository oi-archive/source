<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>危机纪元200年，四体星球大举进攻地球。在太阳系防卫舰队被水滴打击全军覆没以后，人类离死亡只有一步之遥。这时候，勇敢的手雷出现了！得知这个消息后，<strong><em>他恼怒了</em></strong>，但是他并没有离开，而是毅然担任起了面壁者和执剑人的重任，决定保卫地球。经过了999次的失败，他总结出了“黑暗森林”理论和宇宙文明的四条公理，只要按照一定的方法填写出一个矩阵，就可以向宇宙公布四体星球的坐标，进行黑暗森林打击。</p><p>首先，将四体星球的坐标用1表示，填在第一行正中间；接着，按如下方式从小到大依次填写每个数K(K=2,3,…,N*N) ：</p><p>公理一. 若(K−1) 在第一行但不在最后一列，则将K填在最后一行，
(K−1) 所在列的右一列； </p><p>公理二. 若(K−1) 在最后一列但不在第一行，则将K填在第一列，(K−1)
所在行的上一行；</p><p>公理三. 若(K−1) 在第一行最后一列，则将K 填在(K−1) 的正下方；</p><p>公理四.若(K−1) 既不在第一行，也不在最后一列，如果(K−1) 的右
上方还未填数，则将K填在(K−1)的右上方，否则将K填在(K−1)
的正下方。</p><p style=""><em><strong>不要害怕。这其实并不是什么难事，因为它只比周末卷难一点点。</strong></em></p><p>不过，手雷不擅长电脑编程，因此，他需要你的帮助。去吧，手雷，打败邪恶的四体人，地球的未来，就靠你来守卫了！<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件只有一行，包含一个整数N，即矩阵的大小。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件包含N行，每行N个整数，即按上述方法构造出的N*N的矩阵。相邻两个整数之间用单个空格隔开</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8 1 6 </p><p>3 5 7 </p><p>4 9 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤N≤39 且 N 为奇数。</p>
</div>
</div>