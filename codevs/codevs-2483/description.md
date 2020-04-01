<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>通往藏宝库的通道打开了，走下一段长长的楼梯，钻过一条矮矮的地道，你和小可可终于来到了藏宝库的门前。随之而来的就是最后一个挑战，只要能打开宝库的门，里面的宝藏就是你们的了。</p>
<p>宝库的门依然是通过机关打开，这个门很奇怪，是一个正方形，被划分成许多大小一致的正方形的小方格，这些方格不是红色就是白色，猛看上去这些方格组成了许多红十字状的标志。根据藏宝图记载，只要找到门上最大的红十字，按下它中心的方格，宝库的门就能打开了。</p>
<p>红十字标志也是一个正方形，边长为(2k+1)*(2k+1)，其中k为非负整数。它的四条边与门的边平行，而且恰由门上的(2k+1)*(2k+1)个小方格组成。这里，红十字标志是以白色为底色，红色为十字的颜色。假设用1表示红色，用0表示白色。对应到计算机处理的数据中，就是除了正中列与正中行全为1外，其余方格均为0。以下是几种不同大小的标志：</p>
<p>1*1:</p>
<p>1</p>
<p>3*3</p>
<p>010</p>
<p>111</p>
<p>010</p>
<p>5*5</p>
<p>00100</p>
<p>00100</p>
<p>11111</p>
<p>00100</p>
<p>00100</p>
<p> </p>
<p>小可可被这个机关难到了，现在只有靠你了，请你帮助他在这个门上找到一个最大的红十字标志，输出它的边长即可。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中第一行有一个整数n（1&lt;=n&lt;=2,000），表示门由n个方格组成。</p>
<p>以下n行，每行n个字符，每个字符都是0或1。数据中不会出现全为0的情况。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个数，即最大的红十字标志的边长。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>00011</p>
<p>01011</p>
<p>11100</p>
<p>01001</p>
<p>00010</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>