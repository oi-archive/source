
# Description

<div class="content"><div><span style="color: black">     </span><span style="color: black">很久很久很久很久很久以前,有一个有趣的游戏。这个游戏是这样的,地上 有一些砖块,保证每一块的长度都是</span><span style="color: black">{1,2,3,4}</span><span style="color: black">的一个整数。每次你有两种操作, 拿走 </span><span style="color: black">n </span><span style="color: black">个长度为 </span><span style="color: black">n </span><span style="color: black">的砖块,或者把一个长度大于 </span><span style="color: black">1 </span><span style="color: black">的砖块分为两个长度大于等于 </span><span style="color: black">0 </span><span style="color: black">的砖块。如果某个玩家无法操作,就算这位玩家输。</span></div>
<div><span style="color: black">现在给出你一些局面,判断这个游戏是先手必胜还是后手必胜。</span></div>
<div> </div></div>

# Input

<div class="content"><div><span style="color: black">     </span><span style="color: black">输入的第一行包含一个整数 </span><span style="color: black">T</span><span style="color: black">,</span><span style="color: black">表示数据组数。</span></div>
<div><span style="color: black">接下来有 </span><span style="color: black">T </span><span style="color: black">组,每组四个整数 </span><span style="color: black">a b c d</span><span style="color: black">,</span><span style="color: black">表示长度为 </span><span style="color: black">1 2 3 4 </span><span style="color: black">的砖块分别有多少个。</span></div>
<div> </div></div>

# Output

<div class="content"><div><span style="color: black">     </span><span style="color: black">输出 </span><span style="color: black">T </span><span style="color: black">行,每行一个一个整数,</span><span style="color: black">1 </span><span style="color: black">表示先手必胜,</span><span style="color: black">0 </span><span style="color: black">表示后手必胜。 </span></div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">     3 4210 0010 7010<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">     1 1 0<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据说明】<br/><br/>
30%数据满足:a+2b+3c+4d≤10 <br/><br/>
70%数据满足:max{a, b, c, d}≤14 <br/><br/>
100%数据满足:T≤10, max{a, b, c, d}≤10^10000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

