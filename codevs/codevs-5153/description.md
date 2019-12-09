<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">星期日的早上，铃木财团的顾问，铃木次郎吉再次在新闻上对基德发出了挑战。从18点开到始24点为止，将在锦座4丁目交叉路口的中央进行宝石的展示。宝物是100克拉的紫水晶装饰的凉鞋。寺井劝说快斗不要去偷，但快斗说只要有时间就可以去挑战，于是，快斗想到了瞬间移动的好方法。</span></p><p><span style="">但现在基德遇到了一些困难，想请你来帮忙。整个魔术过程可以用N个移动点与M条连接两个不同的移动点的无向通道来描述。移动点被标号为1到N，每条通道有各自的长度。所有移动点一定是连通的，并且可能存在若干个环路，但是，出于美观考虑，每个移动点最多只会属于一个简单环路。</span></p><p><span style=""></span></p><p><span style="">你需要回答多个这样的询问：假如基德处在点x，最终要移动到y点，基德最短需要走多少距离才能到达最终移动点？</span></p><p><span style=""></span><img src="/source/codevs/codevs-5153/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS8yMDE0MDgxMzE2MzIyOF9obUxQei50aHVtYi43MDBfMF8yMDE2MDcxNzExMDAyNl80NjguanBlZw==.jpeg" title=""></p><p><span style=""></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行2个整数N,M，表示魔术表演时移动点的数量和通道数；</span></p><p><span style="">接下来M行，每行3个整数x,y,z，描述一条连接移动点x与移动点y，长度为z的通道；</span></p><p><span style="">再接下来1行包含一个整数Q，表示询问数量；</span></p><p><span style="">之后Q行，每行2个整数x,y，描述一个询问。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 16px; font-family: 楷体, 楷体_GB2312, SimKai;">对于每个询问输出一行一个整数，表示基德所移动的最短距离。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 4</span></p><p><span style="">1 2 1</span></p><p><span style="">2 3 2</span></p><p><span style="">1 3 2</span></p><p><span style="">3 4 1</span></p><p><span style="">2</span></p><p><span style="">2 4</span></p><p><span style="">1 3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">3</span></p><p><span style="">2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">1≤N≤100,000，Q≤200,000，1≤x,y≤N，1≤z≤1000。</span></p><p><span style="">提示什么的去问基德吧。。。。。。</span></p>
</div>
</div>