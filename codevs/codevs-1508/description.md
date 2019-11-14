<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　众所周知，在每一个彗星后都有一只UFO。这些UFO时常来收集地球上的忠诚支持者。不幸的是，他们的飞碟每次出行都只能带上一组支持者。因此，他们要用一种聪明的方案让这些小组提前知道谁会被彗星带走。他们为每个彗星起了一个名字，通过这些名字来决定这个小组是不是被带走的那个特定的小组（你认为是谁给这些彗星取的名字呢？）。关于如何搭配的细节会在下面告诉你；你的任务是写一个程序，通过小组名和彗星名来决定这个小组是否能被那颗彗星后面的UFO带走。</p>
<p>　　小组名和彗星名都以下列方式转换成一个数字：最终的数字就是名字中所有字母的积，其中“A”是1，“Z”是26。例如，“USACO”小组就是21*19*1*3*15=17955。如果小组的数字 mod 47等于彗星的数字mod 47,你就得告诉这个小组需要准备好被带走！（记住“a mod b”是a除以b的余数；34 mod 10等于4）</p>
<p>　　写出一个程序，读入彗星名和小组名并算出用上面的方案能否将两个名字搭配起来，如果能搭配，就输出“GO”，否则输出“STAY”。小组名和彗星名均是没有空格或标点的一串大写字母（不超过6个字母）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个长度为1到6的大写字母串，表示彗星的名字。</p>
<p>第2行：一个长度为1到6的大写字母串，表示队伍的名字。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，包括&ldquo;GO&rdquo;或&ldquo;STAY&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>COMETQ</p>
<p>HVNGAT</p>
<p>【样例输入2】</p>
<p>ABSTAR</p>
<p>USACO</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】</p>
<p>GO</p>
<p>【样例输出2】</p>
<p>STAY</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>