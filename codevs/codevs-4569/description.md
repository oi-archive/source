<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>收下巧克力，rxt心情大好，决定跟tjx一起（坐着他们家的豪华法拉利）去外面兜风。</p><p>众所周知，富人都喜欢居住在远离城市的地方，tjx也不例外。已知他们俩住在一个不知名的小城，城里的道路是封闭的（即在路中间不能出马路），有n个出入口，编号为0到n-1，有m条道路，他们全部都是单向的。（什么鬼奇怪的城镇）</p><p>俗话说，跟女神同行，谁都希望遇到多一点熟人。现在某些路上有些熟人，全都是单身的，tjx想兜风的时候能虐更多的狗。tjx可以从任意一个出入口上公路，且燃油充足。</p><p>另外，这个小镇的警察很缺钱，他们决定如果发现tjx逆行，就没收他所有的财产。现在问在安全情况下，tjx兜风一次最多能虐狗多少？已知虐狗值为他经过的公路的虐狗值之和。如果不存在最大的虐狗值，请输出“No solution”（不包含引号）</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为正整数n和m，含义如题目描述</p><p>下面m行，每行为一个整数s,t,w，代表s到t有一条虐狗值为w的道路。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两个整数，第一个为虐狗值的最大值，第二个为tjx离开公路的出口的编号，两个数之间用一个空格隔开</p><p>或者是“No solution”</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4</p><p>0 2 5</p><p>2 1 4</p><p>1 3 6</p><p>0 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n≤100000，m ≤4*n</p><p>数据范围很小的</p><p>注意公路出口是从0开始编号</p>
</div>
</div>