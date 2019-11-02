<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>生物课上，老师开始为同学们介绍细胞。为了加深同学们的印象，老师在一张<em>N</em>×<em>M</em>的矩阵中定义了一种细胞，矩阵中仅有井号“#”和点“.”：</p>
<p>细胞由细胞核、细胞质及细胞膜构成。细胞核是一个4连通（上下左右相连）的全为“#”的连通块，它必须实心，即不能存在一个4连通的“.”连通块被其完全包围（所谓完全包围指的是，这个“.”连通块不能位于矩阵边界相邻，且它的4相邻格子均属于包含它的“#”连通块）。细胞膜是一个8连通（上下左右，以及4个对角方向）的全为“#”的非实心连通块。细胞膜仅包围一个4连通的区域，且这个区域内有且仅有一个细胞核，这个区域剩下的位置全为“.”。</p>
<p>所有连通块必须极大化，即一个8连通块周围不能找到一个“#”与这个连通块的任意一个“#”8连通；同样，对于一个4连通块周围不能找到一个“#”与这个连通块的任意一个“#”4连通。</p>
<p>现在，老师画了一幅图画，并让小E回答图画中一共有几个细胞，并把图画中不属于任何一个细胞的“#”改成“.”。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个用空格分隔的正整数<em>N</em>和<em>M</em>，表示矩阵的高和长。</p>
<p>接下来一个<em>N</em>行<em>M</em>列的矩阵，矩阵中仅含井号“#”和点“.”，保证没有多余字符。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出第一行包含一个整数，表示输入的矩阵中的细胞数。</p>
<p>接下来一个<em>N</em>行<em>M</em>列的矩阵，矩阵中仅含井号&ldquo;#&rdquo;和点&ldquo;.&rdquo;，表示更改后的图画。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>12 13</p>
<p>.###..#####..</p>
<p>#...#.#....#.</p>
<p>#.#.#.#..#.#.</p>
<p>#...#..#...#.</p>
<p>.###.#..###..</p>
<p>....#..##...#</p>
<p>..........###</p>
<p>##########..#</p>
<p>#...........#</p>
<p>#.###...###.#</p>
<p>#...........#</p>
<p>#############</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>......#####..</p>
<p>......#....#.</p>
<p>......#..#.#.</p>
<p>.......#...#.</p>
<p>........###..</p>
<p>.......##....</p>
<p>.............</p>
<p>.............</p>
<p>.............</p>
<p>.............</p>
<p>.............</p>
<p>.............</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于20%的数据，满足1 ≤ <em>N</em>, <em>M </em>≤ 20。</p>
<p>另有20%的数据，满足所有“#”都属于某一个正确的细胞。</p>
<p>对于100%的数据，满足1 ≤ <em>N</em>, <em>M </em>≤ 1,000。</p>
</div>
</div>
</div>