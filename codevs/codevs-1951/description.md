<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小 Z有一片森林， 含有 N个节点， 每个节点上都有一个非负整数作为权值。初始的时候，森林中有 M 条边。 <br>    小 Z希望执行T 个操作，操作有两类： <br>    1、Q x y k 查询点 x 到点 y路径上所有的权值中，第k小的权值是多少。此操作保证点x 和点 y连通，同时这两个节点的路径上至少有 k个点。 <br>    2、L x y 在点x 和点 y之间连接一条边。保证完成此操作后，仍然是一片森林。 <br>    为了体现程序的在线性，我们把输入数据进行了加密。设 lastans 为程序上一次输出的结果，初始的时候 lastans 为0。 <br>    对于一个输入的操作 Q x y k，其真实操作为 Q x^lastans y^lastans k^lastans。 <br>    对于一个输入的操作 L x y，其真实操作为 L x^lastans y^lastans。 <br>    其中^运算符表示异或，等价于pascal 中的 xor运算符。 <br>    请写一个程序来帮助小 Z完成这些操作。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行包含一个正整数 testcase，表示当前测试数据的测试点编号。保证 1≤testcase≤20。 <br>    第二行包含三个整数 N，M，T，分别表示节点数、初始边数、操作数。 <br>    第三行包含N个非负整数表示N个节点上的权值。 <br>    接下来 M 行，每行包含两个整数 x 和 y，表示初始的时候，点 x 和点 y 之间有一条无向边。 <br>    接下来 T行，每行描述一个操作，格式为“Q x y k”或者“L x y”，其含义见题目描述部分。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个第一类操作，输出一个非负整数表示答案。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 <br>8 4 8 <br>1 1 2 2 3 3 4 4 <br>4 7 <br>1 8 <br>2 4 <br>2 1 <br>Q 8 7 3 <br>Q 3 5 1<br><span style="">Q 10 0 0<br></span><span style="">L 5 4 <br></span><span style="">L 3 2 <br></span><span style="">L 0 7 <br></span><span style="">Q 9 2 5 <br></span><span style="">Q 6 1 6</span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 <br>2 <br>1 <br>4 <br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】 <br>解密后的操作为 <br>Q 8 7 3 <br>Q 1 7 3 <br>Q 8 2 2 <br>L 4 5 <br>L 2 3 <br>L 1 6 <br>Q 8 3 4 <br>Q 2 5 2 <br><br>    对于第一个操作 Q 8 7 3，此时lastans=0，所以真实操作为 Q 8^0 7^0 3^0，也即Q 8 7 3。点8到点 7的路径上一共有5个点，其权值为 4 1 1 2 4。这些权值中，第三小的为2，输出 2，lastans 变为2。 <br>    对于第二个操作 Q 3 5 1，此时lastans=2，所以真实操作为 Q 3^2 5^2 1^2，也即Q 1 7 3。点1到点 7的路径上一共有4个点，其权值为 1 1 2 4。这些权值中，第三小的为2，输出 2，lastans 变为2。<br>    之后的操作类似。 <br><br><br>【数据范围】</p>
<table border="0">
<tbody>
<tr>
<td>测试点编号</td>
<td>N,M,T的上限</td>
<td>L操作</td>
<td>Q操作</td>
<td>形态</td>
</tr>
<tr>
<td>1</td>
<td>20</td>
<td>N/A</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>2</td>
<td>200</td>
<td>N/A</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>3</td>
<td>4*10<sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>链</td>
</tr>
<tr>
<td>4</td>
<td>4*10<sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>链</td>
</tr>
<tr>
<td>5</td>
<td>8*10<sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>链</td>
</tr>
<tr>
<td>6</td>
<td><span>8*10</span><sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>链</td>
</tr>
<tr>
<td>7</td>
<td><span>8*10</span><sup>4</sup></td>
<td>无L操作</td>
<td>保证k=1</td>
<td>N/A</td>
</tr>
<tr>
<td>8</td>
<td><span>8*10</span><sup>4</sup></td>
<td>无L操作</td>
<td><span>保证k=1</span></td>
<td>N/A</td>
</tr>
<tr>
<td>9</td>
<td><span>8*10</span><sup>4</sup></td>
<td>无L操作</td>
<td><span>保证k=1</span></td>
<td>N/A</td>
</tr>
<tr>
<td>10</td>
<td>4*10<sup>4</sup></td>
<td>N/A</td>
<td><span>保证k=1</span></td>
<td>N/A</td>
</tr>
<tr>
<td>11</td>
<td>4*10<sup>4</sup></td>
<td>N/A</td>
<td><span>保证k=1</span></td>
<td>N/A</td>
</tr>
<tr>
<td>12</td>
<td>8*10<sup>4</sup></td>
<td>N/A</td>
<td><span>保证k=1</span></td>
<td>N/A</td>
</tr>
<tr>
<td>13</td>
<td>8*10<sup>4</sup></td>
<td>N/A</td>
<td><span>保证k=1</span></td>
<td>N/A</td>
</tr>
<tr>
<td>14</td>
<td><span>4*10</span><sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>15</td>
<td><span>4*10</span><sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>16</td>
<td>8*10<sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>17</td>
<td>8*10<sup>4</sup></td>
<td>无L操作</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>18</td>
<td><span>4*10</span><sup>4</sup></td>
<td>N/A</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>19</td>
<td>8*10<sup>4</sup></td>
<td>N/A</td>
<td>N/A</td>
<td>N/A</td>
</tr>
<tr>
<td>20</td>
<td>8*10<sup>4</sup></td>
<td>N/A</td>
<td>N/A</td>
<td>N/A </td>
</tr>
</tbody>
</table>
<p>N/A表示没有特殊性</p>
</div>
</div>