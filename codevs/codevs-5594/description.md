<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>今天，编程十分厉害的小明刚刚学了一元二次方程。刚回到家，他就迫不及待地打开电脑。回想一下今天学的，他发现如果只属于a（二次项系数），b（一次项系数），c（常数）的话就太简单了，所以他灵机一动，想出了一个办法：输入一个完整的一元二次方程（ax^2+bx+c=0），先判断其是否有解，若有解，输出；若误解，输出No Answer。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个字符串（完整的一元二次方程）</p><p>一元二次方程的根的判别式：△=b*b-4*a*c；</p><p>（1）当△=0时，方程具有一个实数根（或两个相等实数根） <br></p><p>（2）当△&lt;0时，方程无解</p><p>（3）当△&gt;0时，方程具有两个不相等实数根</p><p>一元二次方程的求根公式：x1=（-b+sqrt（△））/2*a； <br></p><p>                                         x2=（-b-sqrt（△））/2*a；</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>方程的解或No Answer</p><p>若方程有两个相同的跟，则输出x1=x2=....（注：未知数不一定都是x，但属于[a-z][A-Z]区分大小写）。</p><p>如果方程不是二次的，则输出MATH ERROR<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例一：-x^2-6x+5=0</p><p>样例二：x^2+2x=-1</p><p>样例三：98.32x^2+6.32156x+6.3256=8x^2+9.36x</p><p>样例四：-x^2=-x^2+1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例一：x1=-6.742 x2=0.742（注：有空格）</p><p>样例二：x1=x2=-1.000</p><p>样例三：No Answer</p><p>样例四：MATH ERROR<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>字符串长度不限，其中运算符号只有+，-，^2，与小数点。<br></p>
</div>
</div>