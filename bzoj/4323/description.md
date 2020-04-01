
# Description

<div class="content"><div>有N个书架，每个书架可以容纳M本书。给出了若干本书，每本书有一个正整数的唯一编号，且编号不超过N*M。 给出了初始时各个书架里面的书的编号，即给出二维数组S[1..N][1..M]。设S[i][j]=k，表示的意义是第i个书架的第j个格子放的那本书的编号是k。如果k等于0则说明该格子没有书，是空的。一个格子最多只能放一本书。再给出二维数组T[1..N][1..M]，表示最终你需要把这些书经过移动之后达到的目的。你移动书的过程需要满足如下两个条件：</div>
<div>1、你可以把某一个书架的书向左或者向右推动一格。这就是横向的“推”动作，你可以“推”任意多次。</div>
<div>2、你可以拿起某一个书架的一本书，然后把这本书放到任意书架的空格子里。这就是“拿”动作。你可以“拿”任意多次。注意：当你“拿”起一本书时，你是不能做“推”的动作。则“拿”起一本书，接下来的那个动作必须是把这本书放到一个空格子里。每次只能“拿”起一本书。</div>
<div>现在你的任务是：用最少次数的“拿”动作，去完成目标，如果无法完成目标，输出-1。</div>
<div></div>
<p style="margin: 10px auto; padding: 0px; font-family: Verdana, Arial, Helvetica, sans-serif; font-size: 13.920001029968262px; line-height: 13.333333015441895px;"></p>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行，两个整数N和M。 1&lt;=N,M&lt;=1000。</div>
<div>接下来是N行M列的S二维数组。</div>
<div>接下来是N行M列的T二维数组。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><p>最少次数的“拿”动作。</p>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 4<br/>
1 0 2 0<br/>
3 5 4 0<br/>
2 1 0 0<br/>
3 0 4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><div></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

