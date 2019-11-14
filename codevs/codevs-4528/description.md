<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>花爸爸（<span style="">种花人民共和国主席仙人掌</span>）也叫做FTC，他是一个很有（hen)趣（tai）的学（hen）爸（tai）。</p><p>现在花爸爸复制了n个自己，每个自己有一个<span style="">疝气</span>指数，放在一条线上。<br>每一次花爸爸会询问m次，在l—r这一个区间里面这些自己疝气指数之和是不是比这个区间中的最大<span style="">疝气</span>指数的k倍大，或者修改第x个自己的<span style="">疝气</span>值为y<br>但是花爸爸忙着学习语法和平衡树（其实他现在已经会了），所以请你写一个程序帮他完成这些操作爸<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数n，m<br>第二行n个数表示从1到n所有花爸爸的疝气指数<br>后面每一行每一行一个字符c以及两个数||3个数<br>每一个操作：<br>c=Q时意味着询问l到r这个区间中是否满足区间和大于区间最大值的k倍，即 Q l r k<br>c=M时意味着修改第x位的数为y， 即M x y</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一次询问给出一个答案<br/>区间和<span style="color: rgb(192, 0, 0);">大于</span>区间最大值的k倍输出<span style="color: rgb(146, 208, 80);">YESHBBISNAIVE</span><br/>否则输出<span style="color: rgb(146, 208, 80);">NOHBBISNOTNAIVE</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 10<br>1 2 3 4 5<br>M 1 2<br>M 3 4<br>M 1 2<br>M 4 3<br>M 2 3<br>M 2 1<br>M 5 2<br>M 1 1<br>M 5 5<br>M 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>EOF（无输出）<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>|每个数| &lt;=
<span style="">10000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000（好
多个0）</span><br>n =m = 30000<br>l和r的关系不确定<br>为了让题目有人做，所以花爸爸决定数据中没有<span style="">fu数</span><br>究竟是哪个“<span style="">fu</span>”数呢，就看你们的脸了</p>
</div>
</div>