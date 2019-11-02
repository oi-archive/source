<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小H最近在研究随机算法。随机算法往往需要通过调用随机数生成函数（例如Pascal中的random和C/C++中的rand）来获得随机性。事实上，随机数生成函数也并不是真正的“随机”，其一般都是利用某个算法计算得来的。比如，下面这个二次多项式递推算法就是一个常用算法：算法选定非负整数 x0,a,b,c,d 作为随机种子，并采用如下递推公式进行计算：<br>xi=(a*xi-1^2+b*xi-1+c)mod d<br>对于任意 i≥1,这样可以得到一个任意长度的非负整数数列{xi }(i≥1)，一般来说，我们认为这个数列是随机的。利用随机序列{xi }(i≥1)，我们还可以采用如下算法来产生一个1到K的随机排列{Ti }(i=1)K：初始设T为1到K的递增序列；对T进行K次交换，第 i 次交换，交换 Ti 和 T((x(i) mod i)+1) 的值。此外，小H在这 K 次交换的基础上，又额外进行了 Q 次交换操作，对于第 i 次额外交换，小H会选定两个下标 ui 和 vi，并交换 T(u_i ) 和 T(v_i ) 的值。为了检验这个随机排列生成算法的实用性，小H设计了如下问题：小H有一个 N 行 M 列的棋盘，她首先按照上述过程，通过 N×M+Q 次交换操作，生成了一个 1~N×M 的随机排列 {Ti }(i=1)(N×M)，然后将这 N×M 个数逐行逐列依次填入这个棋盘：也就是第 i 行第 j 列的格子上所填入的数应为 T((i-1)*M+j)。接着小H希望从棋盘的左上角，也就是第一行第一列的格子出发，每次向右走或者向下走，在不走出棋盘的前提下，走到棋盘的右下角，也就是第 N 行第 M 列的格子。小H把所经过格子上的数字都记录了下来，并从小到大排序，这样，对于任何一条合法的移动路径，小H都可以得到一个长度为 N+M-1 的升序序列，我们称之为路径序列。小H想知道，她可能得到的字典序最小的路径序列应该是怎样的呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第1行包含5个整数，依次为 x_0,a,b,c,d ，描述小H采用的随机数生成算法所需的随机种子。 第2行包含三个整数 N,M,Q ，表示小H希望生成一个1到 N×M 的排列来填入她 N 行 M 列的棋盘，并且小H在初始的 N×M 次交换操作后，又进行了 Q 次额外的交换操作。 接下来 Q 行，第 i 行包含两个整数 u_i,v_i，表示第 i 次额外交换操作将交换 T_(u_i )和 T_(v_i ) 的值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行，包含 N+M-1 个由空格隔开的正整数，表示可以得到的字典序最小的路径序列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 3 5 1 71 <br>3 4 3 <br>1 7 <br>9 9 <br>4 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 2 6 8 9 12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2&lt;=n,m&lt;=5000<br>0&lt;=q&lt;=50000<br>0&lt;=a&lt;=300<br>0&lt;=b,c&lt;=10^8<br>0&lt;=x0&lt;d&lt;=10^8<br>1&lt;=vi,ui&lt;=n*m</p>
</div>
</div>