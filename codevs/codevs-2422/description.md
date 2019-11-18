<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小西有一条很长的彩带，彩带上挂着各式各样的彩珠。已知彩珠有<em>N</em>个，分为<em>K</em>种。简单的说，可以将彩带考虑为x轴，每一个彩珠有一个对应的坐标(即位置)。某些坐标上可以没有彩珠，但多个彩珠也可以出现在同一个位置上。</p>
<p>小布生日快到了，于是小西打算剪一段彩带送给小布。为了让礼物彩带足够漂亮，小西希望这一段彩带中<strong>能包含所有种类的彩珠</strong>。同时，为了方便，小西希望这段彩带尽可能短，你能帮助小西计算这个最短的长度么？彩带的长度即为彩带开始位置到结束位置的位置差。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数<em>N</em>, <em>K</em>，分别表示彩珠的总数以及种类数。接下来<em>K</em>行，每行第一个数为<em>T<sub>i</sub></em>，表示第<em>i</em>种彩珠的数目。接下来<strong>按升序</strong>给出<em>T<sub>i</sub></em>个非负整数，为这<em>T<sub>i</sub></em>个彩珠分别出现的位置。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含一行，为最短彩带长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 3</p>
<p>1 5</p>
<p>2 1 7</p>
<p>3 1 3 8</p>

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
<div>
<p>对于50%的数据， <em>N</em>≤10000；</p>
<p>对于80%的数据， <em>N</em>≤800000；</p>
<p>对于100%的数据，1≤<em>N</em>≤1000000，1≤<em>K</em>≤60，0≤<em>T<sub>i</sub></em>&lt;2<sup>31</sup>。</p>
</div>
</div>
</div>