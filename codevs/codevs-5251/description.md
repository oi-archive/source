<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""></span></p><p style=""><span style="">wyw有一个数字n，他要用这个数字写出一个数字金字塔。</span></p><p style=""><span style="">wyw用随机数生成器生成了一个小于n且大于1的正整数k。</span></p><p style=""><span style="">wyw找来一张白纸，他在白纸的最低端写下了这个数字n。</span></p><p style=""><span style="">wyw在n的上面紧挨着写下了一个正整数a</span><sub><span style="">1</span></sub><span style=""><span style="">，</span>a</span><sub><span style="">1</span></sub><span style=""><span style="">满足不大于</span>n/k，</span></p><p style=""><span style="">wyw又在a</span><sub><span style="">1</span></sub><span style=""><span style="">上面写下了一个正整数</span>a</span><sub><span style="">2</span></sub><span style=""><span style="">，满足</span>a</span><sub><span style="">2</span></sub><span style=""><span style="">不大于</span>a</span><sub><span style="">1</span></sub><span style="">/k，</span></p><p style=""><span style=""><span style="">时间过了</span>t...</span></p><p style=""><span style="">wyw在a</span><sub><span style="">h-1</span></sub><span style=""><span style="">的上面写下了一个正整数</span>a</span><sub><span style="">h</span></sub><span style=""><span style="">，满足</span>a</span><sub><span style="">h</span></sub><span style=""><span style="">不大于</span>a</span><sub><span style="">h-1</span></sub><span style="">/k</span></p><p style=""><span style="">wyw已经无法在a</span><sub><span style="">h</span></sub><span style=""><span style="">的上方写出不大于</span>a</span><sub><span style="">h</span></sub><span style="">/k的数字了</span></p><p style=""><span style=""><span style="">这时，</span>wyw就已经写好了一个高度为h的数字金字塔</span></p><p style=""><span style="">wyw可以按照这个规则写出好多符合条件的数字金字塔。</span></p><p style=""><span style=""><span style="">试问：</span>wyw一共能够写出多少种数字金字塔？wyw能写出的所有的数字金字塔中最高的金字塔的高度是多少？</span></p><p><span style=""><span style="">注意：由于答案可能较大，所以对每一组数据请输出答案对</span>p取模后的值</span></p><p style=""><span style=""></span><br></p><p style=""><span style=""><img src="/source/codevs/codevs-5251/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01MjUxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE2MDgxNDE5NDUxNl80ODgucG5n.png" title=""></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入数据的第一行包含两个正整数T、p，表示有T组测试数据，p的意义如题目所述</span></p><p><span style="">    后面跟着T组数据，每组数据仅一行，包含了一个正整数n和k，意义如题目所述</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:15px;font-family:黑体">&nbsp;&nbsp;&nbsp;&nbsp;<span style="font-size: 15px; font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">输出数据一共n行，每行两个整数，表示答案对p取模后的值</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">2 2</span></p><p style=""><span style="">6 2</span></p><p style=""><span style="">20 3</span></p><p><span style="">样例说明：以20 3这组数据为例，wyw能写出的所有金字塔如下</span></p><p><img src="/source/codevs/codevs-5251/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01MjUxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE2MDgyNjEyNTgzN183MzcucG5n.png" title=""></p><p style=""><span style="">因此答案是7 3，对2取模后输出1 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">1 1</span></p><p style=""><span style="">1 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><img src="/source/codevs/codevs-5251/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01MjUxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE2MDgxNDE0NDYzMF82ODcucG5n.png" title=""></p>
</div>
</div>