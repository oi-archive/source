<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>打保龄球是用一个滚球去打击十个站立的柱，将柱击倒。一局分十轮，每轮可滚球一次或多次，以击倒的柱数为依据计分。一局得分为十轮得分之和，而每轮的得分不仅与本轮滚球情况有关，还可能与后续一两轮的滚球情况有关。即某轮某次滚球击倒的柱数不仅要计入本轮得分，还可能会计入前一两轮得分。具体的滚球击柱规则和计分方法如下：</p>
<p>   （1）若某一轮的第一次滚球就击倒全部十个柱，则本轮不再滚球（若是第十轮则还需</p>
<p>另加两次滚球，不妨称其为第十一轮和第十二轮，并不是所有的情况都需要滚第十一轮和第十二轮球）。该轮得分为本次击倒柱数10与以后两次滚球所击倒柱数之和。</p>
<p>   （2）若某一轮的第一次滚球未击倒十个柱，则可对剩下未倒的柱再滚球一次。如果这</p>
<p>两次滚球击倒全部十个柱，则本轮不再滚球（若是第十轮则还需另加一次滚球），该轮得分</p>
<p>为这两次共击倒柱数10与以后一次滚球所击倒柱数之和。</p>
<p>   （3）若某一轮两次滚球未击倒全部十个柱，则本轮不再继续滚球，该轮得分为这两次</p>
<p>滚球击倒的柱数之和。</p>
<p>    总之，若—轮中一次滚球或两次滚球击倒十个柱，则本轮得分是本轮首次滚球开始的</p>
<p>连续三次滚球击倒柱数之和（其中有一次或两次不是本轮滚球）。若一轮内二次滚球击倒柱</p>
<p>数不足十个，则本轮得分即为这两次击倒柱数之和。下面以实例说明如下(字符“/”表示击倒当前球道上的全部的柱)：</p>
<p>    轮          1    2   3    4    5    6    7    8    9   10   11   12</p>
<p>    击球情况    /    /    /    72   9/   81   8/    /    9/    /    8/</p>
<p>    各轮得分   30   27   19   9   18    9   20   20   20   20</p>
<p>累计总分   30   57  76   85  103   112  132  152  172  192</p>
<p>现在请你编写一个保龄球实时计分程序，用来计算和显示某轮结束后的得分情况。若某轮的得分暂时无法算出，则该轮得分不显示。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅有一行，为前若干轮滚球的情况，每轮滚球用一到两个字符表示，每一个字符表示一次击球，字符“/”表示击倒当前球道上的全部的柱，否则用一个数字字符表示本次滚球击倒的当前球道上的柱的数目，两轮滚球之间用一个空格字符隔开。</p>
<p>如上例对应的输入文件内容为：/  /  /  72  9/  81  8/  /  9/  /  8/</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共两行，第一行为每轮得分，第二行为到当前轮为止的总得分。每个得分之间用一个空格隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> /    /    /   72    9/   81   8/    /    9/    /   8/</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30   27  19   9   18   9   20   20   20   20</p>
<p>30   57  76   85  103  112  132  152  172  192</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>  </p>
</div>
</div>