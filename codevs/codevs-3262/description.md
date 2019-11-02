<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>时间过得真快，</p>
<p>时间过的真快，转眼钱宗伟升入了初二。<br>他注定不是一个安分的人（或者说花心），他把他的注意力放在了那些初一的学妹们（生物老师言：多吃多占），并制定了严密的泡学妹计划（明知狼多肉少）。<br>但：<br>很不幸，这个计划被孙毅远（可恶，这家伙为了那子虚乌有的一元钱以及利息追了我三年）发现了，并威胁要告诉老班！<br>当然，如果钱宗伟帮孙毅远解决一道C语言题目，他会考虑保密（不然孙毅远会被出题人干掉的）。要知道，去年钱宗伟那NOIP一战不知使多少清纯少女倾心。<br>钱宗伟只好答应( 不然就是思想汇报一篇，以及请家长）。<br>这是孙毅远亲戚出的一道题（他们家族关系太复杂，我也不知道辈分）：<br>下面是一个乘法竖式，如果用我们给定的那n个数字来取代*，可以使式子成立的话，我们就叫这个式子Y式（以那人名字命名，保护当事人隐私）</p>
<p>* * *<br> x * *<br> -------<br> * * *<br> * * *<br> -------<br> * * * *</p>
<p>数字只能取代*，当然第一位不能为0。</p>
<p>注意：“部分乘积”，第一部分乘积是第二个数的个位和第一个数的积，第二部分乘积是第二个数的十位和第一个数的乘积.</p>
<p>写一个程序找出所有的Y式。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行:数字的个数n。</p>
<p>第二行:N个用空格分开的数字（每个数字都∈{1,2,3,4,5,6,7,8,9}）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>共一行，一个数字。表示Y式的总数</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5</span><br><span>2 3 4 6 8</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>下面是样例的那个Y式。</span><br><span>      2 2 2</span><br><span>    x   2 2</span><br><span>     ------</span><br><span>      4 4 4</span><br><span>    4 4 4</span><br><span>  ---------</span><br><span>    4 8 8 4</span></p>
<p><span>此题改编自USACO  </span><span style="">Prime Cryptarithm</span></p>
<p>建议使用枚举</p>
<p><strong>The constraints of this problem are small enough that we can just try all possible products of 3 digit * 2 digit numbers, and look to see if all the correct digits are used.</strong></p>
<p><strong>The function "isgood" checks that a number is composed only of acceptable digits, and "isgoodprod" checks that all the lines of the multiplication are composed of acceptable digits.</strong></p>
</div>
</div>