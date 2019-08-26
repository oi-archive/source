
# Description

<div class="content"><div>You arrive m Ye Olde Magic Shoppe with some hard-earned gold to purchase wondrous and </div>
<div>unique magic items. There are n such items in the shop, each of them locked in a special magic </div>
<div>box. The i-th box costs ci gold pieces to buy, and contains an item worth vi gold pieces. The </div>
<div>costs and item values are known to you, as you have previously read, mastered, and memorized </div>
<div>Ye Olde Magic Catalogue. </div>
<div>A mortal, such as you, can safely carry only one magic item. You therefore aim to get the </div>
<div>most precious one. And obtain it you would, if not for a malicious, magical creature, known as </div>
<div>The Imp. </div>
<div>The Imp can cast a mischievous spell, which transforms the content of any magic box into </div>
<div>worthless dust. Of course, he will use the spell just after you buy a box, to make you pay for the </div>
<div>item and not get it. You are thus forced to buy another box, and then the next one_ </div>
<div>The Imp has enough magic to cast the spell at most k times. He can, of course, refrain from </div>
<div>using it, allowing you to keep an item. You can walk away at any time, empty-handed (though </div>
<div>it would surely be a disgrace). However, if you get an item, you must keep it and leave the shop. </div>
<div>You aim to maximize your gain (the value of the acquired item minus all the expenses paid </div>
<div>previously), while The Imp wants to mimmize it. If both vou and the creature use the optimal </div>
<div>strategy, how much gold will vou earn? </div>
<div>T组询问。每组询问： </div>
<div>第一行有两个数字N,K，表示有N个物体，接下来每个物体有2个描述权值Vi, Ci，表示该物体的价值和价格。</div>
<div>商家很坑，他有K次机会使得你买完物品之后就立马让你买的该物品消失（但已经付了钱），而商家的目标</div>
<div>则是使得你的净收入尽量低。你可以无限量买东西，但最后只能带走一件物品，不过当然想要使得净收入尽</div>
<div>量高。在双方皆采取最佳策略的情况下，你最多能得到多少钱？（当然，你也可以什么都不买） </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains the number of test cases T. The descriptions of the test cases </div>
<div>follow: </div>
<div>Each test case starts with a line containing the number of items n (1《n≤ 150 000) and the </div>
<div>the maximum number of The Imp&#39;s spells k (0≤ k &lt; 9). The next n lines contain the items&#39; </div>
<div>values and costs, the i-th line containing the numbers vi and ci, in that order (0≤ vi, ci≤ 10^6). </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>For each test case, output one line containing your gain</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3 1<br/>
10 5<br/>
8 1<br/>
20 12</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

