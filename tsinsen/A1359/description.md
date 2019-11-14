<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　沿着一条道路有 <i>N</i> 个仓库,相邻两个仓库间距离为 1 公里。假设第 <i>i</i>个仓库存有 <i>X</i><i><sub>i</sub></i> 个单位的货物。现在希望将货物重新分配,使得最终每个仓库内的货物量 <i>X<sub>i</sub></i> 相等。<br/>
　　假设将 1 个单位的货物运送 1 公里的耗费为 1 个金币。请你计算出为了让各个仓库内的货物相等最少需要花费多少个金币。</div>
# 输入格式

<div class="pdcont">　　输入第一行有一个数,<i>N</i> (1 ≤ <i>N</i> ≤ 1000) ,表示仓库的个数。<br/>
　　第二行为用空格隔开的 <i>N</i> 个正整数,依次表示 <i>X</i><sub>1</sub> 到 <i>X</i><i><sub>N</sub></i> 。假定 <i>X</i><i><sub>i</sub></i> 不超过 1000的非负整数。所有 X<i><sub>i</sub></i> 的和一定为 <i>N</i> 的倍数。</div>
# 输出格式

<div class="pdcont">　　输出文件只有一行,一个整数,表示最少花费。</div>
# 样例输入

<div class="pddata">3<br/>
1 6 2</div>
# 样例输出

<div class="pddata">3<br/>
对样例的解释<br/>
先从 2 号仓库运送 2 个单位的货物给 1 号仓库,然后从 2 号仓库运送<br/>
1 个单位的货物给 3 号仓库,所以总费用为 2 × 1 + 1 × 1 = 3。</div>

</div>