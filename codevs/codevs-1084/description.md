<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">国际乒联现在主席沙拉拉自从上任以来就立志于推行一系列改革，以推动乒乓球运动在全球的普及。其中<span style="font-family: DejaVu Serif Condensed,serif;">11</span>分制改革引起了很大的争议，有一部分球员因为无法适应新规则只能选择退役。华华就是其中一位，他退役之后走上了乒乓球研究工作，意图弄明白<span style="font-family: DejaVu Serif Condensed,serif;">11</span>分制和<span style="font-family: DejaVu Serif Condensed,serif;">21</span>分制对选手的不同影响。在开展他的研究之前，他首先需要对他多年比赛的统计数据进行一些分析，所以需要你的帮忙。</p>
<p style=""> </p>
<p style="">【问题描述】华华通过以下方式进行分析，首先将比赛每个球的胜负列成一张表，然后分别计算在<span style="font-family: DejaVu Serif Condensed,serif;">11</span>分制和<span style="font-family: DejaVu Serif Condensed,serif;">21</span>分制下，双方的比赛结果（截至记录末尾）。</p>
<p style="">比如现在有这么一份记录，（其中<span style="font-family: DejaVu Serif Condensed,serif;">W</span>表示华华获得一分，<span style="font-family: DejaVu Serif Condensed,serif;">L</span>表示华华对手获得一分）：</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">WWWWWWWWWWWWWWWWWWWWWWLW</span></p>
<p style="">在<span style="font-family: DejaVu Serif Condensed,serif;">11</span>分制下，此时比赛的结果是华华第一局<span style="font-family: DejaVu Serif Condensed,serif;">11</span>比<span style="font-family: DejaVu Serif Condensed,serif;">0</span>获胜，第二局<span style="font-family: DejaVu Serif Condensed,serif;">11</span>比<span style="font-family: DejaVu Serif Condensed,serif;">0</span>获胜，正在进行第三局，当前比分<span style="font-family: DejaVu Serif Condensed,serif;">1</span>比<span style="font-family: DejaVu Serif Condensed,serif;">1</span>。而在<span style="font-family: DejaVu Serif Condensed,serif;">21</span>分制下，此时比赛结果是华华第一局<span style="font-family: DejaVu Serif Condensed,serif;">21</span>比<span style="font-family: DejaVu Serif Condensed,serif;">0</span>获胜，正在进行第二局，比分<span style="font-family: DejaVu Serif Condensed,serif;">2</span>比<span style="font-family: DejaVu Serif Condensed,serif;">1</span>。如果一局比赛刚开始，则此时比分为<span style="font-family: DejaVu Serif Condensed,serif;">0</span>比<span style="font-family: DejaVu Serif Condensed,serif;">0</span>。</p>
<p style="">你的程序就是要对于一系列比赛信息的输入（<span style="font-family: DejaVu Serif Condensed,serif;">WL</span>形式），输出正确的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">每个输入文件包含若干行字符串（每行至多<span style="font-family: DejaVu Serif Condensed,serif;">20</span>个字母），字符串有大写的<span style="font-family: DejaVu Serif Condensed,serif;">W</span>、<span style="font-family: DejaVu Serif Condensed,serif;">L</span>和<span style="font-family: DejaVu Serif Condensed,serif;">E</span>组成。其中<span style="font-family: DejaVu Serif Condensed,serif;">E</span>表示比赛信息结束，程序应该忽略<span style="font-family: DejaVu Serif Condensed,serif;">E</span>之后的所有内容。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 0.74cm; margin-bottom: 0cm;">输出由两部分组成，每部分有若干行，每一行对应一局比赛的比分（按比赛信息输入顺序）。其中第一部分是<span style="font-family: DejaVu Serif Condensed,serif;">11</span>分制下的结果，第二部分是<span style="font-family: DejaVu Serif Condensed,serif;">21</span>分制下的结果，两部分之间由一个空行分隔。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">WWWWWWWWWWWWWWWWWWWW</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">WWLWE</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">11:0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">11:0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1:1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">21:0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2:1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>每行最多20个字符</p>
<p>总共的字符数不超过100000</p>
</div>
</div>