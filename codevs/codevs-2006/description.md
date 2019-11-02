<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　某RPG游戏中，最后一战是主角单挑Boss，将其简化后如下：</span><br><span>　　主角的气血值上限为HP，魔法值上限为MP，愤怒值上限为SP；Boss仅有气血值，其上限为M。</span><br><span>　　现在共有N回合，每回合都是主角先行动，主角可做如下选择之一：</span><br><span>　　1. 普通攻击：减少对方X的气血值，并增加自身D</span><sub>SP</sub><span>的愤怒值。（不超过上限）</span><br><span>　　2. 法术攻击：共有N</span><sub>1</sub><span>种法术，第i种消耗B</span><sub>i</sub><span>的魔法值，减少对方Y</span><sub>i</sub><span>的气血值。（使用时要保证MP不小于B</span><sub>i</sub><span>）</span><br><span>　　3. 特技攻击：共有N</span><sub>2</sub><span>种特技，第i种消耗C</span><sub>i</sub><span>的愤怒值，减少对方Z</span><sub>i</sub><span>的气血值。（使用时要保证SP不小于C</span><sub>i</sub><span>）</span><br><span>　　4. 使用HP药水：增加自身D</span><sub>HP</sub><span>的气血值。（不超过上限）</span><br><span>　　5. 使用MP药水：增加自身D</span><sub>MP</sub><span>的魔法值。（不超过上限）</span><br><span>　　之后Boss会攻击主角，在第i回合减少主角A</span><sub>i</sub><span>的气血值。</span><br><span>　　刚开始时气血值，魔法值，愤怒值都是满的。当气血值小于等于0时死亡。</span><br><span>　　如果主角能在这N个回合内杀死Boss，那么先输出“Yes”，之后在同一行输出最早能在第几回合杀死Boss。（用一个空格隔开）</span><br><span>　　如果主角一定会被Boss杀死，那么输出“No”。</span><br><span>　　其它情况，输出“Tie”。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　输入的第一行包含一个整数T，为测试数据组数。</span><br><span>　　接下来T部分，每部分按如下规则输入：</span><br><span>　　第一行九个整数N, M, HP, MP, SP, D</span><sub>HP</sub><span>, D</span><sub>MP</sub><span>, D</span><sub>SP</sub><span>, X。</span><br><span>　　第二行N个整数A</span><sub>i</sub><span>。</span><br><span>　　第三行第一个整数N</span><sub>1</sub><span>，接下来包含N</span><sub>1</sub><span>对整数B</span><sub>i</sub><span>, Y</span><sub>i</sub><span>。</span><br><span>　　第四行第一个整数N</span><sub>2</sub><span>，接下来包含N</span><sub>2</sub><span>对整数C</span><sub>i</sub><span>, Z</span><sub>i</sub><span>。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　输出共包含T行，每行依次对应输出一个答案。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>2</span><br><span>5 100 100 100 100 50 50 50 20</span><br><span>50 50 30 30 30</span><br><span>1 100 40</span><br><span>1 100 40</span><br><span>5 100 100 100 100 50 50 50 10</span><br><span>50 50 30 30 30</span><br><span>1 100 40</span><br><span>1 100 40</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>Yes 4</span><br><span>Tie</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于第一个样例，主角的策略是：第一回合法术攻击，第二回合使用HP药水，第三回合特技攻击，第四回合普通攻击。</span></p>
<p><span><br></span></p>
<p><span><span>　　对于10%的数据：N ≤ 10，N</span><sub>1 </sub><span>= N</span><sub>2 </sub><span>= 0。</span><br><span>　　对于30%的数据：N ≤ 10，N</span><sub>1</sub><span> = N</span><sub>2</sub><span> = 1。</span><br><span>　　对于60%的数据：N ≤ 100，M ≤ 10000，HP,MP,SP ≤ 70。</span><br><span>　　对于100%的数据：1 ≤ N ≤ 1000，1 ≤ M ≤ 1000000，1 ≤ HP,MP,SP ≤ 1000，N</span><sub>1</sub><span>,N</span><sub>2</sub><span> ≤ 10，D</span><sub>HP</sub><span>,A</span><sub>i</sub><span> ≤ HP，D</span><sub>MP</sub><span>,B</span><sub>i</sub><span> ≤ MP，D</span><sub>SP</sub><span>,C</span><sub>i</sub><span> ≤ SP，X,Y</span><sub>i</sub><span>,Z</span><sub>i</sub><span> ≤ 10000，1 ≤ T ≤ 10。</span></span></p>
<p><span><span><br></span></span></p>
<p><span><span>来源：<span>中国国家队清华集训 2012-2013 第三天</span></span></span></p>
</div>
</div>