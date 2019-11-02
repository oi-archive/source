<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">有个同学（编号为</span> 1 <span style="">到）正在玩一个信息传递的游戏。在游戏里每人都有一个</span><span style="">固定的信息传递对象，其中，编号为的同学的信息传递对象是编号为的同学。</span><span style="">游戏开始时，每人都只知道自己的生日。之后每一轮中，所有人会同时将自己当前</span><span style="">所知的生日信息告诉各自的信息传递对象（注意：可能有人可以从若干人那里获取信息，</span><span style="">但是每人只会把信息告诉一个人，即自己的信息传递对象）。当有人从别人口中得知自</span><span style="">己的生日时，游戏结束。请问该游戏一共可以进行几轮？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入共</span> 2<span style="">行。</span></p><p><span style="">第</span> 1<span style="">行包含</span>1<span style="">个正整数</span>n<span style="">，表示</span>n<span style="">个人</span></p><p><span style="">第</span> 2 <span style="">行包含</span>n <span style="">个用空格隔开的正整数</span>T1 ,T 2 ,<span style="">……</span>,Tn <span style="">，</span> <span style="">其中第</span>i<span style="">个整数</span>Ti<span style="">表示编号为</span>i</p><p><span style="">的同学的信息传递对象是编号为</span> T i <span style="">的同学，</span>Ti<span style="">≤</span>n <span style="">且</span> Ti<span style="">≠</span>i<span style="">。</span></p><p><span style="">数据保证游戏一定会结束。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">输出共</span> 1<span style="font-family:宋体">行，包含</span>&nbsp; 1<span style="font-family:宋体">个整数，表示游戏一共可以进行多少轮。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>2 4 2 3 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style=""></span></p><p><span style="">【输入输出样例</span> 1 <span style="">说明】</span></p><p><span style="">游戏的流程如图所示。当进行完第</span> 3 <span style="">轮游戏后，</span>4 <span style="">号玩家会听到</span> 2 <span style="">号玩家告诉他自</span><span style="">己的生日，所以答案为</span> 3<span style="">。当然，第</span> 3 <span style="">轮游戏后，</span>2 <span style="">号玩家、</span>3 <span style="">号玩家都能从自己的消息</span><span style="">来源得知自己的生日，同样符合游戏结束的条件。</span></p><p><br></p><p><span style=""><br></span></p><p><span style="">对于</span> 30%<span style="">的数据，</span>    ≤ 200<span style="">；</span></p><p><span style="">对于</span> 60%<span style="">的数据，</span>    ≤ 2500<span style="">；</span></p><p><span style="">对于</span> 100%<span style="">的数据，</span>    ≤ 200000<span style="">。</span></p><p><br></p>
</div>
</div>