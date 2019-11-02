<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小 Victor 在二次元看到了许多他喜欢的人物（比如 Saber,阿尔托莉雅·潘 德拉贡，亚瑟王....），小 Victor 对于二次元人物都有自己的看法，即可以用 i 表示该人物对于他本身的吸引力，用 j 表示 findstr 魔王对其安利程度，同 时他又有自己的判断，我们可以用 A 和 B 来表示，所以我们定义一个人物对小 Victor 的吸引度为 Ai+Bj,然而小 Victor 并不是什么人物都感兴趣的，他只会 去关注那些吸引度对他大于 C 的人物。  然而求小 Victor 到底去关注多少个人物对于大家来说太简单了，所以 findstr 大魔王决定使坏。我们定义每个人物会有一个使小 Victor 入宅的入宅 度 v[x]，findstr 大魔王会随时给小 Victor 安利奇怪的人物，假设为(i,j)， 由于他口才很好，他会对小 Victor 造成一次口才度为 R 的精神辐射，即他会让 所有(i`,j`)（i`,j`为已加入点）[sqr(i`-i)+sqr(j`-j)&lt;=R*R]的点的入宅度都加上 delta。  然而小 Victor 也是会变化自己的口味的，现在请你求出每一次他变化口味 时总入宅度是多少（当然只有他关注的人物才会产生入宅度）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数 m，表示一共有 m 次操作 接下来 m 行，每行包含一个字符串和一些数字，现在格式如下 Insert I j R delta 表示 findstr 大魔王给小 Victor 安利了本身对他吸引 度为 I,安利程度为 j 的人物，并造成口才度为 R 的精神辐射（如题意） Query A B C 表示询问当小 Victor 的口味发生变化时，他的总入宅度是多少？ 此题强制在线，每一次的所有数字异或（xor/^）lastans，一开始 lastans=0， 之后 lastans 为上一次询问的答案</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个 Query 操作你需要输出一个整数表示答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p><p>Insert 1 1 0 1</p><p>Insert 2 2 0 1</p><p>Insert 3 3 2 1</p><p>Query 1 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30%的数据 m&lt;=5000 对于 60%的数据 m&lt;=50000 对于 100%的数据 m&lt;=100000 对于 100%的数据|A|,|B|,|C|,|delta|,|R|,|I|,|J| &lt;= 10^9</p>
</div>
</div>