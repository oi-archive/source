
# Description

<div class="content"><div style="text-indent: 21pt">我们有一个的矩形房间，被划分成了n * n个大小样的矩形格子。每个格子有两种状态，要么有箱子，要么没有箱子。箱子是一个低面为1 * 1的矩形，高为2、3或者4的长方体。开始时你被困于该房间内的S点（必有箱子）上，你想用尽量少的时间要到T点，即出口，并且你不能落到地面上。每一时刻，如果你不留在原地发呆，你可以做两件事：</div>
<div style="margin: 0cm 0cm 0pt 18pt; text-indent: -18pt"><span>1．</span>你可以移动到上下左右的某一个相邻的方格内，但是该方格必须有箱子（高度不是问题）；</div>
<div style="margin: 0cm 0cm 0pt 18pt; text-indent: -18pt"><span>2．</span>如果现在你所处的箱子的高度大于1，那么你可以把该箱子向上下左右方向推倒。推倒后原来的位置变空了，推倒后的箱子将覆盖该方向连续的相邻的height（该箱子的高度）个格子，此时你也将向该方向移动一格。但是要注意，如果你推到箱子后该箱子将倒在其他箱子上或者墙上或者出口上，那么你将不被允许去推倒它。</div>
<div style="text-indent: 17.95pt">对于每一件你可以做的事情，他们都耗费1的时间。现在你要找出一种方案，使得你可以用最少的时间到达T点。</div>
<div> </div></div>

# Input

<div class="content"><div><span>    </span>每个输入文件有多组输入（不超过100组），对于每一组数据：</div>
<div style="text-indent: 21pt">第一行三个数，n、p、q，表示箱子的长度为n(n &lt;= 8)，你初始的位置为(p, q)，这里使用窗口坐标系。</div>
<div style="text-indent: 21pt">然后n行，每行n个字符，’.’表示空地，数字（2、3、4）表示该位置箱子的高度，’E’表示该位置为出口。</div>
<div style="text-indent: 21pt">最后以三个0表示输入文件结尾。</div>
<div> </div>
<div>[</div></div>

# Output

<div class="content"><p>对于每组数据输出一行，表示最短需要的时间。无解则输出‘Impossible’。</p>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 3<br/>
.2..E<br/>
…2.<br/>
4….<br/>
….4<br/>
..2..<br/>
0 0 0<br/>
 <br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata">18<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

