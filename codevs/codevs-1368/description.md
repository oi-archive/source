<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>第XXXX届NOI期间，为了加强各省选手之间的交流，组委会决定组织一场省际电子竞技大赛，每一个省的代表队由n名选手组成，比赛的项目是老少咸宜的网络游戏泡泡堂。每一场比赛前，对阵双方的教练向组委会提交一份参赛选手的名单，决定了选手上场的顺序，一经确定，不得修改。比赛中，双方的一号选手，二号选手……，n号选手捉对厮杀，共进行n场比赛。每胜一场比赛得2分，平一场得1分，输一场不得分。最终将双方的单场得分相加得出总分，总分高的队伍晋级(总分相同抽签决定)。</p>
<p>作为浙江队的领队，你已经在事先将各省所有选手的泡泡堂水平了解的一清二楚，并将其用一个实力值来衡量。为简化问题，我们假定选手在游戏中完全不受任何外界因素干扰，即实力强的选手一定可以战胜实力弱的选手，而两个实力相同的选手一定会战平。由于完全不知道对手会使用何种策略来确定出场顺序，所以所有的队伍都采取了这样一种策略，就是完全随机决定出场顺序。</p>
<p>当然你不想这样不明不白的进行比赛。你想事先了解一下在最好与最坏的情况下，浙江队最终分别能得到多少分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件的第一行为一个整数n，表示每支代表队的人数。</p>
<p>       接下来n行，每行一个整数，描述了n位浙江队的选手的实力值。</p>
<p>       接下来n行，每行一个整数，描述了你的对手的n位选手的实力值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;输入文件中包括两个用空格隔开的整数，分别表示浙江队在最好与最坏的情况下分别能得多少分。不要在行末输出多余的空白字符。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例数据1】</p>
<p>2</p>
<p>1</p>
<p>3</p>
<p>2</p>
<p>4</p>
<p>【样例数据2】</p>
<p>6</p>
<p>10000000</p>
<p>10000000</p>
<p>10000000</p>
<p>10000000</p>
<p>10000000</p>
<p>10000000</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例数据1】</p>
<p>2 0</p>
<p>【样例数据2】</p>
<p>12 12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>样例说明1</strong></p>
<p>我们分别称4位选手为A,B,C,D。则可能出现以下4种对战方式，最好情况下可得2分，最坏情况下得0分。</p>
<p><strong>样例说明2</strong></p>
<div>
<p>对手都是认真学习的好孩子，不会打游戏。无论如何排列出场顺序都无法改变被蹂躏的结果。浙江队总能取得全胜的结果。</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top">
<p> </p>
</td>
<td valign="top">
<p>一</p>
</td>
<td valign="top">
<p>二</p>
</td>
<td valign="top">
<p>三</p>
</td>
<td valign="top">
<p>四</p>
</td>
</tr>
<tr>
<td valign="top">
<p> </p>
</td>
<td valign="top">
<p>浙江</p>
</td>
<td valign="top">
<p>???</p>
</td>
<td valign="top">
<p>结果</p>
</td>
<td valign="top">
<p>浙江</p>
</td>
<td valign="top">
<p>???</p>
</td>
<td valign="top">
<p>结果</p>
</td>
<td valign="top">
<p>浙江</p>
</td>
<td valign="top">
<p>???</p>
</td>
<td valign="top">
<p>结果</p>
</td>
<td valign="top">
<p>浙江</p>
</td>
<td valign="top">
<p>???</p>
</td>
<td valign="top">
<p>结果</p>
</td>
</tr>
<tr>
<td valign="top">
<p>一号选手</p>
</td>
<td valign="top">
<p>A</p>
</td>
<td valign="top">
<p>C</p>
</td>
<td valign="top">
<p>负</p>
</td>
<td valign="top">
<p>A</p>
</td>
<td valign="top">
<p>D</p>
</td>
<td valign="top">
<p>负</p>
</td>
<td valign="top">
<p>B</p>
</td>
<td valign="top">
<p>C</p>
</td>
<td valign="top">
<p>胜</p>
</td>
<td valign="top">
<p>B</p>
</td>
<td valign="top">
<p>D</p>
</td>
<td valign="top">
<p>负</p>
</td>
</tr>
<tr>
<td valign="top">
<p>二号选手</p>
</td>
<td valign="top">
<p>B</p>
</td>
<td valign="top">
<p>D</p>
</td>
<td valign="top">
<p>负</p>
</td>
<td valign="top">
<p>B</p>
</td>
<td valign="top">
<p>C</p>
</td>
<td valign="top">
<p>胜</p>
</td>
<td valign="top">
<p>A</p>
</td>
<td valign="top">
<p>D</p>
</td>
<td valign="top">
<p>负</p>
</td>
<td valign="top">
<p>A</p>
</td>
<td valign="top">
<p>C</p>
</td>
<td valign="top">
<p>负</p>
</td>
</tr>
<tr>
<td valign="top">
<p>总得分</p>
</td>
<td valign="top">
<p>0</p>
</td>
<td valign="top">
<p>2</p>
</td>
<td valign="top">
<p>2</p>
</td>
<td valign="top">
<p>0</p>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>