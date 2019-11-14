<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    贝贝是一个聪明的小孩，从小就对数字特别有兴趣，喜欢研究数字的规律。一天，当老师教会他把十进制数转换成二进制数后，他就开始想：十进制数还可以转换成其他进制数吗？他就尝试用类似于十进制转换为二进制的方法进行转换。在转换的过程中，他发现有些数据是很有特点的：</p>
<p>    在一对数字之间交替转换的数，如1212121，将它命名为波浪数。在两种进制下都是波浪数的数就叫双重波浪数，如十进制数191919是一个十进制下的波浪数，它对应的十一进制数121212也是一个波浪数，所以十进制数191919是一个双重波浪数。</p>
<p>类似的可以定义三重波浪数，三重波浪数在三种不同的进制中都是波浪数。甚至还有四重波浪数，如十进制数300=606（七进制）=363（九进制）=454（八进制）=1A1（十三进制）……，你的任务就是用不超过2秒的时间在指定范围内找出双重、三重、四重波浪数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>1行，包含五个用空格隔开的十进制整数，前两个数表示进制的范围(2～32)，第三与第四个数表示指定的范围(1～10000000)，第五个数为2，3，4中的一个，表示要找的波浪数的重数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;&nbsp;从小到大，以十进制形式输出指定范围内的指定重数的波浪数，一行输出一个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 11 190000 960000 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>191919</p>
<p>383838</p>
<p>575757</p>
<p>767676</p>
<p>959595</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见输入描述</p>
</div>
</div>