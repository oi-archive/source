<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一年一度的“农心杯”三国围棋擂台赛是世界上最高水平的围棋比赛，也是中日韩三国围棋界最激动人心的较量。本题就是建立在这一比赛的规则之上。</p>
<p>三国围棋擂台赛是三个国家的代表队之间的比赛，下面简要介绍一下比赛的规则：</p>
<ol>
<li>不妨设三个国家分别为<em>A</em><em>、B</em>和<em>C</em>，每个国家各有<em>n</em>名选手（在上述的实际比赛中<em>n</em> = 5），分别称其为<em>A</em><sub>1</sub>，<em>A</em><sub>2</sub>，…，<em>A<sub>n</sub></em>，<em>B</em><sub>1</sub>，<em>B</em><sub>2</sub>，…，<em>B<sub>n</sub></em>，<em>C</em><sub>1</sub>，<em>C</em><sub>2</sub>，…，<em>C<sub>n</sub></em>。</li>
<li>每场比赛都能分出胜负。每场比赛的负者遭到淘汰。</li>
<li> 每队第一位出场的选手都已经确定为每队的第<em>n</em>位选手，即<em>A<sub>n</sub></em>、<em>B<sub>n</sub></em>和 <em>C<sub>n</sub></em>。<ol>
<li>通过抽签等概率地选出一支队伍。该队将在第一轮中轮空，而剩下的两支队伍的第<em>n</em>位选手将进行第一场比赛。</li>
<li>第一场比赛的胜者（这里的胜者是指赢得该局比赛的选手，下同）与轮空队伍的第<em>n</em>位选手进行第二场比赛。比如在第一场比赛中<em>C<sub>n</sub></em>战胜了<em>A<sub>n</sub></em>，则第二场则由<em>C<sub>n</sub></em>对阵<em>B<sub>n</sub></em>。</li>
<li>从第三场比赛开始，前一场比赛未参加的队伍将选出一个未被淘汰的选手与上一场比赛的胜者进行下一场比赛。</li>
<li>这个过程将一直进行，直到某个队伍的全部参赛选手都被淘汰为止。</li>
<li>当只有两支队伍的时候，每场比赛后，由负方选择一位未被淘汰的选手与胜者进行下一场比赛。</li>
<li>当两支队伍中的任意一队的全部选手均被淘汰后比赛结束，余下的那支队伍将获得农心杯。</li>
</ol></li>
</ol>
<p>新一届的比赛就要开始了。你作为<em>A</em>队的领队，在比赛开始前已经统计了这3<em>n</em>位选手之间的胜率——即对于来自不同队伍的两个选手<em>Q</em>和<em>R</em>，我们已知<em>Q</em>战胜<em>R</em>的概率为<em>p</em>（），且<em>R</em>战胜<em>Q</em>的概率为。</p>
<p>由于你所在的国家实力超群，可以认为剩下的两只队伍都将矛头对准了你。<em>B</em>、<em>C</em>队的每个决策，即派出选手的顺序的目的都是使你所在的国家（<em>A</em>队）夺冠的概率尽可能小，而<em>A</em>队的决策的目的必然是使最后夺冠的概率尽可能大。你要做的事情就是计算出在这种极为不利的情况下，在三方都做出最优决策的前提下，<em>A</em>队夺冠的期望<em>E<sub>A</sub></em>。</p>
<p>关于期望的计算：设现在在场上比赛的人是<em>Q</em>和<em>R</em>，<em>Q</em>胜<em>R</em>的概率为<em>p</em>，则此时<em>A</em>队胜率的期望</p>
<p> </p>
<p>其中为<em>Q</em>胜<em>R</em>后<em>A</em>队夺冠的期望，为<em>R</em>胜<em>Q</em>后<em>A</em>队夺冠的期望。、则同样使用上式递归计算。</p>
<p><em>A</em>队的决策会尽可能使这个期望尽可能大，而<em>B</em>、<em>C</em>队则会使这个期望尽可能小。当<em>B</em>、<em>C</em>队的全部选手都被淘汰后夺冠期望为1，<em>A</em>队所有队员被淘汰后期望为0。</p>
<p>例如当每队有3位参赛选手时，相互之间的胜率由如下的3个的矩阵给出，其中矩阵中的每个数值<em>p</em>为所在行选手对于所在列选手的胜率，所在列选手对于所在行选手的胜率为。</p>
<table border="0" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td width="32">
<p> </p>
</td>
<td width="34">
<p><em>B</em><sub>1</sub></p>
</td>
<td width="34">
<p><em>B</em><sub>2</sub></p>
</td>
<td width="34">
<p><em>B</em><sub>3</sub></p>
</td>
<td valign="top" width="34">
<p> </p>
</td>
<td width="34">
<p> </p>
</td>
<td width="34">
<p><em>C</em><sub>1</sub></p>
</td>
<td width="34">
<p><em>C</em><sub>2</sub></p>
</td>
<td width="34">
<p><em>C</em><sub>3</sub></p>
</td>
<td valign="top" width="34">
<p> </p>
</td>
<td width="34">
<p> </p>
</td>
<td width="34">
<p><em>C</em><sub>1</sub></p>
</td>
<td width="34">
<p><em>C</em><sub>2</sub></p>
</td>
<td width="34">
<p><em>C</em><sub>3</sub></p>
</td>
</tr>
<tr>
<td width="32">
<p><em>A</em><sub>1</sub><em></em></p>
</td>
<td width="34">
<p>1.0</p>
</td>
<td width="34">
<p>0.0</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td valign="top" width="34">
<p><em> </em></p>
</td>
<td width="34">
<p><em>A</em><sub>1</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>1.0</p>
</td>
<td valign="top" width="34">
<p><em> </em></p>
</td>
<td width="34">
<p><em>B</em><sub>1</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.0</p>
</td>
<td width="34">
<p>1.0</p>
</td>
</tr>
<tr>
<td width="32">
<p><em>A</em><sub>2</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>1.0</p>
</td>
<td width="34">
<p>1.0</p>
</td>
<td valign="top" width="34">
<p><em> </em></p>
</td>
<td width="34">
<p><em>A</em><sub>2</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.0</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td valign="top" width="34">
<p><em> </em></p>
</td>
<td width="34">
<p><em>B</em><sub>2</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
</tr>
<tr>
<td width="32">
<p><em>A</em><sub>3</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td valign="top" width="34">
<p><em> </em></p>
</td>
<td width="34">
<p><em>A</em><sub>3</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td valign="top" width="34">
<p><em> </em></p>
</td>
<td width="34">
<p><em>B</em><sub>3</sub></p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
<td width="34">
<p>0.5</p>
</td>
</tr>
</tbody>
</table>
<p>三支队的第三位选手的水平相同，在第两局比赛后，三支队的选手获胜的概率是相同的。假设第二局获胜的是<em>B</em><sub>3</sub>，第三局轮到<em>A</em>队出场。这时我们可以排出<em>A</em><sub>1</sub><em> </em>和<em>A</em><sub>2</sub>两种选择。</p>
<p>如果派出<em>A</em><sub>2</sub>，虽然第三局一定可以战胜<em>B</em><sub>3</sub>（胜率为100%），但是<em>C</em>队会在第四场比赛中派出<em>C</em><sub>2</sub>，<em>A</em><sub>2</sub>对于<em>C</em><sub>2</sub>必败（胜率为0），第五场中<em>B</em>队会让<em>B</em><sub>1</sub>出场，第六场<em>A</em><sub>1</sub>只能出场，这时对<em>A</em><sub>1</sub>必胜的<em>B</em><sub>2</sub>还未登场，因此<em>A</em><sub>1</sub>迟早会遭到淘汰，<em>A</em>队夺冠的概率就为0。</p>
<p>如果派出<em>A</em><sub>1</sub>，虽然本局对于<em>B</em><sub>3</sub>比赛只有50%的胜率，但是夺冠的概率为6.25%；因此在第三场应该派出<em>A</em><sub>1</sub>。</p>
<p>根据第三场比赛的参赛选手的六种情况，最后夺冠的期望为：</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括一个整数<em>n</em>，表示每队的选手数。</p>
<p>第二行到第<em>n</em> + 1行每行包含<em>n</em>个实数，整体为一个的矩阵，表示<em>A</em>队对<em>B</em>队的胜率。其中第<em>i</em> + 1行的第<em>j</em>个数表示选手<em>A<sub>i</sub></em>对选手<em>B<sub>j</sub></em>时的胜率。</p>
<p>第<em>n</em>+2行为空行。</p>
<p>第<em>n</em> + 3行到第2<em>n</em> + 2行每行包含<em>n</em>个实数，同样为一个的矩阵，表示<em>A</em>队对<em>C</em>队的胜率。其中第<em>i</em> + <em>n</em> + 2行的第<em>j</em>个数表示选手<em>A<sub>i</sub></em>对选手<em>C<sub>j</sub></em>时的胜率。</p>
<p>第2<em>n</em> + 3行为空行。</p>
<p>第2<em>n</em> + 4行到第3<em>n</em> + 3行每行包含<em>n</em>个实数，整体为一个的矩阵，表示<em>B</em>队对<em>C</em>队的胜率。其中第<em>i</em> + 2<em>n</em> + 3行的第<em>j</em>个数表示选手<em>B<sub>i</sub></em>对选手<em>C<sub>j</sub></em>时的胜率。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="NOI">仅包含一个实数，保留6位小数，表示<em>A</em>队获得冠军的概率。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3</span></p>
<p><span>1.0 0.0 0.5</span></p>
<p><span>0.5 1.0 1.0</span></p>
<p><span>0.5 0.5 0.5</span></p>
<p><span> </span></p>
<p><span>0.5 0.5 1.0</span></p>
<p><span>0.5 0.0 0.5</span></p>
<p><span>0.5 0.5 0.5</span></p>
<p><span> </span></p>
<p><span>0.5 0.0 1.0</span></p>
<p><span>0.5 0.5 0.5</span></p>
<p><span>0.5 0.5 0.5 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>0.273438</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据中，<em>n</em> ≤ 4。</p>
<p>40%的数据中，<em>n</em> ≤ 5。</p>
<p>100%的数据中，<em>n</em> ≤ 7。</p>
<p>对于10%的数据有三个胜率矩阵中，每个矩阵的元素都相同，但不同矩阵的数字可能不同。</p>
<p> </p>
</div>
</div>