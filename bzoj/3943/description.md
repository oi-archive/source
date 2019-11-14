
# Description

<div class="content"><div>
<div>Bessie and her friends are playing hoofball in the annual Superbull championship, and Farmer John is</div>
<div> in charge of making the tournament as exciting as possible. A total of N (1 &lt;= N &lt;= 2000) teams are</div>
<div> playing in the Superbull. Each team is assigned a distinct integer team ID in the range 1...2^30-1 </div>
<div>to distinguish it from the other teams. The Superbull is an elimination tournament -- after every ga</div>
<div>me, Farmer John chooses which team to eliminate from the Superbull, and the eliminated team can no l</div>
<div>onger play in any more games. The Superbull ends when only one team remains.Farmer John notices a ve</div>
<div>ry unusual property about the scores in matches! In any game, the combined score of the two teams al</div>
<div>ways ends up being the bitwise exclusive OR (XOR) of the two team IDs. For example, if teams 12 and </div>
<div>20 were to play, then 24 points would be scored in that game, since 01100 XOR 10100 = 11000.Farmer J</div>
<div>ohn believes that the more points are scored in a game, the more exciting the game is. Because of th</div>
<div>is, he wants to choose a series of games to be played such that the total number of points scored in</div>
<div> the Superbull is maximized. Please help Farmer John organize the matches.</div>
<div>贝西和她的朋友们在参加一年一度的“犇”(足)球锦标赛。FJ的任务是让这场锦标赛尽可能地好看。一共有N支球</div>
<div>队参加这场比赛，每支球队都有一个特有的取值在1-230-1之间的整数编号(即：所有球队编号各不相同)。“犇”</div>
<div>锦标赛是一个淘汰赛制的比赛——每场比赛过后，FJ选择一支球队淘汰，淘汰了的球队将不能再参加比赛。锦标赛</div>
<div>在只有一支球队留下的时候就结束了。FJ发现了一个神奇的规律：在任意一场比赛中，这场比赛的得分是参加比赛</div>
<div>两队的编号的异或(Xor)值。例如：编号为12的队伍和编号为20的队伍之间的比赛的得分是24分，因为 12(01100) </div>
<div>Xor 20(10100) = 24(11000)。FJ相信比赛的得分越高，比赛就越好看，因此，他希望安排一个比赛顺序，使得所</div>
<div>有比赛的得分和最高。请帮助FJ决定比赛的顺序</div>
</div>
<p></p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></p>
<p></p></div>

# Input

<div class="content"><div>
<div>
<div>The first line contains the single integer N. The following N lines contain the N team IDs.</div>
<div>第一行包含一个整数N接下来的N行包含N个整数，第i个整数代表第i支队伍的编号, 1&lt;=N&lt;=2000</div>
</div>
</div>
<div>
<p></p>
</div>
<div>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></p>
</div>
<p></p></div>

# Output

<div class="content"><h4 style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">
<div>
<div>Output the maximum possible number of points that can be scored in the Superbull.</div>
<div>一行，一个整数，表示锦标赛的所有比赛的得分的最大值</div>
</div>
</h4>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3<br/>
6<br/>
9<br/>
10</span></div>

# Sample Output

<div class="content"><span class="sampledata">37<br/>
</span></div>

# Hint

<div class="content"><p></p><div>样例解释：</div><br/>
<div>FJ先让编号为3和编号为9的队伍进行比赛，然后让编号为9的队伍赢得比赛(淘汰编号为6的队伍)，现在</div><br/>
<div>剩下了编号为6910的队伍。然后他让编号为6和编号为9的队伍比赛，然后让编号为6的队伍赢得比赛。现在编号为6</div><br/>
<div>10的队伍留了下来最后让编号为6和编号为10的队伍比赛，让编号为10的队伍赢得比赛。所有比赛的得分和就是：(</div><br/>
<div>3Xor9)+(6Xor9)+(6Xor10)=10+15+12=37</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

