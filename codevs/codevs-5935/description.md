<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>许多的小球一个一个的从一棵满二叉树上掉下来组成FBT（Full Binary Tree，满二叉树），每一时间，一个正在下降的球第一个访问的是非叶子节点。然后继续下降时，或者走右子树，或者走左子树，直到访问到叶子节点。决定球运动方向的是每个节点的布尔值。最初，所有的节点都是FALSE，当访问到一个节点时，如果这个节点是FALSE，则这个球把它变成TRUE，然后从左子树走，继续它的旅程。如果节点是TRUE，则球也会改变它为FALSE，而接下来从右子树走。满二叉树的标记方法如下图。</p><p><span style=""></span><br></p><p>因为所有的节点最初为FALSE，所以第一个球将会访问节点1，节点2和节点4，转变节点的布尔值后在在节点8停止。第二个球将会访问节点1、3、6,在节点12停止。明显地，第三个球在它停止之前，会访问节点1、2、5，在节点10停止。<br>　　现在你的任务是，给定FBT的深度D，和I，表示第I个小球下落，你可以假定I不超过给定的FBT的叶子数，写一个程序求小球停止时的叶子序号。<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件仅一行包含两个用空格隔开的整数D和I。其中2&lt;=D&lt;=20，1&lt;=I&lt;=524288。<br><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对应输出第I个小球下落停止时的叶子序号。<br/><br/><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 2<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2&lt;=D&lt;=20，1&lt;=I&lt;=524288。<br><br></p>
</div>
</div>