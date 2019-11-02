<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">  HR神犇最近桃花运真好，一大群妹纸围在他旁边撒娇。<br></span></p><p><span style=""><br></span></p><p>  一天早上，一个绝好的泡妞机会来了，所有的男生都请了病假，妹纸却全都到了，妹纸之间有一些空位可以给HR神犇坐，请找出有多少个这样的万花丛（上下左右都围着妹纸，中间有空位）。当然，HR神犇的眼光可不会这么低，HR神犇会以那个位置的愉悦值的高低来判断是否要坐那里。周围的妹纸越多，愉悦值越高。<span style="text-decoration: underline;">如果HR坐</span><span style="text-decoration: underline;">在</span><span style="text-decoration: underline;">某个位置上，那么HR对周围妹纸的好感值 And HR对他周围妹纸的周围的妹纸的好</span><span style="text-decoration: underline;">感</span><span style="text-decoration: underline;">值都会算进这个位置的愉悦值中。（什么鬼。。。相当于一个妹纸组成的连通块）</span><span style="">HR对普通妹纸的好感值是1点，对 </span><em style=""><strong>ZX </strong></em><span style="">的好感值</span><span style="">是5点。</span><br></p><p><span style=""><br></span></p><p>  现在，请你帮HR神犇找出所有万花丛还有判断HR神犇到底坐哪里愉悦值最高。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">  第一行包含N,M两个数(1&lt;=n&lt;=50，1&lt;=m&lt;=50)，分别表示教室的行数和列数。<br></p><p style="">  第二行包含N行，每行M个字符：ZX的位置用“l”（lover）来表示，普通妹纸的位置用“g”（girl）来表示，空位置用“e”（empty）来表示。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="white-space: normal;">&nbsp; 第一行1个整数，表示万花丛的个数，没有则输出0。<br/></p><p style="white-space: normal;">&nbsp; 第二行3个整数，表示HR神犇要坐的行列坐标以及该地区的愉悦值，没有则不用输出。<span style="text-decoration: underline;">如有多解，则输出行、列坐标最小的答案。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">4 7<br></p><p style="">g l g e e g g</p><p style="">g e g e g e g</p><p style="">g g g e e g g</p><p style="">g g g e e g g</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">2<br></p><p style="">2 2 15</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，1&lt;=n&lt;=50，1&lt;=m&lt;=50.</p><p>数据保证有且仅有一个‘l'.</p>
</div>
</div>