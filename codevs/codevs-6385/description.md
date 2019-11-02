<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>        你有一个密码锁，由N个部件组成。每个部件是一个环，每个环上面都有K个格子，每个格子里面有一个1-9的整数，而且每个环可以各自独立地旋转，可以顺时针转，也可以逆时针转。</p><p><img src="/source/codevs/codevs-6385/img/aHR0cDovL3d3My5zaW5haW1nLmNuL2xhcmdlLzAwNjBsbTdUZ3kxZmlvYTMxbHBvZ2ozMGNnMDY5ZGdlLmpwZw==.jpg"></p><p>但是不管锁上面有多少个数字，只有给定的两排数字会被你看到。比如上图中被你看到的数字就是“3，1，2，3，1，3”和“2，3，3，3，3，1”。当你能看到的数字上下两排的和相同的时候，密码锁就会打开。上面这个例子中3+1+2+3+1+3=13，2+3+3+3+3+1=15，因此这把锁没有打开。</p><p>        现在给出密码锁的构造，你需要对每个环分别进行旋转，以打开这把锁。输出打开这把锁最少需要旋转的总次数。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第</span>1<span style="">行为</span>2<span style="">个整数，</span>N<span style="">和</span>K<span style="">，意义如上所述。</span></p><p><span style="">第</span>2~N+1<span style="">行描述每个环。每行有</span>K<span style="">个整数。这些行中，每行的第一个数构成了上文中所说的你能看到的第一行，每行第二个数构成了你能看到的第二行。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">一个整数，表示打开锁需要的最小的总旋转次数。如果无法打开，输出</span>-1<span style="font-family:宋体">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 5</p><p>3 2 6 7 9</p><p>1 3 2 4 6</p><p>2 3 9 6 5</p><p>3 3 8 7 6</p><p>1 3 8 9 1</p><p>3 1 6 9 7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=N&lt;=400<span style="">，</span>3&lt;=K&lt;=8<span style="">，</span>1&lt;=<span style="">每个数字</span>&lt;=9</p><p><span style="">左数第</span>5<span style="">个环向下转一下。</span></p><p><br></p>
</div>
</div>