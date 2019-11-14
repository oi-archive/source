<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">有N棵小草，编号0至N-1。奶牛Bessie不喜欢小草，所以Bessie要用剪刀剪草，目标是使得这N棵小草的高度总和不超过H。在第0时刻，第i棵小草的高度是h[i]，接下来的每个整数时刻，会依次发生如下三个步骤：</span></p><p style=""><span style="">（1）每棵小草都长高了，第i棵小草长高的高度是grow[i]。 </span></p><p style=""><span style="">（2）Bessie选择其中一棵小草并把它剪平，这棵小草高度变为0。注意：这棵小草并没有死掉，它下一秒还会生长的。</span></p><p style=""><span style="">（3）Bessie计算一下这N棵小草的高度总和，如果不超过H，则完成任务，一切结束，    否则轮到下一时刻。</span></p><p><span style="">你的任务是计算：最早是第几时刻，奶牛Bessie能完成它的任务？如果第0时刻就可以完成就输出0，如果永远不可能完成，输出-1，否则输出一个最早的完成时刻。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行，两个整数N和H。 1 </span><span style="">≤</span><span style=""> N </span><span style="">≤</span><span style=""> 50</span><span style="">，0 </span><span style="">≤</span><span style=""> H </span><span style="">≤</span><span style=""> 1000000</span><span style="">。</span></p><p style=""><span style="">第二行，N个整数，表示h[i]。0 </span><span style="">≤</span><span style=""> h[i] </span><span style="">≤</span><span style=""> 100000</span><span style="">。</span></p><p style=""><span style="">第三行，N个整数，表示grow[i]。1 </span><span style="">≤</span><span style=""> grow[i] </span><span style="">≤</span><span style=""> 100000</span><span style="">。</span></p><p style=""><span style="">    </span><strong><span style="">对于20%的<span style="">数据</span>， 1 </span></strong><span style="">≤</span><strong><span style=""> N </span></strong><span style="">≤</span><strong><span style=""> 7。</span></strong></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:32px;line-height:125%"><span style="font-size:16px;line-height:125%;font-family:宋体">一个整数，最早完成时刻或-1。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">3  16</span></p><p style=""><span style="">5  8  58</span></p><p><span style="">2  1  1  </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">1 </span><span style="">≤</span><span style=""> N </span><span style="">≤</span><span style=""> 50</span><span style="">，0 </span><span style="">≤</span><span style=""> H </span><span style="">≤</span><span style=""> 1000000</span><span style="">。<span style="">h[i]</span><span style="">。0 </span><span style="">≤</span><span style=""> h[i] </span><span style="">≤</span><span style=""> 100000</span></span></p><p><span style=""><span style=""><span style="">grow[i]</span><span style="">。1 </span><span style="">≤</span><span style=""> grow[i] </span><span style="">≤</span><span style=""> 100000</span><span style="">。</span></span></span></p>
</div>
</div>