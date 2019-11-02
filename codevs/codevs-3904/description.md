<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出如下定义：</p><ol style=""><li><p>子矩阵：从一个矩阵当中选取某些行和某些列交叉位置所组成的新矩阵（保持行与 列的相对顺序）被称为原矩阵的一个子矩阵。<br>例如，下面左图中选取第 2、4 行和第 2、4、5 列交叉位置的元素得到一个 2*3 的子矩阵如右图所示。<br><br></p></li><li><p>相邻的元素：矩阵中的某个元素与其上下左右四个元素（如果存在的话）是相邻的。</p></li><li><p>矩阵的分值：矩阵中每一对相邻元素之差的绝对值之和。</p></li></ol><p>本题任务：给定一个 n 行 m 列的正整数矩阵，请你从这个矩阵中选出一个 r 行 c 列的 子矩阵，使得这个子矩阵的分值最小，并输出这个分值。</p><p><br></p>

<img src="/source/codevs/codevs-3904/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zOTA0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8zOTA0LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含用空格隔开的四个整数 n，m，r，c，意义如问题描述中所述，每两个整数之间用一个空格隔开。</p><p>接下来的 n 行，每行包含 m 个用空格隔开的整数，用来表示问题描述中那个 n 行 m 列的矩阵。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共 1 行，包含 1 个整数，表示满足题目描述的子矩阵的最小分值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<h3 style="">样例输入1</h3><p>5 5 2 3<br></p><p>9 3 3 3 9</p><p>9 4 8 7 4</p><p>1 7 4 6 6</p><p>6 8 5 6 9</p><p>7 4 5 6 1</p><p><br></p><h3 style="">样例输入2</h3><p>7 7 3 3</p><p>7 7 7 6 2 10 5</p><p>5 8 8 2 1 6 2</p><p>2 9 5 5 6 1 7</p><p>7 9 3 6 1 7 8</p><p>1 9 1 4 7 8 8</p><p>10 5 9 1 1 8 10</p><p>1 3 1 5 4 8 6</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<h3 style="">样例输出1</h3><p>6<br></p><p><br></p><h3 style="">样例输出2</h3><p>16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 50%的数据，1 ≤ n ≤ 12, 1 ≤ m ≤ 12, 矩阵中的每个元素 1 ≤ a[i][j] ≤20；</p><p>对于 100%的数据，1 ≤ n ≤ 16, 1 ≤ m ≤ 16, 矩阵中的每个元素 1 ≤ a[i][j] ≤1000,1 ≤ r ≤ n, 1 ≤ c ≤ m。</p><p>时间限制：每一组测试数据1s。</p><p><br></p><p>【输入输出样例 1 说明】<br>该矩阵中分值最小的 2 行 3 列的子矩阵由原矩阵的第 4 行、第 5 行与第 1 列、第 3 列、 第 4 列交叉位置的元素组成，为</p><p>6 5 6<br></p><p>7 5 6<br></p><p>，其分值为 |6 − 5| + |5 − 6| + |7 − 5| + |5 − 6| + |6 − 7| + |5 − 5| + |6 − 6| = 6。</p><p>【输入输出样例 2 说明】<br>该矩阵中分值最小的 3 行 3 列的子矩阵由原矩阵的第 4 行、第 5 行、第 6 行与第 2 列、第 6 列、第 7 列交叉位置的元素组成，选取的分值最小的子矩阵为<br></p><p>9 7 8</p><p>9 8 8</p><p>5 8 10</p>
</div>
</div>