
# Description

<div class="content"><div align="center"></div>
<div><span style="font-size: medium">减法不满足结合率, 例如 (5-2)-1=2, 但 5-(2-1)=4, 因此 (5-2)-1&lt;&gt;5-(2-1). 这意味着表达式5-2-1 依赖减法操作的顺序. 如果没有扩号，假定表达式计算从左到右, 即5-2-1 等于 (5-2)-1.我们给出表达式的形式如下：</span></div>
<div align="center"><span style="font-size: medium"><i>x</i><sub>1</sub> +/- <i>x</i><sub>2</sub> +/- ... +/- <i>x<sub>n</sub></i>,</span></div>
<div><span style="font-size: medium">+/- 表示+ (加) - (减), <i>x</i><sub>1</sub>,<i>x</i><sub>2</sub>,...,<i>x<sub>n</sub></i> 表示计算变量. 对下面的表达式</span></div>
<div align="center"><span style="font-size: medium"><i>x</i><sub>1</sub>-<i>x</i><sub>2</sub>-...-<i>x<sub>n</sub></i></span></div>
<div><span style="font-size: medium">我们想插入<i>n</i>-1对括号得到和表达式相同的结果.例如，我们想得到和下面表达式相等值的表达式 </span></div>
<div align="center"><span style="font-size: medium"><i>x</i><sub>1</sub>-<i>x</i><sub>2</sub>-<i>x</i><sub>3</sub>+<i>x</i><sub>4</sub>+<i>x</i><sub>5</sub>-<i>x</i><sub>6</sub>+<i>x</i><sub>7</sub></span></div>
<div><span style="font-size: medium">可以对下面的表达式插入括号</span></div>
<div align="center"><span style="font-size: medium"><i>x</i><sub>1</sub>-<i>x</i><sub>2</sub>-<i>x</i><sub>3</sub>-<i>x</i><sub>4</sub>-<i>x</i><sub>5</sub>-<i>x</i><sub>6</sub>-<i>x</i><sub>7</sub></span></div>
<div><span style="font-size: medium">得到</span></div>
<div align="center"><span style="font-size: medium">(((<i>x</i><sub>1</sub>-<i>x</i><sub>2</sub>)-((<i>x</i><sub>3</sub>-<i>x</i><sub>4</sub>)-<i>x</i><sub>5</sub>))-(<i>x</i><sub>6</sub>-<i>x</i><sub>7</sub>)).</span></div>
<div><span style="font-size: medium"><b>注意:</b> 我们只对完整而正确的表达式有兴趣，一个完整正确的表达式必须符合</span></div>
<ul type="disc">
    <li><span style="font-size: medium">它可能是单个变量, </span></li>
    <li><span style="font-size: medium">可能形如(<i>w</i><sub>1</sub>-<i>w</i><sub>2</sub>), 而且 <i>w</i><sub>1</sub> 和 <i>w</i><sub>2</sub> 都是完成而正确的表达式. </span></li>
</ul>
<div><span style="font-size: medium">通常来说，我们对如下空括号形式不感兴趣: (), (<i>x<sub>i</sub></i>), ((...)). 而表达式 <i>x</i><sub>1</sub>-(<i>x</i><sub>2</sub>-<i>x</i><sub>3</sub>) 不是完整的，因为它缺少最外层的括号.</span></div></div>

# Input

<div class="content"><div style="margin: auto 0cm"><span style="font-size: medium">第一行有一个整数 <i>n</i>, 2&lt;=<i>n</i>&lt;=1 000 000. 表示表达式变量的个数.在下面的 <i>n</i>-1 行有一个字符<tt>+</tt> 或 <tt>-</tt>. 第<i>i</i>行 出现的字符给出了<i>x<sub>i</sub></i><sub>-1</sub> 和 <i>x<sub>i</sub></i> 之间的操作. </span></div>
<div></div></div>

# Output

<div class="content"><div><span style="font-size: medium">对表达式<i>x</i><sub>1</sub>-<i>x</i><sub>2</sub>-...-<i>x<sub>n</sub></i>添加n-1对括号，使得它与给出的表达式等价。在<tt>naw.out</tt> 中写入一个整数，表示插入空格的不同方案数，答案不超过1 000 000 000。</span></div>
<p><divre></divre>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
-<br/>
-<br/>
+<br/>
+<br/>
-<br/>
+<br/>
<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

