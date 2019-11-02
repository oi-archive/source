<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>怀特先生是一个大胖子。他很喜欢玩跳舞机（Dance Dance Revolution, DDR），甚至希望有一天人家会脚踏“舞蹈家怀特先生”。可惜现在他的动作根本不能称作是在跳舞，尽管每次他都十分投入的表演。这也难怪，有他这样的体型，玩跳舞机是相当费劲的。因此，他希望写一个程序来安排舞步，让他跳起来轻松一些，至少不要每次都汗流浃背。</span><br><span>　　DDR的主要内容是用脚来踩踏板。踏板有四个方向的箭头，用1 (Up)、2 (Left)、3 (Down)、4 (Right)来代表，中间位置由0来代表。每首歌曲有一个箭头序列，游戏者必须按照或这个序列一次用某一只脚踩相应的踏板。在任何时候，两只脚都不能在同一踏板上，但可以同时待在中心位置0。</span><br><span>　　每一个时刻，它必须移动而且只能移动他的一只脚去踩相应的箭头，而另一只脚不许移动。跳完一首曲子之后，怀特先生会计算他所消耗的体力。从中心移动到任何一个箭头耗费2单位体力，从任何一个箭头移动到相邻箭头耗费3单位体力，移动到相</span><span>对的箭头（1和3相对，2和4相对）耗费4单位体力，而留在原地再踩一下只需要1单位。怀特先生应该怎样移动他的双脚（即，对于每个箭头，选一只脚去踩它），才能用最少的体力完成一首给定的舞曲呢？</span><br><span>　　例如，对于箭头序列Left (2), Left (2), Up (1), Right (4)，他应该分别用左、左、右、右脚去踩，总的体力耗费为2+1+2+3=8单位。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行N，表示有N个时刻 1&lt;=N&lt;=10000</span><br><span>第二到n+1行，每行一个数，表示需要踩得版</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一个数，最小消耗体力</span></p>

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
<p>1</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>n&lt;=10000</span></p>
</div>
</div>