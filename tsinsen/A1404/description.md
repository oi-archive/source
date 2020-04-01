<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　八岁的小正太Stas和小萝莉Masha发明了一个游戏。游戏道具是a个两两不同的箱子和b个两两不同的皮球，每一回合Stas或Masha都可以新增一个完全不同的箱子或皮球。 如果Stas或Masha操作了以后，把b个皮球放进a个箱子的方案数不小于n，那么这个人就会输掉。所有箱子和皮球都是不同的，可以有空的箱子。<br/>
　　如果第一回合由Stas先操作，且Stas和Masha都按照最优策略进行游戏，那么是否会打平？如果不打平，谁会输？？</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含三个正整数a，b，n。</div>
# 输出格式

<div class="pdcont">　　如果Stas会输，输出&#39;Stas&#39;（不要输出引号）；如果Masha会输，输出&#39;Masha&#39;；如果游戏会打平（也就是不结束），输出&#39;Missing&#39;。</div>
# 样例输入

<div class="pddata">2 2 10</div>
# 样例输出

<div class="pddata">Masha</div>
# 样例输入

<div class="pddata">5 5 16808</div>
# 样例输出

<div class="pddata">Masha</div>
# 样例输入

<div class="pddata">3 1 4</div>
# 样例输出

<div class="pddata">Stas</div>
# 样例输入

<div class="pddata">1 4 10</div>
# 样例输出

<div class="pddata">Missing</div>
# 数据规模和约定

<div class="pdcont">　　1≤a≤10,000, 1≤b≤30, 2≤n≤1,000,000,000, a^b&lt;n<br/>
　　对于10%的数据，n不超过10；<br/>
　　对于30%的数据，n不超过10000。</div>

</div>