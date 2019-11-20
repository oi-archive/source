<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""></span></p><p><span style="">某城市冬季举办环城Mkm马拉松接力赛，每个代表队有N人参加比赛，比赛要求每个队的每名参赛选手只能跑一次，一次至少跑1km、最多只能跑Kkm，而且每个选手所跑的公里数必须为整数，即接力的地方在整公里处。</span></p><p><span style="">    </span><span style="">刘老师作为学校代表队的教练，精心选择了N名长跑能手，进行了训练和测试，得到了这N名选手尽力连续跑1km、2km、…、Kkm的所用时间。现在他要进行一个合理的安排，让每个选手跑合适的公里数，使学校代表队跑完Mkm所用的时间最短。根据队员的情况，这个最短的时间是惟一的，但安排方案可能并不惟一。</span></p><p style=""><span style="">根据测试情况及一般运动员的情况得知，连续跑1km要比连续跑2km速度快、连续跑2km又要比连续跑3km速度快……也就是说连续跑的路程越长，速度越慢，当然也有特殊的，就是速度不会变慢，但是绝不可能变快。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""></span></p><p><span style="">    </span><span style="">第一行，三个数M（10&lt;=M&lt;=100），N(5&lt;=N&lt;=100)，K(5&lt;=K&lt;=100)如题目描述。</span></p><p style=""><span style="">接下来N行，每行K个数，分别表示某一个运动员尽力连续跑1km、2km、…、Kkm所用时间。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="MsoNormal"><span style="mso-bidi-font-size:10.5pt;font-family:宋体"><span style="font-size:14px;font-family:宋体">两行，第一行是最短的时间，第二行是N个数据，分别是1到N号队员各自连续跑的公里数，以一个空格隔开。输入输出举例：</span><span lang="EN-US"><o:p></o:p></span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">25 5 10</span><br></p><p><span style=""><span style="">333 700 1200 1710
2240 2613 3245 3956 4778 5899</span><br></span></p><p><span style=""><span style=""><span style="">300 610 960 1370 1800
2712 3834 4834 5998 7682</span><br></span></span></p><p><span style=""><span style=""><span style=""><span style="">298 612 990 1560 2109
2896 3790 4747 5996 7654</span><br></span></span></span></p><p><span style=""><span style=""><span style=""><span style=""><span style="">289 577 890 1381 1976
2734 3876 5678 6890 9876</span><br></span></span></span></span></p><p><span style=""><span style=""><span style=""><span style=""><span style=""><span style="">312 633 995 1467 1845
2634 3636 4812 5999 8123</span><br></span></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">9748</span><br></p><p><span style=""><span style="">6 5 5 4 5</span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如上题目所示</p><p>其中可以出现运动员没有跑的情况</p>
</div>
</div>