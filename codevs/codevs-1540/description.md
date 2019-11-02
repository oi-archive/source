<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>公元五八<span style="font-family: Times New Roman;">○</span><span style="">一年，地球居民迁移至金牛座</span><span style="font-family: Times New Roman;">&amp;alpha;</span><span style="">第二行星，在那里发表银河联邦创立宣言，同年改元为宇宙历元年，并开始向银河系深处拓展。</span></p><p>    宇宙历七九九年，银河系的两大军事集团在巴米利恩星域爆发战争。泰山压顶集团派宇宙舰队司令莱因哈特率领十万余艘战舰出征，气吞山河集团点名将杨威利组织麾下三万艘战舰迎敌。</p><p>    杨威利擅长排兵布阵，巧妙运用各种战术屡次以少胜多，难免恣生骄气。在这次决战中，他将巴米利恩星域战场划分成<span style="font-family: Times New Roman;">30000</span><span style="">列，每列依次编号为</span><span style="font-family: Times New Roman;">1, 2, &amp;hellip;, 30000</span><span style="">。之后，他把自己的战舰也依次编号为</span><span style="font-family: Times New Roman;">1, 2, &amp;hellip;, 30000</span><span style="">，让第</span><span style="font-family: Times New Roman;">i</span><span style="">号战舰处于第</span><span style="font-family: Times New Roman;">i</span><span style="">列</span><span style="font-family: Times New Roman;">(i = 1, 2, &amp;hellip;, 30000)</span><span style="">，形成</span><span style="font-family: Times New Roman;">&amp;ldquo;</span><span style="">一字长蛇阵</span><span style="font-family: Times New Roman;">&amp;rdquo;</span><span style="">，诱敌深入。这是初始阵形。当进犯之敌到达时，杨威利会多次发布合并指令，将大部分战舰集中在某几列上，实施密集攻击。合并指令为</span><span style="font-family: Times New Roman;">M i j</span><span style="">，含义为让第</span><span style="font-family: Times New Roman;">i</span><span style="">号战舰所在的整个战舰队列，作为一个整体（头在前尾在后）接至第</span><span style="font-family: Times New Roman;">j</span><span style="">号战舰所在的战舰队列的尾部。显然战舰队列是由处于同一列的一个或多个战舰组成的。合并指令的执行结果会使队列增大。</span></p><p>    然而，老谋深算的莱因哈特早已在战略上取得了主动。在交战中，他可以通过庞大的情报网络随时监听杨威利的舰队调动指令。</p><p>    在杨威利发布指令调动舰队的同时，莱因哈特为了及时了解当前杨威利的战舰分布情况，也会发出一些询问指令：<span style="font-family: Times New Roman;">C i j</span><span style="">。该指令意思是，询问电脑，杨威利的第</span><span style="font-family: Times New Roman;">i</span><span style="">号战舰与第</span><span style="font-family: Times New Roman;">j</span><span style="">号战舰当前是否在同一列中，如果在同一列中，那么它们之间布置有多少战舰。</span></p><p>    作为一个资深的高级程序设计员，你被要求编写程序分析杨威利的指令，以及回答莱因哈特的询问。</p><p>    最终的决战已经展开，银河的历史又翻过了一页<span style="font-family: Times New Roman;">&amp;hellip;&amp;hellip;</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件<span style="font-family: Times New Roman;">galaxy.in</span><span style="">的第一行有一个整数</span><span style="font-family: Times New Roman;">T</span><span style="">（</span><span style="font-family: Times New Roman;">1&lt;=T&lt;=500,000</span><span style="">），表示总共有</span><span style="font-family: Times New Roman;">T</span><span style="">条指令。</span></p><p>以下有<span style="font-family: Times New Roman;">T</span><span style="">行，每行有一条指令。指令有两种格式：</span></p><p>1.        M  i  j  <span style="">：</span><span style="font-family: Times New Roman;">i</span><span style="">和</span><span style="font-family: Times New Roman;">j</span><span style="">是两个整数（</span><span style="font-family: Times New Roman;">1&lt;=i , j&lt;=30000</span><span style="">），表示指令涉及的战舰编号。该指令是莱因哈特窃听到的杨威利发布的舰队调动指令，并且保证第</span><span style="font-family: Times New Roman;">i</span><span style="">号战舰与第</span><span style="font-family: Times New Roman;">j</span><span style="">号战舰不在同一列。</span></p><p>2.        C  i  j  <span style="">：</span><span style="font-family: Times New Roman;">i</span><span style="">和</span><span style="font-family: Times New Roman;">j</span><span style="">是两个整数（</span><span style="font-family: Times New Roman;">1&lt;=i , j&lt;=30000</span><span style="">），表示指令涉及的战舰编号。该指令是莱因哈特发布的询问指令。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件为<span style="font-family: Times New Roman;">galaxy.out</span><span style="font-family: 宋体;">。你的程序应当依次对输入的每一条指令进行分析和处理：</span></p><p class="p0">如果是杨威利发布的舰队调动指令，则表示舰队排列发生了变化，你的程序要注意到这一点，但是不要输出任何信息；</p><p class="p0">如果是莱因哈特发布的询问指令，你的程序要输出一行，仅包含一个整数，表示在同一列上，第<span style="font-family: Times New Roman;">i</span><span style="font-family: 宋体;">号战舰与第</span><span style="font-family: Times New Roman;">j</span><span style="font-family: 宋体;">号战舰之间布置的战舰数目。如果第</span><span style="font-family: Times New Roman;">i</span><span style="font-family: 宋体;">号战舰与第</span><span style="font-family: Times New Roman;">j</span><span style="font-family: 宋体;">号战舰当前不在同一列上，则输出</span><span style="font-family: Times New Roman;">-1</span><span style="font-family: 宋体;">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p><p>M 2 3</p><p>C 1 2</p><p>M 2 4</p><p>C 4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1</p><p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table><tbody><tr><td valign="center" width="92"><p> </p></td><td valign="center" width="92"><p>第一列</p></td><td valign="center" width="92"><p>第二列</p></td><td valign="center" width="92"><p>第三列</p></td><td valign="center" width="92"><p>第四列</p></td><td valign="center" width="92"><p>&amp;hellip;&amp;hellip;</p></td></tr><tr><td valign="center" width="92"><p>初始时</p></td><td valign="center" width="92"><p>1</p></td><td valign="center" width="92"><p>2</p></td><td valign="center" width="92"><p>3</p></td><td valign="center" width="92"><p>4</p></td><td valign="center" width="92"><p>&amp;hellip;&amp;hellip;</p></td></tr><tr><td valign="center" width="92"><p>M 2 3</p></td><td valign="center" width="92"><p>1</p></td><td valign="center" width="92"><p> </p></td><td valign="center" width="92"><p>3</p><p>2</p></td><td valign="center" width="92"><p>4</p></td><td valign="center" width="92"><p>&amp;hellip;&amp;hellip;</p></td></tr><tr><td valign="center" width="92"><p>C 1 2</p></td><td valign="center" width="460"><p>1号战舰与2号战舰不在同一列，因此输出-1</p></td></tr><tr><td valign="center" width="92"><p>M 2 4</p></td><td valign="center" width="92"><p>1</p></td><td valign="center" width="92"><p> </p></td><td valign="center" width="92"><p> </p></td><td valign="center" width="92"><p>4</p><p>3</p><p>2</p></td><td valign="center" width="92"><p>&amp;hellip;&amp;hellip;</p></td></tr><tr><td valign="center" width="92"><p>C 4 2</p></td><td valign="center" width="460"><p>4号战舰与2号战舰之间仅布置了一艘战舰，编号为3，输出1</p></td></tr></tbody></table>
</div>
</div>