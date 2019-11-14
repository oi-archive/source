<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Liyundu大神要去约妹子，已知他手中有n张邀请卷，每一张邀请卷上有一个二进制串(如010101)，表达多个妹子的邀请状态(并且已经按照优先级降序排序)，如(010101)就代表邀请1、3、5号妹子，注意邀请卷可以无限搭配使用，但每张只能使用一次。另外妹子们非常傲娇，如果被邀请两次就不会去了，但是被邀请三次就又会去(以此类推)。作为Liyundu大神的朋友，我们自然要帮一帮他，请编写程序找到在妹子优先级最高的情况下约到的妹子尽量多的方法。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示会有n张邀请卷</p><p>接下来n行每行有一个10进制整数Ai,表示一张邀请卷。</p><p>(为了方便输入输出并降低难度，已经把所有邀请卷的方案转化为10进制整数)</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行一个10进制整数x，代表邀请妹子的方案。</p><p>第二行一个整数y，代表邀请到的妹子数目。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>7</p><p>23</p><p>39</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>55</p><p>5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据有</p><p>n&lt;=50;</p><p>0&lt;=Ai&lt;=2^31</p><p><br></p>
</div>
</div>