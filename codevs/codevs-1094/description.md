<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">我们可以把由“<span style="font-family: DejaVu Serif Condensed,serif;">0<span style="">”</span></span>和“<span style="font-family: DejaVu Serif Condensed,serif;">1<span style="">”</span></span>组成的字符串分为三类：全“<span style="font-family: DejaVu Serif Condensed,serif;">0<span style="">”</span></span>串称为<span style="font-family: DejaVu Serif Condensed,serif;">B</span>串，全“<span style="font-family: DejaVu Serif Condensed,serif;">1<span style="">”</span></span>串称为<span style="font-family: DejaVu Serif Condensed,serif;">I</span>串，既含“<span style="font-family: DejaVu Serif Condensed,serif;">0<span style="">”</span></span>又含“<span style="font-family: DejaVu Serif Condensed,serif;">1<span style="">”</span></span>的串则称为<span style="font-family: DejaVu Serif Condensed,serif;">F</span>串。</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">FBI</span>树是一种二叉树<span style="font-family: DejaVu Serif Condensed,serif;">[1]</span>，它的结点类型也包括<span style="font-family: DejaVu Serif Condensed,serif;">F</span>结点，<span style="font-family: DejaVu Serif Condensed,serif;">B</span>结点和<span style="font-family: DejaVu Serif Condensed,serif;">I</span>结点三种。由一个长度为<span style="font-family: DejaVu Serif Condensed,serif;">2N</span>的“<span style="font-family: DejaVu Serif Condensed,serif;">01<span style="">”</span></span>串<span style="font-family: DejaVu Serif Condensed,serif;">S</span>可以构造出一棵<span style="font-family: DejaVu Serif Condensed,serif;">FBI</span>树<span style="font-family: DejaVu Serif Condensed,serif;">T</span>，递归的构造方法如下：</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1) T</span>的根结点为<span style="font-family: DejaVu Serif Condensed,serif;">R</span>，其类型与串<span style="font-family: DejaVu Serif Condensed,serif;">S</span>的类型相同；</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2) </span>若串<span style="font-family: DejaVu Serif Condensed,serif;">S</span>的长度大于<span style="font-family: DejaVu Serif Condensed,serif;">1</span>，将串<span style="font-family: DejaVu Serif Condensed,serif;">S</span>从中间分开，分为等长的左右子串<span style="font-family: DejaVu Serif Condensed,serif;">S1</span>和<span style="font-family: DejaVu Serif Condensed,serif;">S2</span>；由左子串<span style="font-family: DejaVu Serif Condensed,serif;">S1</span>构造<span style="font-family: DejaVu Serif Condensed,serif;">R</span>的左子树<span style="font-family: DejaVu Serif Condensed,serif;">T1</span>，由右子串<span style="font-family: DejaVu Serif Condensed,serif;">S2</span>构造<span style="font-family: DejaVu Serif Condensed,serif;">R</span>的右子树<span style="font-family: DejaVu Serif Condensed,serif;">T2</span>。</p>
<p style="">现在给定一个长度为<span style="font-family: DejaVu Serif Condensed,serif;">2N</span>的“<span style="font-family: DejaVu Serif Condensed,serif;">01<span style="">”</span></span>串，请用上述构造方法构造出一棵<span style="font-family: DejaVu Serif Condensed,serif;">FBI</span>树，并输出它的后序遍历<span style="font-family: DejaVu Serif Condensed,serif;">[2]</span>序列。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入的第一行是一个整数<span style="font-family: DejaVu Serif Condensed,serif;">N</span>（<span style="font-family: DejaVu Serif Condensed,serif;">0 &lt;= N &lt;= 10</span>），第二行是一个长度为<span style="font-family: DejaVu Serif Condensed,serif;">2N</span>的“<span style="font-family: DejaVu Serif Condensed,serif;">01<span style="">”</span></span>串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;">输出<span style="margin-bottom: 0cm;">t</span>包括一行，这一行只包含一个字符串，即<span style="font-family: DejaVu Serif Condensed,serif;">FBI</span>树的后序遍历序列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">10001011</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">IBFBBBFIBFIIIFF</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">对于<span style="font-family: DejaVu Serif Condensed,serif;">40%</span>的数据，<span style="font-family: DejaVu Serif Condensed,serif;">N &lt;= 2</span>；</p>
<p style="">对于全部的数据，<span style="font-family: DejaVu Serif Condensed,serif;">N &lt;= 10</span>。</p>
</div>
</div>