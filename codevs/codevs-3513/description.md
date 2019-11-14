<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>阿良良木火怜 &amp; 阿良良木月火 不甘心被哥哥（阿良良木历）收入后宫！为了让哥哥脑部构造奇特，他们想到了利用核武器，希望辐射波越多越好。<br>辐射装置是一个四维的跟个魔方一样的东西，分成A*B*C*D个格子，每个格子都处于两种状态中的一种。<br>当且仅当两个格子相邻且状态不同时，才可以产生辐射波，设这两个格子坐标分别为(x1,y1,z1,w1)和(x2,y2,z2,w2)，则这对格子产生的辐射量为f(x1,y1,z1,w1,x2,y2,z2,w2)    (1&lt;=f&lt;=10)。<br>（不要告诉我你不知道”相邻”是什么，就是坐标差的绝对值之和为1）<br>整个核武器的辐射量为上述之和（一个格子会跟相邻的所有状态不同的格子产生能量，但一对格子只会被算一次，也就是说描述这对格子的二元组是无序的）。<br>某些格子的状态是已经被固定的了，另外的格子则可以在两者中选择一种作为状态（必须选择一种）。<br>请输出最后辐射波的最大值</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行四个数A,B,C,D<br>接下来有5个类似的数据块：<br>接下来A*B*C行，每行D个数，每个数描述一个格子（顺序按照A为第一关键字，B为第二关键字，C为第三关键字，D为第四关键字），若为1则表示已经被固定成第一种状态；若为2则表示已经被固定成第二种状态；若为0则表示可以由你选择。<br></p><p>接下来又是A*B*C行，每行D个数，每个数描述一个格子（顺序跟上面的一样），描述(x,y,z,w)这个格子的数表示的是f(x,y,z,w,x+1,y,z,w)的值；<br></p><p>接下来还是A*B*C行，每行D个数，每个数描述一个格子（顺序跟上面的一样），描述(x,y,z,w)这个格子的数表示的是f(x,y,z,w,x,y+1,z,w)的值；<br>接下来还还是A*B*C行，每行D个数，每个数描述一个格子（顺序跟上面的一样），描述(x,y,z,w)这个格子的数表示的是f(x,y,z,w,x,y,z+1,w)的值；<br>接下来还还还是A*B*C行，每行D个数，每个数描述一个格子（顺序跟上面的一样），描述(x,y,z,w)这个格子的数表示的是f(x,y,z,w,x,y,z,w+1)的值；<br>若给出的f的参数(比如x+1&gt;A了)超出边界范围，则此值无意义，请忽略之<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数表示最大辐射量</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1 2 2<br>1 0 <br>2 0 <br> <br>0 0 <br>0 0 <br> <br>0 0 <br>0 0 <br> <br>7 4 <br>0 0 <br> <br>4 0 <br>9 0</p><p><br></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Calibri;">24</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%数据，A*B*C*D&lt;=16<br>对于60%数据，A*B*C*D&lt;=10000<br>对于100%数据，1&lt;=A,B,C,D&lt;=16，1&lt;=每个f&lt;=10（数据范围真小啊），输入都是整数<br></p>
</div>
</div>