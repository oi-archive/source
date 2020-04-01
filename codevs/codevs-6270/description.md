<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">    本题由水果狐工作室原创。</span></p><p><span style="">    黄睿夏是一个数独爱好者，一天，</span><span style=""><span style="">黄睿夏</span></span><span style="">遇到了一道很难的数独题，</span><span style=""><span style=""><span style="">黄睿夏</span></span></span><span style="">想了很久，但还是没有想出来，于是，他决定向你这个高手求助。</span></p><p><span style="">    但是，你也想不出来这个数独该怎么做，于是，你打算编一条程序来帮助<span style=""><span style=""><span style="">黄睿夏</span></span><span style=""></span></span>克服这个难题，现在已经知道这是一个<strong>9*9</strong>的数独。</span></p><p><span style="">    <strong>数独的规则</strong>是这样的：</span></p><p><span style="">    1.<span style="font-family: 'Microsoft YaHei', SimSun, 'Arial sans-serif';">数独的元素主要包括行、列和宫。这三者划分出数独有三种不同形态的区域，而数独规则就是要求在这些区域内出现的数字都为1~9。</span></span></p><p><span style="">    2.<span style="font-family: 'Microsoft Yahei', arial, sans-serif;">满足每一行、每一列、每一个粗线宫内的数字均含1~9，不能够重复。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">    输入一个9*9的地图，输入0表示这个格子里的数还没有填上去，需要你来填上去。如果输入一个大于0的数的话，就表明这个数已经被填上去了，无需再填。</span></p><p><span style="">    输入时，每行输入9个数字，共9行，每两个数字之间用空格隔开。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">&nbsp; &nbsp; &nbsp; &nbsp;以下是几种的输出情况：</span></p><p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">&nbsp; &nbsp; &nbsp; &nbsp;1.只有一种解：</span></p><p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">&nbsp; &nbsp; &nbsp; &nbsp;输出<strong>一共9行，每行有9个数字</strong>，每两个数字之间用空格隔开，注意，每行的最后一个数字的后面<strong>没有空格</strong>。</span></p><p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;"></span></p><p style="white-space: normal;"><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">&nbsp; &nbsp; &nbsp; &nbsp;2.没有解：</span></p><p style="white-space: normal;"><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">&nbsp; &nbsp; &nbsp; &nbsp;输出一共1行，输出“<strong>No answer.</strong>“（引号不输出哦）。</span></p><p style="white-space: normal;"><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">&nbsp; &nbsp; &nbsp; &nbsp;3.有多种解：</span><br/></p><p style="white-space: normal;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;<span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">输出一共1行，输出“<strong>Not unique.</strong>“（引号不输出哦）。</span></p><p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;"><br/></span><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">9 3 4 7 0 2 1 5 8<br></span></p><p><span style="">7 0 8 1 3 5 4 9 6</span></p><p><span style="">1 6 0 9 8 4 3 2 7</span></p><p><span style="">3 4 7 0 2 1 9 8 5</span></p><p><span style="">0 8 9 3 5 7 6 4 1</span></p><p><span style="">6 5 1 4 9 8 2 7 0</span></p><p><span style="">8 1 6 2 7 9 5 3 0</span></p><p><span style="">4 7 2 5 1 3 8 6 9</span></p><p><span style="">5 9 3 8 4 6 7 1 2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">9 3 4 7 6 2 1 5 8<br></span></p><p style=""><span style="">7 2 8 1 3 5 4 9 6</span></p><p style=""><span style="">1 6 5 9 8 4 3 2 7</span></p><p style=""><span style="">3 4 7 6 2 1 9 8 5</span></p><p style=""><span style="">2 8 9 3 5 7 6 4 1</span></p><p style=""><span style="">6 5 1 4 9 8 2 7 3</span></p><p style=""><span style="">8 1 6 2 7 9 5 3 4</span></p><p style=""><span style="">4 7 2 5 1 3 8 6 9</span></p><p style=""><span style="">5 9 3 8 4 6 7 1 2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">样例解释</span></strong></p><p><span style=""></span></p><p style=""><span style="">因为输入是：</span><br></p><p><span style=""></span></p><p style=""><span style="">9 3 4 7 0 2 1 5 8<br></span></p><p style=""><span style="">7 0 8 1 3 5 4 9 6</span></p><p style=""><span style="">1 6 0 9 8 4 3 2 7</span></p><p style=""><span style="">3 4 7 0 2 1 9 8 5</span></p><p style=""><span style="">0 8 9 3 5 7 6 4 1</span></p><p style=""><span style="">6 5 1 4 9 8 2 7 0</span></p><p style=""><span style="">8 1 6 2 7 9 5 3 0</span></p><p style=""><span style="">4 7 2 5 1 3 8 6 9</span></p><p style=""><span style="">5 9 3 8 4 6 7 1 2</span></p><p><span style=""><br></span></p><p><span style="">你可以发现：在这张图里面有7个0（即有7个数字还没有填上去），（以下方法非正解）通过观察发现：第一行里面有1、2、3、4、5、7、8、9，只是少了一个6，所以将6改为0，以此类推。</span></p><p><strong><span style="">数据范围</span></strong></p><p><span style="">数据保证要填的空不会超过</span><span style="">20</span><span style="">个。</span><br></p><p><span style=""><span style="">对于%30的数据，要填的空&lt;=1个；</span></span></p><p><span style=""><span style=""><span style="">对于%50的数据，要填的空&lt;=7个</span><span style="">；</span></span></span></p><p><span style=""><span style=""><span style=""><span style="">对于%70的数据，要填的空&lt;=16个</span><span style="">；</span></span></span></span></p><p><span style=""><span style=""><span style=""><span style=""><span style="">对于%90的数据，要填的空&lt;=18个</span><span style="">；</span></span></span></span></span></p><p><span style="">对于%100的数据，要填的空&lt;=20个；</span></p><p><strong><span style="">提示</span></strong></p><p><span style="">1.此题有<strong>坑点</strong>。</span><br></p><p><span style="">记住，在做题的时候要把<strong>每一种情况</strong>都<strong>考虑</strong>一遍哦！</span></p>
</div>
</div>