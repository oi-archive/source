<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个边长为n的正三角形可以被划分成若干个小的边长为1的正三角形，称为单位三角形。边长为3的正三角形被分成三层共９个小的正三角形，我们把它们从顶到底，从左到右以1~9编号。同理，边长为n的正三角形可以划分成n<sup>2</sup>个单位三角形。</p>
<p> </p>
<p>四个这样的边长为n的正三角形可以组成一个三棱锥。我们将正三棱锥的三个侧面依顺时针次序(从顶向底视角)编号为A, B, C，底面编号为D。侧面的A, B, C号三角形以三棱锥的顶点为顶，底面的D号三角形以它与A, B三角形的交点为顶。左图为三棱锥展开后的平面图，每个面上标有圆点的是该面的顶，该图中侧面A,B,C分别向纸内方向折叠即可还原成三棱锥。我们把这A、B、C、D四个面各自划分成n<sup>2</sup>个单位三角形。</p>
<p>对于任意两个单位三角形，如有一条边相邻，则称它们为相邻的单位三角形，显然，每个单位三角形有三个相邻的单位三角形。现在，把1~4n<sup>2</sup>分别随机填入四个面总共4n<sup>2</sup>个单位三角形中。</p>
<p>现在要求你编程求<strong>由单位三角形组成的最大排序二叉树</strong>。所谓最大排序二叉树，是指在所有由单位三角形组成的排序二叉树中节点最多的一棵树。对于任一单位三角形，可选它三个相邻的单位三角形中任意一个作为父节点，其余两个分别作为左孩子和右孩子。当然，做根节点的单位三角形不需要父节点，而左孩子和右孩子对于二叉树中的任意节点来说并不是都必须的。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">其中第一行是一个整数n，随后4n<sup>2</sup>行，依次为三棱锥四个面上所填的数字。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>其中仅包含一个整数，表示最大的排序二叉树所含的节点数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="96">
<p><span style="">19</span></p>
<p>33</p>
<p>32</p>
<p>31</p>
<p>29</p>
<p>3</p>
<p>5</p>
<p>4</p>
<p>30</p>
</td>
<td valign="top" width="96">
<p>22</p>
<p>25</p>
<p>20</p>
<p>21</p>
<p>12</p>
<p>24</p>
<p>23</p>
<p>34</p>
<p>35</p>
<p> </p>
</td>
<td valign="top" width="96">
<p><span style="">14</span></p>
<p>13</p>
<p>15</p>
<p>26</p>
<p>18</p>
<p>17</p>
<p>8</p>
<p>16</p>
<p>27</p>
<p> </p>
</td>
<td valign="top" width="96">
<p>11</p>
<p><span style="">10</span></p>
<p>9</p>
<p>1</p>
<p>28</p>
<p>7</p>
<p>2</p>
<p>6</p>
<p>36</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">1&lt;=n&lt;=18</p>
</div>
</div>