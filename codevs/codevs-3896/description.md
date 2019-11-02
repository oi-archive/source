<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      HR神犇接到一个消息，他受邀去当一场跳水比赛的评委，听到这个消息，他兴高采烈，以为自己的眼光被其他人认可，没想到，他只是被叫去计分数。。</p><p>      跳水运动员一开始有个初始分，是他们上一局所得到的。评委会对他们每一次跳水水平进行一个评比，但是这些评委比较逗，他们会选择一些编号连在一起的人，给他们评比。这些评委会让HR给这些人的分数加上一个数或者乘上一个数，还时不时会问HR他们一些编号连在一起的人的分数总和，但是因为分数可能很大，他们不想听HR念分数从早上念到晚上，所以他们会让HR把这个数模x。</p><p>      HR神犇用他那超(meng)迷(meng)人(da)的目光看着你，希望你能帮他忙。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行两个整数n,x，表示有多少个跳水运动员和模多少。</p><p>第2行n个整数，表示每个跳水运动员的初始分。</p><p>第3行一个整数m，表示跳水运动员跳水的次数。</p><p>第4行到m+4行，每行3或4个整数，第1个数为1时，读入a,b,c,d四个整数（a=1），表示给编号b到c的跳水运动员乘上d。第1个数为2时，读入a,b,c,d四个整数（a=2），表示给编号b到c的跳水运动员加上d。第1个数为3时，读入a,b,c三个整数（a=3），表示询问编号b到c的跳水运动员的分数的总和模x。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>a=3的个数行，每行一个整数，<span style="font-size: 16.3636360168457px;">表示编号b到c的跳水运动员的分数的总和模x。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 100</p><p>4 5 6 7</p><p>3</p><p>2 1 2 3</p><p>1 2 4 2</p><p>3 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>35</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=100000 m&lt;=50000 x&lt;=100000000<br></p>
</div>
</div>