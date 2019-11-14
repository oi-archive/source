<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">小明刚刚学完了“中位数”这一课。他现在知道了中位数的概念。但是热爱思考的小明，拿来一张纸条，长度为</span>N<span style="">，上面写了</span>1<span style="">到</span>N<span style="">的数字。他正好对数字</span>X<span style="">很感兴趣，他想知道可以在这样一个纸条中剪出多少种长度为奇数且中位数为</span>X<span style="">的小纸条。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">文件有两行，第一行有两个数</span>N<span style="">与</span>X<span style="">，用一个空格隔开。第二行描述了这个从长度为</span>N<span style="">的纸条上写的数字。注意，<span style="text-decoration: underline;">该序列可以是无序的</span>。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 28px;"><span style="font-family:宋体">输出文件中只有一个数，表示这种可以剪出来小纸条的个数。注意：<span style="text-decoration:underline;">剪出的小纸条长度必须在</span></span><span style="text-decoration:underline;">1~N</span><span style="text-decoration:underline;"><span style="font-family:宋体">之间；若没有这样的小纸条符合要求，则输出</span>0</span><span style="text-decoration:underline;"><span style="font-family:宋体">；假设只要大纸条包含小纸条就算大纸条可以剪出小纸条</span></span><span style="font-family:宋体">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 4</p><p>1 2 3 4 5 6 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例解释】</span></p><p style=""><span style="">可以剪出的小纸条为：</span>[4];[3,4,5];[2,3,4,5,6];[1,2,3,4,5,6,7]<span style="">。总共数量有</span>4<span style="">个。</span></p><p><span style="">【数据范围】</span></p><p><span style="">在</span>20%<span style="">的数据中</span>,1&lt;=N&lt;=10,<span style="">输入保证纸条上的数是升序排列的。</span></p><p><span style="">在</span>40%<span style="">的数据中</span>,1&lt;=N&lt;=30<span style="">。</span></p><p><span style="">在</span>60%<span style="">的数据中</span>,1&lt;=N&lt;=1000,1&lt;=X&lt;=N<span style="">。</span></p><p><span style="">在</span>100%<span style="">的数据中</span>,1&lt;=N,X&lt;=100000,<span style="">输入保证纸条上任意一个数都是在</span>1~N<span style="">的范围内的整数，且没有重复的数。</span>X<span style="">、</span>N<span style="">均为整数。</span></p>
</div>
</div>