<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>纳米猿和mmm<span style="">是好朋友。</span><span style="font-family: 'Times New Roman';">Mmm</span><span style="">的成绩很差，以至于</span><span style="font-family: 'Times New Roman';">GPA</span><span style="">（平均绩点）在年级内倒数。年级内一共有</span><span style="font-family: 'Times New Roman';">N</span><span style="">位同学，每位同学有自己的</span><span style="font-family: 'Times New Roman';">GPA</span><span style="">，以及已修学分数，定义</span><span style="font-family: 'Times New Roman';">GPT=GPA</span>×已修学分数。纳米猿为了帮助mmm<span style="">提高成绩，给</span><span style="font-family: 'Times New Roman';">mmm</span><span style="">提了一个要求：新学期的</span><span style="font-family: 'Times New Roman';">GPA</span><span style="">要超过级内排名第</span><span style="font-family: 'Times New Roman';">K</span><span style="">位同学。</span></p>
<p>为了帮助理解，这里给出一个例子：</p>
<table>
<tbody>
<tr>
<td valign="top" width="100">
<p>排名</p>
</td>
<td valign="top" width="58">
<p>GPA</p>
</td>
<td valign="top" width="96">
<p>已修学分数</p>
</td>
<td valign="top" width="93">
<p>GPT</p>
</td>
</tr>
<tr>
<td valign="top" width="100">
<p>1</p>
</td>
<td valign="top" width="58">
<p>3.8</p>
</td>
<td valign="top" width="96">
<p>21</p>
</td>
<td valign="top" width="93">
<p>79.8</p>
</td>
</tr>
<tr>
<td valign="top" width="100">
<p>2</p>
</td>
<td valign="top" width="58">
<p>3.7</p>
</td>
<td valign="top" width="96">
<p>23</p>
</td>
<td valign="top" width="93">
<p>85.1</p>
</td>
</tr>
<tr>
<td valign="top" width="100">
<p>3</p>
</td>
<td valign="top" width="58">
<p>3.65</p>
</td>
<td valign="top" width="96">
<p>20</p>
</td>
<td valign="top" width="93">
<p>73</p>
</td>
</tr>
<tr>
<td valign="top" width="100">
<p>4<span style="">（跟</span><span style="font-family: 'Times New Roman';">3</span><span style="">一样）</span></p>
</td>
<td valign="top" width="58">
<p>3.65</p>
</td>
<td valign="top" width="96">
<p>18</p>
</td>
<td valign="top" width="93">
<p>65.7</p>
</td>
</tr>
<tr>
<td valign="top" width="100">
<p>5</p>
</td>
<td valign="top" width="58">
<p>3.3</p>
</td>
<td valign="top" width="96">
<p>22</p>
</td>
<td valign="top" width="93">
<p>72.6</p>
</td>
</tr>
</tbody>
</table>
<p>现在给出年级里面每位同学<span style="font-family: 'Times New Roman';">GPT</span><span style="">（只有一位小数），以及他们的已修学分数。你需要帮助</span><span style="font-family: 'Times New Roman';">mmm</span><span style="">把排名第</span><span style="font-family: 'Times New Roman';">K</span><span style="">位的同学的</span><span style="font-family: 'Times New Roman';">GPA</span><span style="">求出来。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第<span style="font-family: 'Times New Roman';">1</span><span style="">行</span>为两个整数N,K<span style="">；</span></p>
<p>第<span style="font-family: 'Times New Roman';">2</span>至N+1行，每行1个非负实数和1<span style="">个整数</span>，分别表示GPT<span style="">和已修学分数</span>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">1个实数，表示排名第K<span style="font-family: 宋体;">同学的</span><span style="font-family: 'Times New Roman';">GPA</span><span style="font-family: 宋体;">，保留</span><span style="font-family: 'Times New Roman';">2</span><span style="font-family: 宋体;">位小数输出</span>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p>
<p>73 20</p>
<p>79.8 21</p>
<p>72.6 22</p>
<p>85.1 23</p>
<p>65.7 18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3.65</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50<span style="">％的数据满足：</span>1≤N≤100</p>
<p>100<span style="">％的数据满足：</span>1≤K≤N≤100000<span style="">，</span><span style="font-family: 'Times New Roman';">GPT</span><span style="">小数点后至多一位，</span><span style="font-family: 'Times New Roman';">GPA</span><span style="">至多</span><span style="font-family: 'Times New Roman';">4.0</span></p>
</div>
</div>