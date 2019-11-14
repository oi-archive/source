<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">牛牛最近迷上了一种叫斗地主的扑克游戏。 斗地主是一种使用黑桃、红心、梅花、<br><span style="">方片的 <strong>A</strong> 到 <strong>K</strong> 加上大小王的共 54 张牌来进行的扑克牌游戏。在斗地主中， 牌的大小关<br><span style="">系根据</span></span></span><em><span style=""><strong><span style="">牌的数码</span></strong></span></em><span style="">表示如下： 3&lt;4&lt;5&lt;6&lt;7&lt;8&lt;9&lt;10&lt;J&lt;Q&lt;K&lt;A&lt;2&lt;小王&lt;大王， 而</span><span style=""><em><strong>花色并不<br>对牌的大小产生影响</strong></em></span><span style="">。</span><span style=""> 每一局游戏中，一副</span><span style=""><em><strong><span style="">手牌</span></strong></em></span><span style="">由 n 张牌组成。游戏者每次可以根据规<br><span style="">定的</span></span><span style=""><em><strong><span style="">牌型</span></strong></em></span><span style="">进行出牌， 首先打光自己的手牌一方取得游戏的胜利。<br><span style="">现在，牛牛只想知道，对于自己的若干组</span></span><strong><span style=""><em><span style="">手牌</span></em></span></strong><span style="">， 分别最少需要多少次出牌可以将它<br><span style="">们打光。 请你帮他解决这个问题。<br><span style="">需要注意的是， 本题中游戏者每次可以出手的</span></span></span><em><span style=""><strong><span style="">牌型</span></strong></span></em><span style="">与一般的斗地主相似而略有不同。<br><span style="">具体规则如下：</span><br style=""></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件名为 <span style="font-family: 'Courier New';">landlords.in<span style="">。<br><span style="">第一行包含<span style="">用空格隔开的 <span style="">2 个正整数<em><strong>T,n</strong></em><span style="">，表示手牌的组数以及每组手牌的张数。<br><span style="">接下来<em><strong>T</strong></em><span style="">组数据，每组数据</span></span></span></span></span></span></span></span></span><span style=""><em><strong>n</strong></em></span><span style="">行， 每行一个非负整数<em><strong>ai</strong></em>,<em><strong>bi</strong></em>,对<span style="font-family: 'Cambria Math';"><span style=""><span style="">表示一张牌， 其中<em><strong>ai</strong></em>表<span style="font-family: 'Cambria Math';"><span style=""><br><span style="">示牌的数码，<em>bi</em><span style="font-family: 'Cambria Math';"><span style="">表示牌的花色，中间<span style="">用空格隔开。 <span style="">特别的， 我们用<strong>1</strong><span style="font-family: 'Cambria Math';"> <span style="">来表示数码 <strong>A</strong>，<strong> 11</strong> 表<br><span style="">示数码<strong> J</strong>， <strong>12</strong> 表示数码 <strong>Q</strong>， <strong>13</strong> 表示数码 <strong>K</strong>；黑桃、红心、梅花、方片分别用 <strong>1-4</strong> 来表示； 小<br><span style="">王的表示方法为 <strong>0 1</strong>， 大王的表示方法为 <strong>0 2</strong>。</span></span></span></span></span><br style=""></span></span></span></span></span></span></span></span></span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体; font-size: 10pt;">输出文件名为 <span style="font-family: &#39;Courier New&#39;; font-size: 10pt;">landlords.out<span style="font-family: 宋体; font-size: 10pt;">。<br/><span style="font-size: 10pt;">共 T 行，每行一个整数，表示打光第<span style="font-family: &#39;Cambria Math&#39;; font-size: 10pt;">i组手牌的最少次数。</span><br style="orphans: 2; text-align: -webkit-auto; white-space: normal; widows: 2;"/></span></span></span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">输入样例1</span></p><p>1 8</p><p>7 4<br>8 4<br>9 1<br>10 4<br>11 1<br>5 1<br>1 4<br></p><p>1 1</p><p>—————</p><p><span style=""><span style="">输入样例2</span><span style=""></span></span></p><p><span style="font-family: Courier New;"><br></span>1 17<br>12 3<br>4 3<br>2 3<br>5 4<br>10 2<br>3 3<br>12 2<br>0 1<br>1 3<br>10 1<br>6 2<br>12 1<br>11 3</p><p>5 2<br>12 4<br>2 2<br>7 2<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">输出样例1</span></p><p><span style=""><span style="font-family: 'Courier New';">3</span></span></p><p><span style=""><span style="font-family: 'Courier New';"><br></span></span></p><p><span style=""><span style="font-family: 'Courier New';">—————</span></span></p><p><span style="">输出样例2</span></p><p><span style=""><span style="font-family: 'Courier New';"><span style="font-family: 'Courier New';">6</span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">测试点， 我们约定手牌组数 <span style="font-family: 'Cambria Math';"><span style="">与张数 <span style="font-family: 'Cambria Math';"><span style="">的规模如下：<br><span style="">测试点编号  T    n</span></span></span></span></span></span></p><p><span style=""><span style="font-family: 'Cambria Math';"><span style=""><span style="font-family: 'Cambria Math';"><span style=""><span style=""><span style="font-family: 'Cambria Math';"><span style=""> </span></span></span></span></span></span></span></span></p><p><span style=""><span style="font-family: 'Cambria Math';"><span style=""><span style="font-family: 'Cambria Math';"><span style=""><span style=""><span style="font-family: 'Cambria Math';"><span style=""><span style="font-family: 'Cambria Math';"><span style="">1 100 2 ｜11 100 14<br><span style="">2 100 2 ｜12 100 15<br><span style="">3 100 3 ｜13 10 16<br><span style="">4 100 3 ｜14 10 17<br><span style="">5 100 4 ｜15 10 18<br><span style="">6 100 4 ｜16 10 19<br><span style="">7 100 10 ｜17 10 20<br><span style="">8 100 11 ｜18 10 21<br><span style="">9 100 12 ｜19 10 22<br><span style="">10 100 13 ｜20 10 23</span></span></span></span></span></span></span></span></span></span></span><br style=""></span></span></span></span></span></span></span></span></p>
</div>
</div>