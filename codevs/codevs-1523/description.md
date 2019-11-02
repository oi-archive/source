<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    传说很久以前，大地上居住着一种神秘的生物：地精。 <br>    地精喜欢住在连绵不绝的山脉中。具体地说，一座长度为 N 的山脉 H可分为从左到右的 N 段，每段有一个独一无二的高度 Hi，其中Hi是1到N 之间的正整数。 <br>    如果一段山脉比所有与它相邻的山脉都高，则这段山脉是一个山峰。位于边缘的山脉只有一段相邻的山脉，其他都有两段（即左边和右边）。 <br>    类似地，如果一段山脉比所有它相邻的山脉都低，则这段山脉是一个山谷。 <br>    地精们有一个共同的爱好——饮酒，酒馆可以设立在山谷之中。地精的酒馆不论白天黑夜总是人声鼎沸，地精美酒的香味可以飘到方圆数里的地方。 <br>    地精还是一种非常警觉的生物，他们在每座山峰上都可以设立瞭望台，并轮流担当瞭望工作，以确保在第一时间得知外敌的入侵。 <br>    地精们希望这N 段山脉每段都可以修建瞭望台或酒馆的其中之一，只有满足这个条件的整座山脉才可能有地精居住。 <br>    现在你希望知道，长度为N 的可能有地精居住的山脉有多少种。两座山脉A和B不同当且仅当存在一个 i，使得 Ai≠Bi。由于这个数目可能很大，你只对它除以P的余数感兴趣。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入仅含一行，两个正整数 N,P。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅含一行，一个非负整数，表示你所求的答案对P取余之后的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>共有10 种可能的山脉，它们是： <br>1324 <span style="">1423 2143 2314 2413 <br></span><span style="">3142 3241 3412 4132 4231 <br><br><br><br></span></p>
<p>【数据规模和约定】 <br>对于 20%的数据，满足 N≤10； <br>对于 40%的数据，满足 N≤18； <br>对于 70%的数据，满足 N≤550； <br>对于 100%的数据，满足 3≤N≤4200，P≤10<sup>9</sup>。</p>
<p> </p>
</div>
</div>