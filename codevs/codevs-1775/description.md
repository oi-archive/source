<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>　　黑板上有n个数字X<sub>1</sub>，X<sub>2</sub>，X<sub>3</sub>，……X<sub>n，男主和女主玩起了数字游戏</sub>。</div>
<div>　　女主和男主轮流对其中一个数进行游戏操作：</div>
<div>　　将X<sub>i</sub>改为区间<strong>[</strong>(X<sub>i</sub>+1)/2,X<sub>i </sub><strong>)</strong>中的一个数。(除法向下取整，区间左闭右开)</div>
<div>　　如果这个数变成了1，便将其擦去(优先于人物操作)，<strong>无法修改数字的人失败</strong>。
<div> </div>
<div>　　男主希望女主在双方均采取最优策略的情况下永远取得胜利。</div>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>　　第一行为一个正整数n，代表数字个数。</div>
<div>　　第二行为n个正整数，代表X<sub>1</sub>，X<sub>2</sub>，X<sub>3</sub>，……X<sub>n</sub>这n个数字。</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<div>　　如果从女主开始游戏，女主可以获胜，输出"Lady First" (不含引号)，表示男主将主动权让给了女主。</div>
<div>　　否则必须是从男主开始，女主才能获胜，输出"You Are An Apple of My Eyes" (不含引号)，表示男主赞美了女主之后才能获得主动权。</div>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】<br>1<br>5201314</p>
<p> </p>
<p>【样例输入2】<br>6<br>20 13 3 22 17 25</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】<br>Lady First</p>
<p>【样例输出2】<br>You Are An Apple of My Eyes</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围与约定】</p>
<p>　　对于100%的数据，1 ≤ n ≤ 520，1 ≤ a<sub>i</sub> ≤ 10<sup>18</sup>。</p>
<p> </p>
<p>【来源】</p>
<p>　　2013年3月24日白色情人节欢乐赛Day2T1。</p>
</div>
</div>