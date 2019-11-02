<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>线段树是一种<span style="font-family: 'Lucida Console';">OI</span><span style="">中喜闻乐见的数据结构。它维护一个序列</span><span style="font-family: 'Lucida Console';">a</span>1，<span style="font-family: 'Lucida Console';">a</span>2，<span style="font-family: 'Lucida Console';">a</span>3，……，<span style="font-family: 'Lucida Console';">a</span>n，其中每个元素都为不小于<span style="font-family: 'Lucida Console';">0</span><span style="">的整数，它支持以下操作：</span></p>
<p>1.修改元素值：给定<span style="font-family: 'Lucida Console';">x</span><span style="">，</span><span style="font-family: 'Lucida Console';">y</span><span style="">，修改</span><span style="font-family: 'Lucida Console';">a</span>x的值为<span style="font-family: 'Lucida Console';">y</span><span style="">；</span></p>
<p>2.查询元素值：给定<span style="font-family: 'Lucida Console';">x</span><span style="">，输出</span><span style="font-family: 'Lucida Console';">a</span>x的值；</p>
<p>3.区间增减：给定<span style="font-family: 'Lucida Console';">l</span><span style="">，</span><span style="font-family: 'Lucida Console';">r</span><span style="">，</span><span style="font-family: 'Lucida Console';">x</span><span style="">，将从</span><span style="font-family: 'Lucida Console';">a</span>l到<span style="font-family: 'Lucida Console';">a</span>r（含<span style="font-family: 'Lucida Console';">a</span>l和<span style="font-family: 'Lucida Console';">a</span>r），即区间<span style="font-family: 'Lucida Console';">[l</span><span style="">，</span><span style="font-family: 'Lucida Console';">r]</span><span style="">中的每个值都加上</span><span style="font-family: 'Lucida Console';">x</span><span style="">（</span><span style="font-family: 'Lucida Console';">x</span><span style="">可以为负数）；</span></p>
<p>4.区间求和：给定<span style="font-family: 'Lucida Console';">l</span><span style="">，</span><span style="font-family: 'Lucida Console';">r</span><span style="">，输出从</span><span style="font-family: 'Lucida Console';">a</span>l到<span style="font-family: 'Lucida Console';">a</span>r（含<span style="font-family: 'Lucida Console';">a</span>l和<span style="font-family: 'Lucida Console';">a</span>r），即区间<span style="font-family: 'Lucida Console';">[l</span><span style="">，</span><span style="font-family: 'Lucida Console';">r]</span><span style="">中的每个元素之和。</span></p>
<p>下面请你编程，实现线段树的功能。</p>
<p> </p>
<p>（请注意本题的数据范围和空间限制，切记切记）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为三个整数<span style="font-family: 'Lucida Console';">s</span><span style="">，</span><span style="font-family: 'Lucida Console';">q</span><span style="">和</span><span style="font-family: 'Lucida Console';">n</span><span style="">，其中</span><span style="font-family: 'Lucida Console';">s</span><span style="">代表此测试点的序号（从</span><span style="font-family: 'Lucida Console';">1</span><span style="">到</span><span style="font-family: 'Lucida Console';">50</span><span style="">，具体见【数据说明】），</span><span style="font-family: 'Lucida Console';">q</span><span style="">代表操作的数量，</span><span style="font-family: 'Lucida Console';">n</span><span style="">代表序列的长度。初始时，序列中每个元素都为</span><span style="font-family: 'Lucida Console';">0</span><span style="">。</span></p>
<p>接下来<span style="font-family: 'Lucida Console';">q</span><span style="">行，每行代表一个操作，第一个数字为操作代号，意义在上面已经给出了。</span></p>
<p>如果操作为<span style="font-family: 'Lucida Console';">1</span><span style="">（修改元素值），则这一行接下来有两个整数</span><span style="font-family: 'Lucida Console';">x</span><span style="">，</span><span style="font-family: 'Lucida Console';">y</span><span style="">；如果操作为</span><span style="font-family: 'Lucida Console';">2</span><span style="">（查询元素值），则这一行接下来有一个整数</span><span style="font-family: 'Lucida Console';">x</span><span style="">；如果操作为</span><span style="font-family: 'Lucida Console';">3</span><span style="">（区间增减），则这一行接下来有三个整数</span><span style="font-family: 'Lucida Console';">l</span><span style="">，</span><span style="font-family: 'Lucida Console';">r</span><span style="">，</span><span style="font-family: 'Lucida Console';">x</span><span style="">；如果操作为</span><span style="font-family: 'Lucida Console';">4</span><span style="">（区间求和），则这一行接下来有两个整数</span><span style="font-family: 'Lucida Console';">l</span><span style="">，</span><span style="font-family: 'Lucida Console';">r</span><span style="">。</span></p>
<p>输入保证操作的合法性，即不会出现<span style="font-family: 'Lucida Console';">l&gt;r</span><span style="">的情况，也不会出现操作之后元素值出现负数的情况。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件共<span style="font-family: 'Lucida Console';">q</span><span style="font-family: 宋体;">行。对于每次询问，需要输出一个返回值，每个占一行。</span></p>
<p class="p0">如果当前操作为不需要返回值的操作（<span style="font-family: 'Lucida Console';">1</span><span style="font-family: 宋体;">修改元素值，</span><span style="font-family: 'Lucida Console';">3</span><span style="font-family: 宋体;">区间增减），则输出一行</span><span style="font-family: 'Lucida Console';">-1</span><span style="font-family: 宋体;">；否则，输出对应操作的返回值。即对于操作</span><span style="font-family: 'Lucida Console';">2</span><span style="font-family: 宋体;">，输出所询问的元素值；对于操作</span><span style="font-family: 'Lucida Console';">4</span><span style="font-family: 宋体;">，输出区间所有元素之和。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 10 4</p>
<p>2 3</p>
<p>1 2 3</p>
<p>2 3</p>
<p>2 2</p>
<p>3 1 3 2</p>
<p>2 3</p>
<p>2 2</p>
<p>2 1</p>
<p>4 2 4</p>
<p>2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>
<p>-1</p>
<p>0</p>
<p>3</p>
<p>-1</p>
<p>2</p>
<p>5</p>
<p>2</p>
<p>7</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例说明】</p>
<p>a<span style="">为一个长度为</span><span style="font-family: 'Lucida Console';">4</span><span style="">的序列，初始为</span><span style="font-family: 'Lucida Console';">{0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0}</span><span style="">。</span></p>
<p>首先询问第<span style="font-family: 'Lucida Console';">3</span><span style="">个元素的值，返回</span><span style="font-family: 'Lucida Console';">0</span><span style="">；</span></p>
<p>然后将第<span style="font-family: 'Lucida Console';">2</span><span style="">个元素的值改为</span><span style="font-family: 'Lucida Console';">3</span><span style="">，序列变为</span><span style="font-family: 'Lucida Console';">{0</span><span style="">，</span><span style="font-family: 'Lucida Console';">3</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0}</span><span style="">，返回</span><span style="font-family: 'Lucida Console';">-1</span><span style="">；</span></p>
<p>分别询问第<span style="font-family: 'Lucida Console';">3</span><span style="">个和第</span><span style="font-family: 'Lucida Console';">2</span><span style="">个元素的值，依次返回</span><span style="font-family: 'Lucida Console';">0</span><span style="">和</span><span style="font-family: 'Lucida Console';">3</span><span style="">；</span></p>
<p>将区间<span style="font-family: 'Lucida Console';">[1</span><span style="">，</span><span style="font-family: 'Lucida Console';">3]</span><span style="">内元素都增加</span><span style="font-family: 'Lucida Console';">2</span><span style="">，序列变为</span><span style="font-family: 'Lucida Console';">{2</span><span style="">，</span><span style="font-family: 'Lucida Console';">5</span><span style="">，</span><span style="font-family: 'Lucida Console';">2</span><span style="">，</span><span style="font-family: 'Lucida Console';">0}</span><span style="">，返回</span><span style="font-family: 'Lucida Console';">-1</span><span style="">；</span></p>
<p>分别询问第<span style="font-family: 'Lucida Console';">3</span><span style="">，</span><span style="font-family: 'Lucida Console';">2</span><span style="">，</span><span style="font-family: 'Lucida Console';">1</span><span style="">个元素的值，依次返回</span><span style="font-family: 'Lucida Console';">2</span><span style="">，</span><span style="font-family: 'Lucida Console';">5</span><span style="">，</span><span style="font-family: 'Lucida Console';">2</span><span style="">；</span></p>
<p>询问区间<span style="font-family: 'Lucida Console';">[2</span><span style="">，</span><span style="font-family: 'Lucida Console';">4]</span><span style="">的元素和，返回</span><span style="font-family: 'Lucida Console';">5+2+0=7</span><span style="">；</span></p>
<p>询问第<span style="font-family: 'Lucida Console';">4</span><span style="">个元素的值，返回</span><span style="font-family: 'Lucida Console';">0</span><span style="">。</span></p>
<p> </p>
<p>【数据说明】</p>
<p> </p>
<table>
<tbody>
<tr>
<td valign="center" width="150">
<p>测试点序号（<span style="font-family: 'Lucida Console';">s</span><span style="">）</span></p>
</td>
<td valign="center" width="170">
<p>数据范围</p>
</td>
<td valign="center" width="250">
<p>其他特征</p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>1,2,3,4,5</p>
</td>
<td valign="center" width="170">
<p>q=n=63,127,</p>
<p>255,511,1023</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">2</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>9</p>
</td>
<td valign="center" width="250">
<p>涉及了全部的<span style="font-family: 'Lucida Console';">4</span><span style="">种操作；</span></p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>6,7,8,9,10</p>
</td>
<td valign="center" width="170">
<p>q=1023,4095,</p>
<p>16383,131071,</p>
<p>1048575</p>
<p>n=2^4096-1<span style="">≈</span><span style="font-family: 'Lucida Console';">10^</span>1233</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">2^</span>4096-1</p>
</td>
<td valign="center" width="250">
<p>所涉及的操作只有：</p>
<p>2<span style="">查询元素值，</span><span style="font-family: 'Lucida Console';">4</span><span style="">区间求和；</span></p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>11,12,13,14,15</p>
</td>
<td valign="center" width="170">
<p>q=63,127,</p>
<p>255,511,1023</p>
<p>n=4294967295</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">1073741823</span></p>
</td>
<td valign="center" width="250">
<p>涉及了全部的<span style="font-family: 'Lucida Console';">4</span><span style="">种操作；</span></p>
<p>所有修改及查询的元素下标</p>
<p>均在<span style="font-family: 'Lucida Console';">[1</span><span style="">，</span><span style="font-family: 'Lucida Console';">n-1]</span><span style="">以内；</span></p>
<p>所有修改及查询的区间</p>
<p>都是<span style="font-family: 'Lucida Console';">[1</span><span style="">，</span><span style="font-family: 'Lucida Console';">n-1]</span><span style="">的子区间；</span></p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>16,17,18,19,20</p>
</td>
<td valign="center" width="170">
<p>q=1023,4095,</p>
<p>16383,131071,</p>
<p>1048575</p>
<p>n=1.44<span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>7</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">3.6</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>9</p>
</td>
<td valign="center" width="250">
<p>所涉及的操作有且只有：</p>
<p>1<span style="">修改元素值，</span><span style="font-family: 'Lucida Console';">2</span><span style="">查询元素值；</span></p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>21,22,23,24,25</p>
</td>
<td valign="center" width="170">
<p>q=n=1023,4095,</p>
<p>16383,131071,</p>
<p>1048575</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">7.2</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>18</p>
</td>
<td valign="center" width="250">
<p>所涉及的操作有且只有：</p>
<p>1<span style="">修改元素值，</span></p>
<p>2<span style="">查询元素值，</span><span style="font-family: 'Lucida Console';">3</span><span style="">区间增减；</span></p>
<p>所有的修改操作进行完之后，</p>
<p>才会有区间增减操作；</p>
<p>所有的区间增减操作进行完之后，</p>
<p>才会有查询操作；</p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>26,27,28,29,30</p>
</td>
<td valign="center" width="170">
<p>q=n=1023,4095,</p>
<p>16383,131071,</p>
<p>1048575</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">1.44</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>13</p>
</td>
<td valign="center" width="250">
<p>所涉及的操作有且只有：</p>
<p>1<span style="">修改元素值，</span></p>
<p>2<span style="">查询元素值，</span><span style="font-family: 'Lucida Console';">4</span><span style="">区间求和；</span></p>
<p>所有的修改操作进行完之后，</p>
<p>才会有查询以及区间求和操作；</p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>31,32,33,34,35</p>
</td>
<td valign="center" width="170">
<p>q=n=1023,4095,</p>
<p>16383,131071,</p>
<p>1048575</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">1.44</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>13</p>
</td>
<td valign="center" width="250">
<p>涉及了全部的<span style="font-family: 'Lucida Console';">4</span><span style="">种操作；</span></p>
<p>所有的修改操作进行完之后，</p>
<p>才会有区间增减操作；</p>
<p>所有的区间增减操作进行完之后，</p>
<p>才会有查询以及区间求和操作；</p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>36,37,38,39,40</p>
</td>
<td valign="center" width="170">
<p>q=n=2047,</p>
<p>4095,8191,</p>
<p>32767,131071</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">1.44</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>14</p>
</td>
<td valign="center" width="250">
<p>所涉及的操作有且只有：</p>
<p>1<span style="">修改元素值，</span></p>
<p>2<span style="">查询元素值，</span><span style="font-family: 'Lucida Console';">4</span><span style="">区间求和；</span></p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>41,42,43,44,45</p>
</td>
<td valign="center" width="170">
<p>q=n=2047,</p>
<p>4095,8191,</p>
<p>32767,131071</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤<span style="font-family: 'Lucida Console';">3.6</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>18</p>
</td>
<td valign="center" width="250">
<p>所涉及的操作有且只有：</p>
<p>1<span style="">修改元素值，</span></p>
<p>2<span style="">查询元素值，</span><span style="font-family: 'Lucida Console';">3</span><span style="">区间增减；</span></p>
</td>
</tr>
<tr>
<td valign="center" width="150">
<p>46,47,48,49,50</p>
</td>
<td valign="center" width="170">
<p>q=2047,</p>
<p>4095,8191,</p>
<p>32767,131071</p>
<p>n=2^128≈<span style="font-family: 'Lucida Console';">3.4</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>38</p>
<p>0<span style="">≤</span><span style="font-family: 'Lucida Console';">a</span>i≤2^128-1</p>
</td>
<td valign="center" width="250">
<p>所涉及的操作有且只有：</p>
<p>1<span style="">修改元素值，</span><span style="font-family: 'Lucida Console';">2</span><span style="">查询元素值；</span></p>
</td>
</tr>
</tbody>
</table>
<p><span style=""><br></span></p>
</div>
</div>