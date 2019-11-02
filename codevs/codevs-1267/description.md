<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>You are a mouse that lives in a cage in a large laboratory.</p>
<p>你是一只生活在笼子里的实验室老鼠。</p>
<p>The laboratory is composed of one rectangular grid of square cages, with a total of R rows and C columns of cages (1 ≤ R,C ≤ 25).</p>
<p>实验室是一个R行C列的格子矩阵(1 ≤ R,C ≤ 25). 每个格子是一个笼子. (尼玛还要我活么……)</p>
<p>To get your exercise, the laboratory owners allow you to move between cages.</p>
<p>为了让你锻炼身体，实验室管理员允许你在笼子之间移动。</p>
<p>You can move between cages either by moving right between two adjacent cages in the same row, or by moving down between two adjacent cages in the same column.</p>
<p>你只能向右和向下移动。</p>
<p>You cannot move diagonally, left or up.</p>
<p>你不能斜着移动，也不能向上和向左移动。</p>
<p>Your cage is in one corner of the laboratory, which has the label (1,1) (to indicate top-most row, left-most column).</p>
<p>你所在的笼子是实验室的左上角，标记为(1,1)</p>
<p>You would like to visit your brother who lives in the cage labelled (R,C) (bottom-most row, right-most column), which is in the other corner diagonally.</p>
<p>你想去右下角的笼子(R,C)里找你的女朋友(尼玛老鼠也有女盆友么！！！)</p>
<p>However, there are some cages which you cannot pass through, since they contain cats.</p>
<p>但是有一些笼子是不能经过的，因为里面有猫（谁说老鼠怕猫么，还有，管理员有毛病么……）</p>
<p>Your brother, who loves numbers, would like to know how many different paths there are between your cage and his that do not pass through any cat cage. Write a program to compute this number of cat-free paths.</p>
<p>你女朋友很爱数学，她想要知道有多少条不同的路径可以从你的笼子到达她的笼子。写一个程序来计算吧。（这样的女朋友不要也罢……）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of input contains two integers R and C, separated by one space representing the number of rows and columns (respectively). On the second line of input is the integer K, the number of cages that contain cats. The next K lines each contain the row and column positions (in that order) for a cage that contains a cat. None of the K cat cages are repeated, and all cages are valid positions. Note also that (1,1) and (R,C) will not be cat cages.</p>
<p>第一行包含2个整数R和C，第二行一个整数K，代表包含猫的笼子的个数，接下来K行包含K个不同的位置信息，代表K个包含猫的笼子的位置信息，注意(1,1)和(R,C)这两个位置是不会有猫的， 否则出题者就没法活了……</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Output the non-negative integer value representing the number of paths between your cage at position (1,1) and your brother&rsquo;s cage at position (R,C). You can assume the output will be strictly less than 1 000 000 000.</p>
<p>输出一个非负整数代表你可以去你女朋友笼子里和她啪啪啪的路径数目，你可以假设这个输出会严格小于1,000,000,000。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入 1:</p>
<p>2 3</p>
<p>1</p>
<p>2 1</p>
<p>样例输入 2:</p>
<p>3 4</p>
<p>3</p>
<p>2 3</p>
<p>2 1</p>
<p>1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出 1: 2</p>
<p>样例输出 2: 1</p>

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