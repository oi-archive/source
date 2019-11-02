<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<table cellpadding="0" cellspacing="0" style="" width="602"><tbody><tr><td style="" valign="top"><p><span style="">在猴村有一条笔直的山路，这条山路很窄，宽度忽略不计。有   </span><span style="">n </span><span style="">只猴子正站在山路上</span></p><p><span style="">静静地观望今天来参加比赛的各位同学。用一个正整数   </span><span style="">X</span><span style="">i </span><span style="">表示第   </span><span style="">i </span><span style="">只猴子所站位置，任意</span></p><p><span style="">两只猴子的所站位置互不相同。在这条山路的   </span><span style="">m </span><span style="">个位置上种着一些高大的树木，正整数   </span><span style="">Y</span><span style="">j</span></p><p><span style="">表示第 </span><span style="">j </span><span style="">棵树木所在的位置，任意两棵树的位置互不相同。</span></p><p><span style="">正当猴子们聚精会神的欣赏各位高超的编程技能时，一只老虎大摇大摆的走了过来。</span></p><p><span style="">猴子们吓得直冒冷汗，第一反应就是找一棵大树爬上去，这样就能避免被老虎咬死或者吃掉</span></p><p><span style="">（不考虑老虎上树问题）。</span></p><p><span style="">在位置 </span><span style="">a </span><span style="">的猴子跑到在位置 </span><span style="">b </span><span style="">的大树上，需要消耗的能量为 </span><span style="">|a-b|</span><span style="">（即</span><span style=""> a-b   </span><span style="">的绝对值）。</span></p><p><span style="">为了尽可能有效利用这些大树避难，每棵大树上至少要有一只猴子。</span></p><p><span style="">请编程计算 </span><span style="">n </span><span style="">只猴子全部上树最少需要消耗多少能量？</span></p></td></tr></tbody></table><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<table cellpadding="0" cellspacing="0" width="496"><tbody><tr><td style="" valign="top"><p><span style="">输入共 </span><span style="">4 </span><span style="">行。</span></p><p><span style="">第 </span><span style="">1 </span><span style="">行一个整数 </span><span style="">n</span><span style="">，表示猴子的数量。</span></p><p><span style="">第 </span><span style="">2 </span><span style="">行 </span><span style="">n </span><span style="">个整数，第 </span><span style="">i </span><span style="">个整数 </span><span style="">X</span><span style="">i </span><span style="">表示第 </span><span style="">i </span><span style="">只猴子所在的位置。</span></p><p><span style="">第 </span><span style="">3 </span><span style="">行一个整数 </span><span style="">m</span><span style="">，表示大树的数量。</span></p><p><span style="">第 </span><span style="">4 </span><span style="">行 </span><span style="">m </span><span style="">个整数，第 </span><span style="">j </span><span style="">个整数 </span><span style="">Y</span><span style="">j </span><span style="">表示第 </span><span style="">j </span><span style="">棵大树所在的位置。</span></p></td></tr></tbody></table><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<table cellspacing="0" cellpadding="0" hspace="0" vspace="0" width="496"><tbody><tr class="firstRow"><td valign="top" style="padding-top:0;padding-right:0;padding-bottom:0;padding-left:0"><p><span style="font-size: 13px;font-family: 宋体">输出一行，一个整数，表示 </span><span style="font-size: 13px">n </span><span style="font-size: 13px;font-family: 宋体">只猴子全部上树最少需要消耗的能量。</span></p></td></tr></tbody></table><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1<br></p><table cellpadding="0" cellspacing="0" width="90"><tbody><tr><td style="" valign="top"><p><span style="font-family: 'Courier New';">3</span></p><p><span style="font-family: 'Courier New';">145</span></p><p><span style="font-family: 'Courier New';">2</span></p><p><span style="font-family: 'Courier New';">38</span></p></td></tr></tbody></table><p>样例2</p><table cellpadding="0" cellspacing="0" width="98"><tbody><tr><td style="" valign="top"><p><span style="font-family: 'Courier New';">3</span></p><p><span style="font-family: 'Courier New';">3 1 10</span></p><p><span style="font-family: 'Courier New';">2</span></p><p><span style="font-family: 'Courier New';">83</span></p></td></tr></tbody></table><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1</p><p>6</p><p>样例2</p><p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table cellpadding="0" cellspacing="0" style="" width="602"><tbody><tr><td style="" valign="top"><p><span style="">【样例 1 解释】</span></p><p><span style="">  </span><span style="">输入中共有 3 只猴子，所在的位置分别为   1，4，5。山路旁边有两棵大树，位置在   3 和</span></p><p><span style="">8</span><span style="">。第 1 只猴子爬上在位置 3 的大树，消耗的能量为|1-3|=2，第 2 只猴子也爬上在位置 3</span></p><p><span style="">的大树，消耗的能量为|4-3|=1。因为要保证每棵树上至少有一只猴子，所以第 3 只猴子爬</span></p><p><span style="">上在位置 8 的大树，消耗的能量为|5-8|=3。所以 </span><span style="">3 </span><span style="">只猴子全部上树最少需要消耗的能量为</span></p><p><span style="">6</span><span style="">。</span></p></td></tr></tbody></table><table cellpadding="0" cellspacing="0" width="394"><tbody><tr><td style="" valign="top"><p><span style="">【数据范围】</span></p><p><span style="">                  </span><span style="">30%</span><span style="">的数据 </span><span style="">1≤n≤500</span><span style="">，</span><span style="">1≤X</span><span style="">i </span><span style="">,Y</span><span style="">i</span><span style="">≤10   。</span></p><p><span style="">                       </span><span style="">100%</span><span style="">的数据 </span><span style="">1≤n≤5000</span><span style="">，</span><span style="">1≤m≤n</span><span style="">，</span><span style="">1≤X</span><span style="">i </span><span style="">,Y</span><span style="">i</span><span style="">≤10   。</span></p><p><span style="">提示：请关注本题内存限制大小。</span></p></td></tr></tbody></table><p><br></p>
</div>
</div>