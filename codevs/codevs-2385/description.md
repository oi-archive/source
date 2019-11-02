<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近，一个方块填数的游戏风靡全球：<br>给定一个n*m的方块。 n行从上到下标号为1到n，m列从左到右标号为1到<br>m。如果一个方格所在的行的标号和所在的列的标号都是奇数，那么该方格就称<br>为奇方格。游戏的开始所有的奇方格中都填上了数。你需要在其他的方格里填数，<br>如果填完数后，方块满足下面条件，你就赢得了这个游戏：<br>1、任意一个a1*b1的子方块中所有数的和大于0；<br>2、任意一个a2*b2的子方块中所有数的和小于0；<br>其中，a1、 b1、 a2、 b2都是在游戏的开始给定的。 一个a*b的子方块是指行标号<br>在i（1≤i≤n-a+1）到i+a-1之间，列标号在j(1≤j≤m-b+1)到j+b-1之间的所有的方<br>格的集合。<br>小P很喜欢这种游戏，他希望你帮助写一个程序给出一种填数的方案，或<br>者告诉他这样的方案不存在。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为用空格分开的6个正整数n, m, a1, b1, a2, b2，都在1到100之间。<br>从第 2 行起到(n+1)/2 行，每一行有(m+1)/2个整数，第 i+1 行的第<br>k(k=1,2,…, (m+1)/2) 个数表示在游戏开始时方块的第2i-1行，2j-1列的方格所填的整数。这些整数都在-100到100之间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果填数方案不存在，输出一行&ldquo;No&rdquo;。<br />如果填数方案存在，第一行输出&ldquo;Yes&rdquo;。</p>
<p>接下来的n行，每一行有用空格分开的m个整数，描述一个填数方案。 输出的每一个整数必须在-10<sup>9</sup>到10<sup>9</sup>之间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 2 2 3 3<br>1 1<br>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes<br>1 -1 1<br>-4 5 -4<br>1 -1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n, m, a1, b1, a2, b2，都在1到100之间。</p>
</div>
</div>