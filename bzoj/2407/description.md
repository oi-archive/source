
# Description

<div class="content"><div>探险家小T好高兴！X国要举办一次溶洞探险比赛，获奖者将得到丰厚奖品哦！小T虽然对奖品不感兴趣，但是这个大振名声的机会当然不能错过！</div>
<div>比赛即将开始，工作人员说明了这次比赛的规则：每个溶洞和其他某些溶洞有暗道相连。两个溶洞之间可能有多条道路，也有可能没有，但没有一条暗道直接从自己连到自己。参赛者需要统一从一个大溶洞出发，并再次回到这个大溶洞。</div>
<div>如果就这么点限制，那么问题就太简单了，可是举办方又提出了一个条件：<b>不能经过同一条暗道两次</b>。这个条件让大家犯难了。这该怎么办呢？</div>
<div>到了大溶洞口后，小T愉悦地发现这个地方他曾经来过，他还记得有哪些暗道，以及通过每条暗道的时间。小T现在向你求助，你能帮他算出至少要多少时间才能回到大溶洞吗？</div></div>

# Input

<div class="content"><p>第一行两个数<i>n</i><i>，m</i>表示溶洞的数量以及暗道的数量。</p>
<div>接下来m行，每行4个数<i>s</i><i>、t</i><i>、w</i><i>、v</i>，表示一个暗道连接的两个溶洞<i>s</i><i>、t</i>，这条暗道正着走（<i>s </i><i><span>à</span> t</i>）的所需要的时间<i>w</i>，倒着走（<i>t </i><i><span>à</span> s</i>）所需要的时间<i>v</i>。由于溶洞的相对位置不同，<i>w</i>与<i>v</i>可能不同。</div></div>

# Output

<div class="content"><div>输出一行一个数t，表示最少所需要的时间。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 2 1<br/>
2 3 4 5<br/>
3 1 3 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p><p class="NOI" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font face="Times New Roman" size="3">N&lt;=10000,M&lt;=200000,1&lt;=W,V&lt;=10000</font></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

