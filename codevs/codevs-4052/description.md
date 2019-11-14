<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: Fixedsys;">现在，黎恒健与YJY由于身处异地，非常迫切地想在最短的时间内相遇，然后干一架。但是由于双方都在努力地编程序想干掉对方，所以他们希望你来帮他们找到一个最好的方案使得相遇的时间最短。</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">　　   在此我们定义"相遇"为：两个人皆在同一个有编号的星球上就可以了，并且这两个人均可以站在原地等另外一个人。也就是说，在这里我们不考虑两人在宇宙中间相遇。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Fixedsys;">输入数据第一行：N和M（用空格隔开） 表示这是一个N个点的图并且有M条边</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">第二行到第M+1行 为这个图的详细信息。</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">　　  每行共有被空格隔开的三个数：a b c。表示编号为a的星球到编号为b的星球</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">　　  有一个双向边，并且要过这条双向边所需要花费的时间为c。</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">最后一行有两个数：Y和T，Y表示黎恒健所在星球（也就是月球），T表示YJY所处的</span><br style="font-family: Fixedsys;"><span style="font-family: Fixedsys;">星球（也就是天狼星）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(50, 101, 109); font-family: Fixedsys; font-size: 14px; line-height: 18px; background-color: rgb(255, 255, 255);">输出只有一行，D，表示二者&quot;相遇&quot;的最短时间。当然，如果无法相遇则输出&quot;They are all died!&quot;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>1 2 1 </p><p>2 3 1</p><p>1 3 1</p><p>1 3</p><p><br></p>

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
<p><span style="font-family: Fixedsys;">[数据范围]每组都是n=5000 m=5000 并且保证运算过程中的所有值都不会超过117901063</span></p>
</div>
</div>