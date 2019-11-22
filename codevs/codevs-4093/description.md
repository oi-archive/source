<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">由于外国间谍的大量渗入，学校安全正处于高度的危机之中。YJY决定挺身而作出反抗。如果</span>A<span style="">间谍手中掌握着关于</span>B<span style="">间谍的犯罪证据，则称</span>A<span style="">可以揭发</span>B<span style="">。有些间谍收受贿赂，只要给他们一定数量的美元，他们就愿意交出手中掌握的全部情报。所以，如果我们能够收买一些间谍的话，我们就可能控制间谍网中的每一分子。因为一旦我们逮捕了一个间谍，他手中掌握的情报都将归我们所有，这样就有可能逮捕新的间谍，掌握新的情报。</span></p><p><span style="">　　我们的神通广大的YJY获得了一份资料，色括所有已知的受贿的间谍，以及他们愿意收受的具体数额。同时我们还知道哪些间谍手中具体掌握了哪些间谍的资料。假设总共有</span>n<span style="">个间谍</span>(n<span style="">不超过</span>3000)<span style="">，每个间谍分别用</span>1<span style="">到</span>3000<span style="">的整数来标识。</span></p><p><span style="">　　请根据这份资料，判断我们是否有可能控制全部的间谍，如果可以，求出我们所需要支付的最少资金。否则，输出不能被控制的一个间谍。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行只有一个整数</span>n<span style="">。</span></p><p><span style="">　　第二行是整数</span>p<span style="">。表示愿意被收买的人数，</span>1<span style="">≤</span>p<span style="">≤</span>n<span style="">。</span></p><p><span style="">　　接下来的</span>p<span style="">行，每行有两个整数，第一个数是一个愿意被收买的间谍的编号，第二个数表示他将会被收买的数额。这个数额不超过</span>20000<span style="">。</span></p><p><span style="">　　紧跟着一行只有一个整数</span>r<span style="">，</span>1<span style="">≤</span>r<span style="">≤</span>8000<span style="">。然后</span>r<span style="">行，每行两个正整数，表示数对</span>(A, B)<span style="">，</span>A<span style="">间谍掌握</span>B<span style="">间谍的证据。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">如果可以控制所有间谍，第一行输出</span>YES<span style="font-family:宋体">，并在第二行输出所需要支付的贿金最小值。否则输出</span>NO<span style="font-family:宋体">，并在第二行输出不能控制的间谍中，编号最小的间谍编号。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例</span>1<span style="">】</span></p><p>3</p><p>2</p><p>1 10</p><p>2 100</p><p>2</p><p>1 3</p><p>2 3</p><p><span style="">【样例</span>2<span style="">】</span></p><p>4</p><p>2</p><p>1 100</p><p>4 200</p><p>2</p><p>1 2</p><p>3 4</p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例</span>1<span style="">】</span></p><p>YES</p><p>110</p><p> </p><p><span style="">【样例</span>2<span style="">】</span></p><p>NO&lt;a name="_GoBack"&gt;&lt;/a&gt;</p><p>3</p><p><br></p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">各个测试点</span>1s</p><p><br></p><p><br></p><p>友情提示：请先膜拜下万能的YJY再做呦^_^</p>
</div>
</div>