<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>      <span>小X从美国回来后，成为了</span><span>USACO中国区的奶牛销售代理商，专门出售质优价廉的“FJ”牌奶牛，因此生意很好。</span></span></p>
<p><span><span>      为了提高牛奶蛋白质含量，有效提升品牌效应，切实巩固市场地位，经元首科学院专家研究，决定对奶牛采用智力训练的方式。也就是说，训练奶牛大脑以提高牛奶蛋白质含量。</span></span></p>
<p><span><span>      呃，怎么办呢？小X想到了一个好办法，给奶牛一串数列，保证小于100个，每个数是-100到100之间的整数，让奶牛求出最后一个数的下一个和包括求出数的该数列和S（S大小不保证）。</span></span></p>
<p><span><span>      比如，给奶牛一串数列：6(表示有几个)</span></span></p>
<p><span><span>                                       1 2 3 4 5 6（每个元素）</span></span></p>
<p><span><span>      奶牛会告诉你               7（6下一个元素）</span></span></p>
<p><span><span>                                      28（1+2+...+7的和）</span></span></p>
<p><span><span>     对了，由于奶牛智力有限，因此各项规律只有+、-、*、平方、+-、+*、-*</span></span></p>
<p><span><span><br></span></span></p>
<p><strong>    计算机界的终极梦想！逻辑判断！模拟人脑思考！分数至少应该1000！</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：一个正整数N</p>
<p>第二行：N个正整数</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>这个数列从逻辑角度判断的第N+1项。</p>
<p>第1到N+1项的和</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>1 2 3 4 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>28</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> 只有一句话：准备高精度吧！平方有你算的。</p>
<p>奶牛代理商III原题是坑爹逻辑题，不予评论，修改一下。原题奉上：</p>
<p>小X设计了一个n*n的巨大牛棚（2&lt;=n&lt;=100）,因此所有奶牛都可以舒舒服服地住在每一个格子里。但是，她发现所拥有的奶牛远远少于N*N，因此她和员工们不得不费力地寻找每一头奶牛，尽管它们都不会动。</p>
<p>      小X想到了<strong>坐标</strong>，如图，线外是坐标，则“*”住坐标为（0，0）在本例中，没有牛标记为零，有牛则标记为一，则该图无牛处坐标为（0，1）：</p>
<p>1 |0 1</p>
<p>0 |* <span>1 </span></p>
<p>   0  1</p>
<p>     在各种大小的牛棚中，都是<strong>以本例中的“*”为始发点（即为左下角）</strong>，注意这个“<strong>*”也可以住牛</strong>。员工们可以向8个方向（上、下、左、右、左上、左下。右上、右下）走，每次一格，当然啦，要视情况而定。</p>
<p>    小X想知道，在这个牛棚中，在走<strong>的步数尽量小</strong>的情况下，怎样找出一条<strong>不重复</strong>的路，让她可以一次从“*”处找到所有牛？如果不行，请你输出“No!”</p>
<p><strong>请注意：只要不是全符合如下条件的，输出“No！”：</strong></p>
<p><strong>不能重复经过某一牛棚；</strong></p>
<p><strong>没有多种而步数一样的路；</strong></p>
<p><strong>没有的牛棚到达不了的；</strong></p>
<p><strong>没有走完所有牛棚就没法走的；</strong></p>
</div>
</div>