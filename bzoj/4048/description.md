
# Description

<div class="content"><div>The aliens from outer space have (finally!) invaded Earth. Defend yourself, or be disintegrated! </div>
<div>Or assimilated. Or eaten. We are not yet sure. </div>
<div>The aliens follow a known attack pattern. There are &#39;n attackers, the i-th one appears at time </div>
<div>ai, at distance di from you. He must be destroyed no later than at time bi, or else he will fire his </div>
<div>weapon, which will definitely end the fight. </div>
<div>Your weapon is an area-blaster, which can be set to any given power. If fired with power R, </div>
<div>it momentarily destroys all aliens at distance R or smaller. It also consumes R fuel cells. </div>
<div>Determine the minimal cost (measured in fuel cells) of destroying all the aliens, without being </div>
<div>killed. </div>
<div>有N个外星人，第i个外星人会在ai时间出现，离你距离di，并且必须在bi之前被消灭。你有一把很NB的武器，</div>
<div>攻击范围是个半径为R的圆，R可以任意调整，不过你以R的范围每攻击一次就要消耗R单位能量。外星人被</div>
<div>攻击一次就会死掉。求需要消灭所有外星人的最小消耗能量。 </div>
<div>N&lt;=300, ai,bi,di&lt;=10000 </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains the number of test cases T. The descriptions of the test cases </div>
<div>
<div>follow: </div>
<div>Each test case starts with a line containing the number of aliens n (1 &lt;= n &lt;= 300). Of the next </div>
<div>n lines, the i-th one contains three integers ai, bi, di, (1 &lt; ai &lt; bi≤ 10 000; I &lt; di≤ 10 000). </div>
<div>The i-th alien appears at time ai, is idle until bi, and his distance from vou is di. </div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>For each test case, output one line containing the mimmum number of cells needed to destrov </div>
<div>all the aliens.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3<br/>
1 4 4<br/>
4 7 5<br/>
3 4 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

