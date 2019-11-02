<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小渊是个聪明的孩子，他经常会给周围的小朋友们讲些自己认为有趣的内容。最近，他准备给小朋友们讲解立体图，请你帮他画出立体图。</p>
<p>小渊有一块面积为m*n的矩形区域，上面有m*n个边长为1的格子，每个格子上堆了一些同样大小的吉姆（积木的长宽高都是1），小渊想请你打印出这些格子的立体图。我们定义每个积木为如下格式，并且不会做任何翻转旋转，只会严格以这一种形式摆放：</p>
<p>  +---+</p>
<p> /   /|  高</p>
<p>+---+ |</p>
<p>|   | +</p>
<p>|   |/ 宽</p>
<p>+---+</p>
<p> 长</p>
<p>每个顶点用1个加号’+’表示，长用3个”-“表示，宽用1个”/”表示，高用两个”|”表示。字符’+’ ‘-‘’/’ ‘|’的ASCII码分别为43，45，47，124。字符’.’（ASCII码46）需要作为背景输出，即立体图里的空白部分需要用’.’代替。立体图的画法如下面的规则：</p>
<p>若两块积木左右相邻，图示为：</p>
<p>..+---+---+</p>
<p>./   /   /|</p>
<p>+---+---+ |</p>
<p>|   |   | +</p>
<p>|   |   |/.</p>
<p>+---+---+..</p>
<p>若两块积木上下相邻，图示为：</p>
<p>..+---+</p>
<p>./   /|</p>
<p>+---+ |</p>
<p>|   | +</p>
<p>|   |/|</p>
<p>+---+ |</p>
<p>|   | +</p>
<p>|   |/.</p>
<p>+---+..</p>
<p>若两块积木前后相邻，图示为：</p>
<p>….+---+</p>
<p>…/   /|</p>
<p>..+---+ |</p>
<p>./   /| +</p>
<p>+---+ |/.</p>
<p>|   | +..</p>
<p>|   |/…</p>
<p>+---+….</p>
<p>立体图中，定义位于第(m,1)的格子（即第m行第1列的格子）上面自底向上的第一块积木（即最下面的一块积木）的左下角顶点为整张图最左下角的点。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件drawing.in第一行有用空格隔开的两个整数m和n，表示有m*n个格子（1&lt;=m，n&lt;=50）。</p>
<p>接下来的m行，是一个m*n的矩阵，每行有n个用空格隔开的整数，其中第i行第j列上的整数表示第i行第j列的格子上摞有多少个积木（1&lt;=每个格子上的积木数&lt;=100）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件drawing.out中包含题目要求的立体图，是一个K行L列的字符矩阵，其中K和L表示最少需要K行L列才能按规定输出立体图。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 4</p>
<p>2 2 1 2</p>
<p>2 2 1 1</p>
<p>3 2 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>......+---+---+...+---+</p>
<p>..+---+   /    /|../   /|</p>
<p>./    /|-+---+ |.+---+ |</p>
<p>+---+ |/   /| +-|    | +</p>
<p>|    | +---+ |/+---+ |/|</p>
<p>|    |/   /| +/    /|-+ |</p>
<p>+---+---+ |/+---+ |/| +</p>
<p>|    |   | +-|    | + |/.</p>
<p>|    |   |/  |    |/| +..</p>
<p>+---+---+---+---+ |/...</p>
<p>|    |   |    |   | +....</p>
<p>|    |   |    |   |/.....</p>
<p>+---+---+---+---+......</p>

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