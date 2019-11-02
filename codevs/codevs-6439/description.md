<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    以前我们玩过一个猜数字游戏，在一定范围内电脑随机选择一个整数，你来猜，电脑会告诉你是大或者是小了。这一次你在1-999999内输入一个数字，电脑来猜。假设电脑不知情，它猜的方法是二分法（对于确定的大小边界，取两边界的中间值，根据该中间值与所猜数字的大小比较来判断下一次是取小的那部分的中间值还是大的那部分，然后以此类推），直到猜对为止。电脑有18次猜的机会（20次以内肯定能猜对，所以这里扣掉两次，不能让它每次都能猜对），如果它在18次以内没有猜对，输出“Sorry, the computer is lost.”并换行，输出你所输入的数。如果他能猜对，输出“Congratulations on the computer!”换行，输出猜的次数。中间每一次，如果大了，输出“Larger”，反之输出“Smaller”。想想你当时是怎么猜的吧。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行，一个1-999999之间的正整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>2i+1或+2行，第2k-1行输出电脑所猜的数字，2k行输出判断结果（大或者小）,直到k=18或者已经猜对了结束。接下来的在题目描述中已经说过了。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：482596</p><p>样例2：773377</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>(样例1） </p><p>500000</p><p>Larger</p><p>250000</p><p>Smaller</p><p>375000</p><p>Smaller</p><p>437500</p><p>Smaller</p><p>468750</p><p>Smaller</p><p>484375</p><p>Larger</p><p>476562</p><p>Smaller</p><p>480468</p><p>Smaller</p><p>482421</p><p>Smaller</p><p>483398</p><p>Larger</p><p>482909</p><p>Larger</p><p>482665</p><p>Larger</p><p>482543</p><p>Smaller</p><p>482604</p><p>Larger</p><p>482573</p><p>Smaller</p><p>482588</p><p>Smaller</p><p>482596</p><p>Congratulations on the computer!</p><p>17</p><p>（样例2）</p><p>500000</p><p>Smaller</p><p>750000</p><p>Smaller</p><p>875000</p><p>Larger</p><p>812500</p><p>Larger</p><p>781250</p><p>Larger</p><p>765625</p><p>Smaller</p><p>773437</p><p>Larger</p><p>769531</p><p>Smaller</p><p>771484</p><p>Smaller</p><p>772460</p><p>Smaller</p><p>772948</p><p>Smaller</p><p>773192</p><p>Smaller</p><p>773314</p><p>Smaller</p><p>773375</p><p>Smaller</p><p>773406</p><p>Larger</p><p>773390</p><p>Larger</p><p>773382</p><p>Larger</p><p>773378</p><p>Larger</p><p>Sorry, the computer is lost.</p><p>773377</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，保证输入数据在1-999999之间，猜的次数不超过18.</p>
</div>
</div>