<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Memory_of_winter一家人去旅游，但路面高低不平，他们想找一条最舒适的路线</p><p>他们在一个n*m的空间里，从（1,1）出发，去（n,m），寻找一条路线（只能往右、下走），使中途高度差的最大值最小（已在洛谷发出比赛）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行:n,m</p><p>第2~n+1行:每行m个整数,第i行第j个整数表示位置（i-1,j）的高度（可能为负）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数：最小的中途高度差最大值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 4</p><p>4 5 6 7</p><p>9 9 9 9</p><p>1 2 3 4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n,m&lt;=500   //典型的宽(dong)搜(gui)题</p><p>随机数据，生成代码如下</p><p>var</p><p> n,m,l,r,i,j:longint;</p><p>begin</p><p> randomize;</p><p> readln(n,m,l,r);</p><p> writeln(n,' ',m);</p><p> for i:=1 to n do</p><p>  begin</p><p>   for j:=1 to m do write(random(r-l+1)+l,' ');</p><p>   writeln;</p><p>  end;</p><p>end.</p><p><br></p>
</div>
</div>