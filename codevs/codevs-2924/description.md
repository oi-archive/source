<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>“芬兰数学家因卡拉，花费3个月时间设计出了世界上迄今难度最大的数独游戏，而且它只有一个答案。因卡拉说只有思考能力最快、头脑最聪明的人才能破解这个游戏。”这是英国《每日邮报》2012年6月30日的一篇报道。这个号称“世界最难数独”的“超级游戏”，却被扬州一位69岁的农民花三天时间解了出来。</span></p>
<p><span>看到这个新闻后，我激动不已，证明我们OI的实力的机会来了，我们虽然不是思考能力最快、头脑最聪明的人，但是我们可以保证在1s之内解题。</span></p>
<p><span>好了废话不多说了……</span></p>
<p>数独是一种填数字游戏，英文名叫Sudoku，起源于瑞士，上世纪70年代由美国一家数学逻辑游戏杂志首先发表，名为Number Place，后在日本流行，1984年将Sudoku命名为数独，即“独立的数字”的省略，解释为每个方格都填上一个个位数。2004年，曾任中国香港高等法院法官的高乐德(Wayne Gould)把这款游戏带到英国，成为英国流行的数学智力拼图游戏。</p>
<p>　　<span style="text-decoration: underline;"><strong>玩家需要根据9×9盘面上的已知数字，推理出所有剩余位置（数据表示为数字0）的数字，并满足每一行、每一列、每一个粗线宫内的数字均含1-9，不重复。</strong></span></p>
<p>现在给你一个数独，请你解答出来。每个数独保证有解且只有一个。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>9行9列。</p>
<p>每个数字用空格隔开。0代表要填的数</p>
<p><strong>行末没有空格，末尾没有回车。</strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出答案。</p>
<p>排成9行9列。</p>
<p><strong>行末没有空格，结尾可以有回车。</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 0 0 0 1 0 8 9 0<br>0 0 7 0 0 0 0 0 0<br>0 0 0 9 0 0 0 0 7<br>0 6 0 0 0 1 3 0 0<br>0 9 0 7 3 4 0 8 0<br>0 0 3 6 0 0 0 5 0<br>6 0 0 0 0 2 0 0 0<br>0 0 0 0 0 0 1 0 0<br>0 5 9 0 8 0 0 0 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 4 5 3 1 7 8 9 6<br>9 1 7 2 6 8 5 3 4<br>3 8 6 9 4 5 2 1 7<br>4 6 2 8 5 1 3 7 9<br>5 9 1 7 3 4 6 8 2<br>8 7 3 6 2 9 4 5 1<br>6 3 8 1 7 2 9 4 5<br>7 2 4 5 9 3 1 6 8<br>1 5 9 4 8 6 7 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>保证有解，每个数独都由&lt;a href="http://oubk.com/"&gt;http://oubk.com&lt;/a&gt;数独网提供。</p>
<p>其中数据hard1.in为芬兰数学家提供。</p>
</div>
</div>