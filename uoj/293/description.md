# 题目描述

<p>给定一个仅由0和1组成的数列$\{a_0, a_1, \cdots, a_{n - 1}\}$。求有多少个仅有0和1组成的长度在$1$到$n$之间的数列$\{b_0, b_1, \cdots, b_{m - 1}\}$，使得对于任意$0 \le p \le n - m$，$\sum_{k = 0} ^ {m - 1}{a_{p + k} \wedge b_k}$均为偶数。</p>
<p>答案对1000000007取模。</p>

# 输入格式


<p>一行一个01串，表示数列$a$，从左到右的第$k$个字符表示$a_k$。</p>

# 输出格式


<p>一行一个整数表示数列$b$的个数对1000000007取模的值。</p>

# 样例一


<h4>input</h4>
<pre>00101110101110101011

</pre>

<h4>output</h4>
<pre>699063

</pre>


# 样例二


<h4>input</h4>
<pre>00001100100101110011110011100010011010101011001010

</pre>

<h4>output</h4>
<pre>932640914

</pre>


# 限制与约定


<p>每组测试数据的限制与约定如下所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \le 20$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="4">$n \le 100$</td></tr><tr><td>4</td>
</tr><tr><td>5</td>
</tr><tr><td>6</td>
</tr><tr><td>7</td><td rowspan="6">$n \le 5000$</td></tr><tr><td>8</td>
</tr><tr><td>9</td>
</tr><tr><td>10</td>
</tr><tr><td>11</td>
</tr><tr><td>12</td>
</tr><tr><td>13</td><td rowspan="8">$n \le 50000$</td></tr><tr><td>14</td>
</tr><tr><td>15</td>
</tr><tr><td>16</td>
</tr><tr><td>17</td>
</tr><tr><td>18</td>
</tr><tr><td>19</td>
</tr><tr><td>20</td>
</tr></tbody></table></div>

<p>对于全部数据$1 \le n \le 50000$，输入数据中的串是一个01串。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$1024\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=293">样例数据<strong>及题解</strong>下载</a></p>

# 来源


<p>matthew99</p>
