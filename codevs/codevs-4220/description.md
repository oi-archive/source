<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了使同学有更多的时间编程，凡凡把10把计算机机房的钥匙分给了10位同学，每位同学需要同时使用钥匙和个人密码才能够打开机房，通过个人密码凡凡老师能够查看每个学生的访问记录。</p><p>为此，凡凡老师设计了一种加密方式：明文是长度为N的K进制数字串S（数字间有空格），S'由S中连续的一段（或一个）组成。对应字符串的价值是：它所代表的K进制数转换为十进制后的数。</p><p>个人密码的分配如下：对于编号为x(0&lt;=x&lt;=9)的同学，他的个人密码是<strong>满足对应规则的S'的个数</strong>，规则为：对于一个非空字串S'，当其十进制价值的最后一位为x时，满足条件。</p><p>现在，凡凡老师请你将他给的明文转化为10个个人密码</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个用空格分开的正整数N 和K ，分别表示S 的长度和数组串的进制。</p><p>第二行为N 个用空格分开的非负整数，依次表示S1,S2,S3,S4...SN</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共 10 行，为x等于0...9时的答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 12</p><p>1 2 3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p><p>2</p><p>1</p><p>1</p><p>2</p><p>0</p><p>1</p><p>1</p><p>1</p><p>0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20% 的数据，N&lt;=200。</p><p>对于 50% 的数据，N&lt;=3000。</p><p>对于 80% 的数据，N&lt;=10^5。</p><p>对于 100%的数据， N&lt;=10^6,2&lt;=k&lt;=10^9,0&lt;=Si&lt;k</p><p><br></p>
</div>
</div>