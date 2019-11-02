<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>编辑数学公式总是一件烦人的事情，为此HURRICANE小组准备出一个编辑数学公式的软件。除了基本功能外，软件还将实现分式和矩阵输入。按照设想，软件应该是符合人性化设计的，必须最大限度的方便用户输入，尽管代价是软件开发极其复杂。幸好输入的方式和格式都已定好，你只需要编个处理程序就行了，下面是相关的约定和格式：</p>
<p> </p>
<h3>【格式控制的概念】</h3>
<p> </p>
<table border="1" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td width="79">
<p>元素</p>
</td>
<td width="458">
<p>元素可以是<span style="text-decoration: underline;">运算符</span>、<span style="text-decoration: underline;">括号</span>、<span style="text-decoration: underline;">数字</span>、<span style="text-decoration: underline;">字母</span>、<span style="text-decoration: underline;">矩阵</span>、<span style="text-decoration: underline;">分式</span>。<strong></strong></p>
</td>
</tr>
<tr>
<td width="79">
<p>数字、字母和括号</p>
</td>
<td width="458">
<p>数字包括’0’..’9’、’.’。字母包括’A’..’Z’，’a’..’z’。括号包括’（’，’）’。它们都只占一行，该行也是对齐行。<strong></strong></p>
</td>
</tr>
<tr>
<td width="79">
<p>表达式</p>
</td>
<td width="458">
<p><strong>由0</strong><strong>个到至多500</strong><strong>个</strong>元素<strong>构成的序列</strong>。其中矩阵与分式元素总个数最多不超过30个。<strong></strong></p>
</td>
</tr>
<tr>
<td width="79">
<p>编辑框</p>
</td>
<td width="458">
<p><strong>一个输入<span style="text-decoration: underline;">表达式</span>的矩形区域。</strong>每一个编辑框都包括一个对齐行用作编辑框相互之间的对齐。且我们定义编辑框的宽度为最长一行的字符个数，例如表达式空的时候为0，高度为最高行与最低行之间相差的行数（包括），但最小为1，即使表达式为空。<strong></strong></p>
</td>
</tr>
<tr>
<td width="79">
<p>对齐行</p>
</td>
<td width="458">
<p><strong><span style="text-decoration: underline;">编辑框</span></strong><strong>或<span style="text-decoration: underline;">元素</span>中某一特定行</strong>。该行用于框内对齐<span style="text-decoration: underline;">表达式</span>及框间对齐，对齐时需要使<span style="text-decoration: underline;">表达式</span>中的<span style="text-decoration: underline;">元素</span>的<span style="text-decoration: underline;">对齐行</span>位于<span style="text-decoration: underline;">编辑框</span>的对齐行上。<strong></strong></p>
</td>
</tr>
<tr>
<td width="79">
<p>运算符</p>
</td>
<td width="458">
<p>有’+’、’-’、’*’、’/’四个，为了区分“-”（减号）与分数线，“-”两边分别加上一个空列。<strong></strong></p>
</td>
</tr>
<tr>
<td width="79">
<p>矩阵</p>
</td>
<td width="458">
<p>一个（,_）的矩阵包含个<span style="text-decoration: underline;">编辑框</span>将矩阵分为了<em>m</em>个<span style="text-decoration: underline;">编辑列</span>和<em>n</em>个<span style="text-decoration: underline;">编辑行</span>。在矩阵的同一<span style="text-decoration: underline;">编辑行</span>中，相邻的两个编辑框按编辑框的对齐行对齐，同一编辑列的编辑框按照它们的宽度居中对齐。且必须保证行与行之间至少存在一个空行，列与列之间至少存在一个空列。第一列左边与最后一列右边每行各有一个“[”和“]”，位于各行表达式的对齐行上，如图所示：</p>
<p> </p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td width="96">
<p>图形表示</p>
</td>
<td valign="top" width="336"> </td>
</tr>
<tr>
<td width="96">
<p>文本表示</p>
<p> </p>
</td>
<td valign="top" width="336">
<p>          612</p>
<p>[  456   -----]     -第一<span style="text-decoration: underline;">编辑行</span>的对齐行</p>
<p>          123</p>
<p>                    -空行、整个矩阵的对齐行</p>
<p>  65535</p>
<p>[-------  234 ]     -第二<span style="text-decoration: underline;">编辑行</span>的对齐行</p>
<p>    1</p>
<p>  -----</p>
<p>   255</p>
</td>
</tr>
</tbody>
</table>
<p>若矩阵的编辑行数<em>n</em>为奇数，则矩阵的对齐行为中间那行编辑行中编辑框的对齐行，否则为中间两个编辑行之间的空行；<strong></strong></p>
</td>
</tr>
<tr>
<td width="79">
<p>分式</p>
</td>
<td width="458">
<p>分式由分子和分母两个编辑框以及它们之间的分数线组成。分式分数线为一条由“-”组成的字符序列，同时它也是分式的对齐行。分式的宽度为两个编辑框宽度的最大值加2，即在左右两边分别加上一个“-”；而高度为两个编辑框的高度加上分数线的高度1。两个编辑框按居中对齐，如图：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="192">
<p> XXXX              XX</p>
<p>------          --------</p>
<p> XXX            XXXXXX</p>
</td>
</tr>
</tbody>
</table>
<p>在居中对齐时，如果不能正好对准，则往左偏半格，如上图左边的分母编辑框。<strong></strong></p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<h3>【光标控制】</h3>
<p> </p>
<p>应该指出，编辑框是可以层层嵌套的，比如一个编辑框内有一个矩阵，矩阵内又有若干个编辑框。我们说该编辑框比矩阵的编辑框高一级，矩阵内的所有编辑框同级，分式的两个编辑框也是同级的。注意：<strong>同级只是对一个矩阵或一个分式内的编辑框而言。</strong></p>
<p>光标可以跳到编辑框的开始和末尾，也可以向四个方向移动，设光标所处的最低一级的编辑框为A。</p>
<p> </p>
<ul>
<li>如果光标跳到编辑框的开始（末尾），则把光标置于A的前端（末端）；</li>
</ul>
<p> </p>
<p> </p>
<ul>
<li>当光标上下移动时</li>
</ul>
<p>n  如果A上(下)方有与A同级的编辑框B，则把光标置于B的前端，</p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="166">
<p>示例</p>
</td>
<td valign="top" width="166">
<p>下移一次后</p>
</td>
</tr>
<tr>
<td valign="top" width="166">
<p> XXXX|</p>
<p>------</p>
<p>  XX</p>
</td>
<td valign="top" width="166">
<p>XXXX</p>
<p>------</p>
<p>  |XX</p>
</td>
</tr>
</tbody>
</table>
</div>
<p>n  否则对比A高一级的编辑框作同样判断，若A是最高级别的编辑框，则不作任何处理。如图，竖线代表光标：</p>
<div>
<table border="1" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top" width="113">
<p>示例</p>
</td>
<td valign="top" width="113">
<p>下移一次后</p>
</td>
<td valign="top" width="113">
<p>再下移一次后（不变）</p>
</td>
</tr>
<tr>
<td valign="top" width="113">
<p>  d</p>
<p> ---</p>
<p>  |c</p>
<p>-----</p>
<p>  a</p>
<p> ---</p>
<p>  b</p>
</td>
<td valign="top" width="113">
<p>  d</p>
<p> ---</p>
<p>  c</p>
<p>-----</p>
<p>  a</p>
<p> ---</p>
<p>  b</p>
</td>
<td valign="top" width="113">
<p>  d</p>
<p> ---</p>
<p>  c</p>
<p>-----</p>
<p>  a</p>
<p> ---</p>
<p>  b</p>
</td>
</tr>
</tbody>
</table>
</div>
<p> </p>
<ul>
<li>当光标左（右）移动时</li>
</ul>
<p>n  若光标位于A的前端(末端)，</p>
<p>u  如果左(右)边没有同级的编辑框，则光标将返回到更高一级的编辑框（若无则不作处理），置于矩阵或分式的左(右)边；</p>
<p>u  如果左(右)边有同级的编辑框B，则置于B的末端（前端）；</p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="115">
<p>示例</p>
</td>
<td valign="top" width="115">
<p>左移一次后</p>
</td>
<td valign="top" width="115">
<p>再左移两次后</p>
</td>
</tr>
<tr>
<td valign="top" width="115">
<p>1+[B |A]</p>
</td>
<td valign="top" width="115">
<p>1+[B| A]</p>
</td>
<td valign="top" width="115">
<p>1+|[B A]</p>
</td>
</tr>
</tbody>
</table>
</div>
<p> </p>
<p>n  若光标左（右）边是一个矩阵或分式，</p>
<p>u  如果是分式，则光标置于分子编辑框的末端(前端)，</p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="166">
<p>示例</p>
</td>
<td valign="top" width="166">
<p>左移一次后</p>
</td>
</tr>
<tr>
<td valign="top" width="166">
<p> XXXX</p>
<p>------</p>
<p>  XX</p>
</td>
<td valign="top" width="166">
<p>XXXX|</p>
<p>------</p>
<p>  XX</p>
</td>
</tr>
</tbody>
</table>
</div>
<p> </p>
<p>u  如果是矩阵，则置于第<em>m</em>列行（第1列行）编辑框的末端(前端)；</p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="170">
<p>示例</p>
</td>
<td valign="top" width="170">
<p>右移一次后</p>
</td>
</tr>
<tr>
<td valign="top" width="170">
<p>          612</p>
<p>[  456   -----]</p>
<p>          123</p>
<p> </p>
<p>  65535</p>
<p>[-------  234 ]</p>
<p>    1</p>
<p>  -----</p>
<p>   255</p>
</td>
<td valign="top" width="170">
<p>          612</p>
<p>[  456   -----]</p>
<p>          123</p>
<p> </p>
<p>  65535</p>
<p>[-------  234 ]</p>
<p>    1</p>
<p>  -----</p>
<p>   255</p>
</td>
</tr>
</tbody>
</table>
</div>
<p>n  若光标左（右）边是其它元素，则光标左（右）移一格。</p>
<p> </p>
<h3>【输入控制】</h3>
<p> </p>
<p>程序通过一系列的事件来实现输入，每个事件已经被转化成一个字符串：</p>
<p> </p>
<p>u  若字符串只含一个字符，则必为运算符、括号、数字或字母。此时程序在光标处插入该字符，然后光标右移一次；</p>
<p>u  若字符串为Matrix或Fraction，则在光标处插入一个的矩阵或分式，光标右移一次；</p>
<p>u  若字符串为AddRow或AddCol，则在矩阵内光标所处的编辑框前插入一行<span style="text-decoration: underline;">编辑行</span>或一列编辑列，并把光标置于新插入的行（列）中，若光标不在任何矩阵内，则不作处理；</p>
<p>u  字符串Home、End、Left、Right、Up、Down则分别代表光标置于编辑框的开始、末尾，光标向左、右、上、下移动一次。</p>
<p> </p>
<p>注意：由于该软件只用于输入表达式，并不对表达式进行任何处理，所以<strong>所输入的表达式可能并不正确。</strong></p>
<p>你需要根据给定的输入，给出满足题意的输出：</p>
<p>l  输入中包括用如上所述格式所描述的操作序列。序列中可能包括运算符、括号、数字、字母、矩阵或分数的插入及光标的移动控制；</p>
<p>l  你需要根据输入的操作序列，完成对表达式的输入；我们约定初始时的表达式为空；</p>
<p>l  然后你需要在输出文件中用我们约定的格式打印出这个表达式。注意表达式行末不要有空格。</p>
<p><strong><br></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每行有一个代表事件的字符串，直到文件结束。我们约定矩阵的规模不超过，总的元素个数不超过10,000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>按规定的格式输出编辑框的结果，空白的地方用空格补上，每行行末不能有多余空格。最后一行行末保留一个回车。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>+<br>Fraction<br>1<br>Down<br>1<br>+<br>Fraction<br>1 <br>Down<br>1<br>+<br>Fraction<br>1<br>Down<br>x<br>Up<br>Up <br>Right<br>Right<br>Home<br>Up<br>End<br>+<br>2<br>-<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top" width="240">
<p>                [1]</p>
<p>     1</p>
<p> - 5---*[1 2 3]*[2]</p>
<p>     6</p>
<p>                [3]</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>