
# Description

<div class="content"><div>Bessie is hoping to fool Farmer John by building a herd of KK realistic robotic cows (1≤K≤100,000)</div>
<div>.It turns out that building a robotic cow is somewhat complicated. There are N (1≤n≤100,000) indiv</div>
<div>idual locations on the robot into which microcontrollers must be connected (so a single microcontrol</div>
<div>ler must be connected at each location). For each of these locations, Bessie can select from a numbe</div>
<div>r of different models of microcontroller, each varying in cost.For the herd of robotic cows to look </div>
<div>convincing to Farmer John, no two robots should behave identically. Therefore, no two robots should </div>
<div>have exactly the same set of microcontrollers. For any pair of robots, there should be at least one </div>
<div>location at which the two robots use a different microcontroller model. It is guaranteed that there </div>
<div>will always be enough different microcontroller models to satisfy this constraint.Bessie wants to ma</div>
<div>ke her robotic herd as cheaply as possible. Help her determine the minimum possible cost to do this!</div>
<div>
<div>贝茜想制造K(1 ≤ K ≤ 100,000)个奶牛机器人来玩弄农夫约翰。一个奶牛机器人需要在N个位置分别安装一个控</div>
<div>制器。每个位置有M_i(1 ≤ M_i ≤ 10)种控制器可供选择，并且每种控制器都有自己价值P_{i,j}(1 ≤ P_{i,j} </div>
<div>≤ 100,000,000)。为了使得奶牛机器人看起来像真的一样，因此贝茜要求没有两个机器人拥有完全相同的控制器</div>
<div>——也就是说至少有一个位置选择了不同的控制器。数据保证在这种条件下至少有K种不同的奶牛。请帮助贝茜计</div>
<div>算制造K个这样的机器人的最小花费。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains NN and KK separated by a space.</div>
<div>The following N lines contain a description of the different microcontroller models available for ea</div>
<div>ch location. The iith such line starts with MiMi (1≤Mi≤10), giving the number of models available </div>
<div>for location ii. This is followed by MiMi space separated integers Pi,jPi,j giving the costs of thes</div>
<div>e different models (1≤Pi,j≤100,000,000).</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Output a single line, giving the minimum cost to construct K robots.</div>
<div>
<div></div>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 10<br/>
4 1 5 3 10<br/>
3 2 3 3<br/>
5 1 3 4 6 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">61</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum 鸣谢Firstlast提供译文">Platinum 鸣谢Firstlast提供译文</a></p></div>

