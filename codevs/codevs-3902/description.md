<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这是一个魔幻的游戏机，魔幻的游戏机里有N个普通的球槽：1号，2号……N号；和M个魔幻的单向轨道Ai---Bi，表示小球可以从Ai号球槽滚动到Bi号球槽，但不可以按这条魔幻的单向轨道滚回来。可能存在这样的情况，小球从某个球槽开始滚动，通过若干次魔幻的单向轨道，又回到了原先的球槽，很显然这不满足能量守恒定律，这就是单向轨道以及游戏机的魔幻所在了。</p><p>当小球处在x号球槽时，设有k条单向轨道：x---yi，0&lt;i&lt;=k，那么小球会绝对随机地从x号球槽滚向某个yi号球槽，即滚到任一球槽的概率是1/k。如果k=0，那么小球只能停留在原地x号球槽不动。</p><p>初始，小球在1号球槽，最后停留在了某个球槽，显然具体会留在哪个球槽的可能性不是唯一的。作为一台魔幻的游戏机，作为一个游戏，你需要猜测最后小球所停留的球槽具体是哪个，你当然会选择一个概率最大的球槽，你想知道你猜对的期望概率是多大。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，正整数N和非负整数M。</p><p>接下来M行，每行有序正整数对A，B，表示A号地点到B号地点有一条单向魔幻轨道。</p><p>如果把这些信息看作图，即球槽看做点，轨道看做有向边，那么数据保证不会有重边和自环。另外保证小球有停留的可能性。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，一个实数，即当猜选某个球槽时，最大的猜对期望概率，应该保留6位小数。不需要输出猜哪个球槽时有最大的猜对期望概率。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 8</p><p>1 2</p><p>1 3</p><p>3 2</p><p>3 1</p><p>3 4</p><p>1 5</p><p>5 6</p><p>6 5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.800000</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>实际上，小球可能最终停留在2号球槽，4号球槽或在5号和6号球槽之间“徘徊”，概率比是4:1:3。但是，由于已知小球已经停留在某个球槽，故猜选2号球槽时猜对的期望概率最大，为4/(4+1)=0.8。</p><p>1&lt;=N&lt;=45，1&lt;=A&lt;=N，1&lt;=B&lt;=N。</p><p><br></p>
</div>
</div>