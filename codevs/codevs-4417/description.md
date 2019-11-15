<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">    众所周知，一条完整的产业链是由许多环节构成，只有完成了某个环节才能下一个环节，必须先完成的环节成为该环节的子环节。</span><span style="">M</span><span style="">国最大的企业的产业链十分有趣，除了第一个环节外，每个环节有且仅有一个子环节。现在</span><span style="">明明</span><span style="">当上了该公司的一名货车司机。</span><span style="">明明</span><span style="">拿到了</span><span style="">M</span><span style="">国的地图，</span><span style="">M</span><span style="">国共有</span><span style="">n</span><span style="">个城镇，</span><span style="">m</span><span style="">条双向道路。每一环节都在一个城镇</span><span style="">中进行，且同一个城镇最多进行一个环节。每一个环节都需要一定重量的原材，供应原材料的仓库也坐落在某几个互不相同的城镇。明明的任务是用货车将仓库中的材料依</span><span style="">次运往各个环节所在的城镇。</span><span style="">明明</span><span style="">在运输过程中可经过一个仓库多次但只能从每一个仓</span><span style="">库中装载一次原材料。货车载重量及仓库储量不限。运输途中空货车消耗的费用为路程，载重</span><span style="">货车消耗的费用为货车载重量乘以路程。</span><span style="">明明</span><span style="">想知道他是否能完成任务，如果能完成，那么所消耗的最小费用为多少？如果不能完成，那么最多完成多少环节？（</span><span style="">明明</span><span style="">可选择任意一个城镇作为出发点）。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">    输入文件第一行包含两个正整数</span><span style="">n</span><span style="">，</span><span style="">m</span><span style="">，</span><span style="">k</span><span style="">，</span><span style="">p</span><span style="">分别代表</span><span style="">M</span><span style="">国城镇数，道路数，产业链所包含的环节数及仓库数量。</span></p><p><span style="">    </span><span style="">接下来</span><span style="">m</span><span style="">行，每行三个数</span><span style="">x</span><span style="">，</span><span style="">y</span><span style="">，</span><span style="">z</span><span style="">，表示</span><span style="">x</span><span style="">城镇到</span><span style="">y</span><span style="">城镇有一条长度为</span><span style="">z</span><span style="">的双向道路。</span><span style=""></span></p><p><span style="">    </span><span style="">接下来</span><span style="">k</span><span style="">行，每行两个正整数</span><span style="">v</span><span style="">，</span><span style="">w</span><span style="">。代表第</span><span style="">v</span><span style="">个城镇有一个环节需要完成，该环节需要重量为</span><span style="">w</span><span style="">材料。输入顺序即为环节完成的先后顺序。</span></p><p><span style="">    </span><span style="">接下来</span><span style="">1</span><span style="">行，包含</span><span style="">P</span><span style="">个整数，分别代表仓库所在的城镇编号。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">&nbsp; &nbsp; 输出文件包含两行，第一行是一个数字</span><span style="FONT-SIZE: 16px">0</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">或</span><span style="FONT-SIZE: 16px">1</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">。</span><span style="FONT-SIZE: 16px">0</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">代表</span><span style="FONT-SIZE: 16px">明明</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">不能完成任务，</span><span style="FONT-SIZE: 16px">1</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">代表</span><span style="FONT-SIZE: 16px">明明</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">能完成任务。</span></p><p><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">&nbsp; &nbsp; 第二行为一个整数</span><span style="FONT-SIZE: 16px">a</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">，第一行输出</span><span style="FONT-SIZE: 16px">0</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">则</span><span style="FONT-SIZE: 16px">a</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">代表最多可完成</span><span style="FONT-SIZE: 16px">a</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">个环节，第一行输出</span><span style="FONT-SIZE: 16px">1</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">则</span><span style="FONT-SIZE: 16px">a</span><span style="FONT-SIZE: 16px; FONT-FAMILY: 宋体">代表完成任务至少需要花费的费用。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 4 3 2</span></p><p><span style="">1 2 1</span></p><p><span style="">2 3 1</span></p><p><span style="">3 4 1</span></p><p><span style="">4 5 1</span></p><p><span style="">1 10</span></p><p><span style="">3 10        </span></p><p><span style="">5 100</span></p><p><span style="">2 4</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">1</span></p><p><span style="">141</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>样例解释</strong>   <span style="">从2-1-2-3-4-5</span><span style="">花费最小，为20+10+10+1+100=141.</span></p><p><span style=""><br></span></p><p><strong><span style="">数据范围</span></strong></p><p><span style=""></span></p><p><span style="">对于</span><span style="">10%</span><span style="">的数据，第一行输出</span><span style="">0</span><span style="">。</span></p><p><span style="">对于另</span><span style="">10%</span><span style="">的数据，</span><span style="">k=p=1</span><span style="">。</span></p><p><span style="">对于</span><span style="">100%</span><span style="">的数据，</span><span style="">1</span><span style="">≤</span><span style="">n</span><span style="">≤</span><span style="">10000</span><span style="">；</span><span style="">1</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">50000</span><span style="">；</span><span style="">1</span><span style="">≤</span><span style="">k</span><span style="">≤</span><span style="">100</span><span style="">；</span><span style="">1</span><span style="">≤</span><span style="">p</span><span style="">≤</span><span style="">10</span><span style="">。</span></p><p><span style="">对于</span><span style="">100%</span><span style="">的数据，保证数据及答案不超过</span><span style="">maxlongint</span><span style="">。</span></p><p><span style=""><br></span><br></p>
</div>
</div>