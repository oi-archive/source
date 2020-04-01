
# Description

<div class="content"><div>宅男JYY非常喜欢玩RPG游戏，并且JYY总是想花费最少的时间看完所 有的支线剧情。最近JYY买了一款新的正版RPG</div>
<div>游戏,所以JYY总算可以“读 档”和“存档”了！JYY现在所玩的RPG游戏中，一共有N个剧倩点，由1到N编号，第i</div>
<div>个剧情点可以根据JYY的不同的选择，而经过不同的支线剧情，前往Ki种不同的新的剧情点。当然如果Ki为0,则说</div>
<div>明i号剧情点是游戏的一个结局了。</div>
<div>JYY观看一个支线剧情需要一定的时间。</div>
<div>JYY—开始处在1号剧情点，也就是游戏的开始。</div>
<div>JYY买的这款游戏很特殊，从游戏开始到达任何一个剧情点的支线路径都是唯一的。</div>
<div>而且，任何一个剧情点都是从1号剧情点可达的。</div>
<div>与上一款RPG游戏一样，JYY可以在任意时刻选择重新开始游戏，即回到 1号剧情点。不过有些不同的是，这次JYY</div>
<div>买的是正版软件，每当JYY到达一 个剧情点，JYY都可以进行“存档”和“读档”。但是很遗憾的是，JYY的RPG 游</div>
<div>戏只有一个存档的位置：每次“存档”操作都会覆盖之前的存档。比如如果在JYY在x号剧情点进行了 “存档”操</div>
<div>作，那么此后当JYY到达任何一个剧情点（包括结局）都可以“读档”并立即回到x号剧情点。但是如果 之后JYY在</div>
<div>y号剧情点又进行了 “存档”，那么JYY再进行“读档”，就只能回到y号剧情点了。</div>
<div>一开始存档位置里没有存储任何信息，所有JYY只有在进行一次“存档” 操作之后才可以进行“读档”操作。</div>
<div>“读档”，“存档”和“重新开始”都是不需要花费时间的。</div>
<div>重复观看己经看过的剧情是很痛苦，JYY希望花费最少的时间，看完所有不同的支线剧情。</div>
<div></div></div>

# Input

<div class="content"><div>输入一行包含一个正整数N</div>
<div>接下来N行，第i行为第i号剧情点的信息；</div>
<div>第一个非负整数为Ki</div>
<div>接下来Ki个整数对，bij和tij,表示从剧情点i可以前往剧情点bij，并且观看这段支线剧情需要花费tij的时间。</div>
<div>N≤10^6 ，1 ≤ tij ≤10^4 ，Sigma(N,i=1)Ki = N-1</div>
<div></div></div>

# Output

<div class="content"><div>输出一行包含一个整数，表示JYY看完所有支线剧情所需要的最少时间。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
2 5 1 2 1<br/>
2 3 1 6 1<br/>
2 7 1 4 1<br/>
2 8 1 9 1<br/>
0<br/>
0<br/>
0<br/>
0<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
提示<br/>
load表示读档，save表示存档，restart表示重新开始，<br/>
那么最佳路线是： 1-&gt;5-&gt;restart-&gt;2-&gt;save-&gt;6-&gt;load-&gt;3-&gt;save-&gt;7-&gt;load-&gt;4-&gt;save-&gt;8-&gt;load-&gt;9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round3">Round3</a></p></div>

