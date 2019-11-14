<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">明明同学最近迷上了侦探漫画《柯南》并沉醉于推理游戏之中，于是他召集了一群同学玩推理游戏。游戏的内容是这样的，明明的同学们先商量好由其中的一个人充当罪犯（在明明不知情的情况下），明明的任务就是找出这个罪犯。接着，明明逐个询问每一个同学，被询问者可能会说：</p><p style=""> </p><p style=""> </p><p style="">证词中出现的其他话，都不列入逻辑推理的内容。</p><p style="">明明所知道的是，他的同学中有<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>N</span></span></span>个人始终说假话，其余的人始终说真。</p><p style="">现在，明明需要你帮助他从他同学的话中推断出谁是真正的凶手，请记住，<span style="text-decoration: underline;">凶手只有一个！</span></p>

<img src="/source/codevs/codevs-1089/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMDg5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMDg5LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入由若干行组成，第一行有三个整数，M（1&amp;le;M&amp;le;20）、N（1&amp;le;N&amp;le;M）和P（1&amp;le;P&amp;le;100）；<br>M是参加游戏的明明的同学数，N是其中始终说谎的人数，P是证言的总数。接下来M行，<br>每行是明明的一个同学的名字（英文字母组成，没有主格，全部大写）。<br>往后有P行，每行开始是某个同学的名宇，紧跟着一个冒号和一个空格，后面是一句证词，符合前表中所列格式。证词每行不会超过250个字符。<br>输入中不会出现连续的两个空格，而且每行开头和结尾也没有空格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;">如果你的程序能确定谁是罪犯，则输出他的名字；如果程序判断出不止一个人可能是</p><p style="margin-bottom: 0cm;">罪犯，则输出 <span style="font-family: DejaVu Serif Condensed,serif;">Cannot Determine</span>；如果程序判断出没有人可能成为罪犯，则输出 <span style="font-family: DejaVu Serif Condensed,serif;">Impossible</span>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3 1 5</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">MIKE</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">CHARLES</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">KATE</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">MIKE: I am guilty.</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">MIKE: Today is Sunday.</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">CHARLES: MIKE is guilty.</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">KATE: I am guilty.</span></p><p style=""><span style="font-family: DejaVu Serif Condensed,serif;">KATE: How are you??</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: DejaVu Serif Condensed,serif;">MIKE</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>NULL</p>
</div>
</div>