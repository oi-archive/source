<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　在如今的信息社会中，时间-<span style="">就是生命，对于记者们来说，如何以最快的速度传递消息就显得十分重要了，而为了尽快记录消息内容，速记也是必不可少的。速记就是用一些简单且特殊的符号表示一定的含义，具体如何对应依个人习惯而定，没有一种固定的表示方法。 </span>　　<br>　　Tom<span style="">是一名报社的新闻记者，常常马不停蹄的跟着新闻跑，有时只能随手记下采访的内容，让人送回报社，而自己又奔赴下一个现场。不过</span><span style="font-family: 'Times New Roman';">Tom</span><span style="">是一个糊涂的记者，有时忙中出错，把用自己的速记符号写的内容直接传回报社。因为一时联系不上</span><span style="font-family: 'Times New Roman';">Tom</span><span style="">，但这条新闻又十分重要，要赶着在当天的报纸排版前整理出来，于是</span><span style="font-family: 'Times New Roman';">Tom</span><span style="">的同事们只好来猜测</span><span style="font-family: 'Times New Roman';">Tom</span><span style="">的速记符号的意思。幸运的是</span><span style="font-family: 'Times New Roman';">Tom</span><span style="">的同事们与他共事的时间也不短了，对于</span><span style="font-family: 'Times New Roman';">Tom</span><span style="">的一些用词情况有一定的了解，经过讨论，他们列出了一张可能性表来表示每一个速记符号可能与哪些单词相对应，并列出了对应的可能性有多大。 </span>　　<br>　　你的任务是：根据Tom<span style="">的同事们提供的可能性表，找出一种可能性最大的速记符号与单词的对应方法（可能性应该相乘来计算）。 </span>　　<br>　　注意：每一个速记符号有且只有一个单词与其对应，每一个单词有不超过一个速记符号与其对应（可能没有速记符号与之对应）。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　文件的第一行有两个整数，分别为速记符号的个数n(1&lt;=n&lt;=100)<span style="">和单词总</span><span style="font-family: 'Times New Roman';">m (1&lt;=m&lt;=500)</span><span style="">。 　　</span><br>　　从第1<span style="">行到第</span><span style="font-family: 'Times New Roman';">n+1</span><span style="">行为每个速记符号可能对应的单词及其可能性。 </span><br>　　第i+1(1&lt;=i&lt;=n)<span style="">行的第一个数</span><span style="font-family: 'Times New Roman';">Ci</span><span style="">表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个速记符号可能与</span><span style="font-family: 'Times New Roman';">Ci</span><span style="">个单词相对应，后面有</span><span style="font-family: 'Times New Roman';">Ci</span><span style="">个数对</span><span style="font-family: 'Times New Roman';">(Nik</span><span style="">，</span><span style="font-family: 'Times New Roman';">Rik)(1&lt;=k&lt;=Ci)</span><span style="">，表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个速记符号与第</span><span style="font-family: 'Times New Roman';">Nik</span><span style="">个单词相对应的可能性为</span><span style="font-family: 'Times New Roman';">Rik</span><span style="">（</span><span style="font-family: 'Times New Roman';">Rik</span><span style="">为大于</span><span style="font-family: 'Times New Roman';">0</span><span style="">小于</span><span style="font-family: 'Times New Roman';">1</span><span style="">的实数）。 </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">　　输出文件仅包含一行，若有解则输出一个实数即最大的可能性，保留四位有效数字（四舍五入），若无解则输出"NO&nbsp;ANSWER"<span style="font-family: 宋体;">。&nbsp;</span><br />　　（当可能性大于1e-12<span style="font-family: 宋体;">时才被视为有解）&nbsp;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>2 1 0.4 3 0.2</p>
<p>1 3 0.8</p>
<p>3 1 0.1 2 0.9 3 0.2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.2880</p>

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