<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们知道OI界存在非常多的信仰,比如ydc神教,泉岭精神,gty小弟团等等<br></p><p>现在CreationAugust想统计一下这些信仰的情况.</p><p>具体的统计方法是</p><p>现在有n个数,表示一些人的信仰值,不同的信仰值代表不同的宗教.</p><p>CreationAugust给定了你一个数k,要不断询问ai~ai+k-1这段区间中只有一个人信仰的那些宗教里,最大信仰值是多少.<br></p><p>没有询问,你要依次回答a1~a1+k-1  a2~a2+k-1.....以此类推(i+k-1&lt;=n)<br></p><p>共计n-k+1个询问</p><p>一句话题意:<span style="FONT-FAMILY: 'microsoft yahei';">求区间内只出现过一次的元素里的最大元素 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数n和k<br></p><p>接下来n个数ai</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>n-k+1行,每行一个数,为所求最大值.<br/></p><p>如果某区间没有只出现过一次的数,请输出&quot;Nothing&quot;.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="FONT-FAMILY: 'microsoft yahei';">5 3 </span><br style="FONT-FAMILY: 'microsoft yahei';"><span style="FONT-FAMILY: 'microsoft yahei';">1 </span><br style="FONT-FAMILY: 'microsoft yahei';"><span style="FONT-FAMILY: 'microsoft yahei';">2 </span><br style="FONT-FAMILY: 'microsoft yahei';"><span style="FONT-FAMILY: 'microsoft yahei';">2 </span><br style="FONT-FAMILY: 'microsoft yahei';"><span style="FONT-FAMILY: 'microsoft yahei';">3 </span><br style="FONT-FAMILY: 'microsoft yahei';"><span style="FONT-FAMILY: 'microsoft yahei';">3 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="FONT-FAMILY: 'microsoft yahei';">1 </span><br style="FONT-FAMILY: 'microsoft yahei';"><span style="FONT-FAMILY: 'microsoft yahei';">3 </span><br style="FONT-FAMILY: 'microsoft yahei';"><span style="FONT-FAMILY: 'microsoft yahei';">2 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=10^5 k&lt;=n</p><p>-10^9&lt;=ai&lt;=10^9</p>
</div>
</div>