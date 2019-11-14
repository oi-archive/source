<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>永无乡包含 n 座岛,编号从 1 到 n,每座岛都有自己的独一无二的重要度,按照重要度可<br>以将这 n 座岛排名,名次用 1 到 n 来表示。某些岛之间由巨大的桥连接,通过桥可以从一个岛<br>到达另一个岛。如果从岛 a 出发经过若干座(含 0 座)桥可以到达岛 b,则称岛 a 和岛 b 是连<br>通的。现在有两种操作:B x y 表示在岛 x 与岛 y 之间修建一座新桥。Q x k 表示询问当前与岛<br>x 连通的所有岛中第 k 重要的是哪座岛,即所有与岛 x 连通的岛中重要度排名第 k 小的岛是哪<br>座,请你输出那个岛的编号。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>从文件 input.txt 中读入数据,输入文件第一行是用空格隔开的两个正整数 n 和 m,分别<br>表示岛的个数以及一开始存在的桥数。接下来的一行是用空格隔开的 n 个数,依次描述从岛 1<br>到岛 n 的重要度排名。随后的 m 行每行是用空格隔开的两个正整数 ai 和 bi,表示一开始就存<br>在一座连接岛 ai 和岛 bi 的桥。后面剩下的部分描述操作,该部分的第一行是一个正整数 q,<br>表示一共有 q 个操作,接下来的 q 行依次描述每个操作,操作的格式如上所述,以大写字母 Q<br>或 B 开始,后面跟两个不超过 n 的正整数,字母与数字以及两个数字之间用空格隔开。<br>对于 20%的数据 n≤1000,q≤1000<br>对于 100%的数据 n≤100000,m≤n,q≤300000</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件 output.txt 中,对于每个 Q x k 操作都要依次输出一行,其中包含一个整数,表<br />示所询问岛屿的编号。如果该岛屿不存在,则输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 1<br>4 3 2 5 1<br>1 2<br>7<br>Q 3 2<br>Q 2 1<br>B 2 3<br>B 1 5<br>Q 2 1<br>Q 2 4<br>Q 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1</p>
<p>2</p>
<p>5</p>
<p>1</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>