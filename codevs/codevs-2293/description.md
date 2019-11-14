<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>【Shadow 1】第三题</div>
<div>“南山经之首曰鹊山。其首曰招摇之山，临于西海之上。多桂多金玉。有草焉，其状如韭而青华，其名曰祝馀，食之不饥……<br>又东三百里曰堂庭之山。金棪木，多白猿，多水玉，多黄金。</div>
<div>又东三百八十里曰猨翼之山。其中多怪兽，水多怪鱼。多白玉，多蝮虫，多怪蛇，多怪木，不可以上……”</div>
<div>《山海经》是以山为纲，以海为线记载古代的河流、植物、动物以及矿产等情况，而且每一条记录路线都不会有重复的山出现。某天，wyl8899想游览《山海经》中的路线，为了简化问题，wyl8899已经把每座山用一个整数表示他对该山的喜恶程度。wyl8899想知道第a座山到第b座山的中间某短路[i,j]能使他感到最满意，即[i,j]这条路上所有山的喜恶程度之和是所有[c,d](a≤c≤d≤b)最大。由于wyl8899还要去WJMZBMR家里【哗……】，所以他把这个问题扔给了Shadow：“你做不出来就……”</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>第1行，2个整数N,M，N表示一共有N座山，M表示wyl8899想问的次数（Shadow：问那么多干嘛……）；</div>
<div>第2行，N个整数，代表N座山的喜恶程度，绝对值均小于10000；</div>
<div>第3-(M+2)行，每行有2个数a,b，表示询问从第a座山到第b座山的最大值。</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一共有M行，每行有3个数i,j,s，表示从第i座山到第j座山总的喜恶程度为s。显然，对于每个询问，有a&le;i&le;j&le;b，如果有多组解，则输出i最少的，如果i也相等，则输出j最少的解。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>5 3</div>
<div>5 -6 3 -1 4</div>
<div>1 3</div>
<div>1 5</div>
<div>5 5</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>1 1 5</div>
<div>3 5 6</div>
<div>5 5 4</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>对于100%的数据，2≤N≤200000，1≤M≤100000,1≤a≤b≤N。</span></p>
</div>
</div>