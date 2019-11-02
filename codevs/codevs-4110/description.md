<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>     TTY是个富有诗意的男孩。在他居住的小镇上，有n个村庄，由n – 1条道路连接着。这里的生活和谐而又宁静。有一天TTY偶然阅读到一篇杂志上的文章《阳光下的向日葵》，深受感动。特别是其中一位小女孩的故事让他记忆犹新。于是他买来葵花籽，决定也像那位小女孩一样，给村民播种向日葵，把美丽和阳光带给村庄里的每一个人。</p><p>     于是TTY决定在每次播种前选择两个村庄，然后从其中一个村庄出发，在这两个村庄的道路上的每一个村庄（包括起始点）种上一颗向日葵，在编号i的村庄播种在可以长出Wi个葵花籽，而且向日葵受到天神Owaski的保护，在生长过程中不会被人采摘。若干天后，待到向日葵成熟时，TTY又会以相同的路径去采摘那些向日葵上的葵花籽，无论是否采摘，每一次播种的向日葵都会在下一次播种前死亡。但是有轻微强迫症的他，不会采摘比他采摘的上一朵葵花籽相等或者更少的向日葵。而TTY并不知道这些数据，只能凭着感觉开始采摘，他想在更多的向日葵上采摘葵花籽，你能告诉他可以最多采摘的向日葵棵数吗？ </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，代表村庄个数</p><p>接下来n – 1行，每行两个整数x, y，代表x和村庄y之间有道路相连</p><p>接下来一行n个整数W1 … Wn，代表每个村庄的可以长出的葵花籽数目</p><p>接下来一行一个整数q，代表询问个数</p><p>接下来q行，每行两个整数s, t，代表播种的起点和终点</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共q行，每行一个整数，第i行代表第i次播种可以收获的最多葵花棵数（不是葵花籽数）。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>2 1</p><p>3 2</p><p>4 2</p><p>5 4</p><p>6 6 9 4 6</p><p>3 </p><p>1 2</p><p>4 1</p><p>1 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p><p>2</p><p>2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：</p><p>对于第一个询问，路径为1 -&gt; 2，可以采摘其中任意一个</p><p>对于第二个询问，路径为4 -&gt; 2 -&gt; 1，可以先采摘4，后采摘2和1中任意一个</p><p>对于第三个询问，路径为1 -&gt; 2 -&gt; 3，可以先采摘1和2 中任意一个，后采摘3</p><p><br></p><p>数据范围：  <img src="/source/codevs/codevs-4110/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MTEwL2h0dHBzOi8vZG4tY29kZXZzLXRlc3RpbmcucWJveC5tZS9pbWcvQl9EYXRhX1JhbmdlLnBuZz9pbWFnZVZpZXcyLzIvdy83MDA=.png"></p><p><br></p>
</div>
</div>