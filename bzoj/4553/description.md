
# Description

<div class="content"><p> 佳媛姐姐过生日的时候，她的小伙伴从某宝上买了一个有趣的玩具送给他。玩具上有一个数列，数列中某些项的值</p>
<div>可能会变化，但同一个时刻最多只有一个值发生变化。现在佳媛姐姐已经研究出了所有变化的可能性，她想请教你</div>
<div>，能否选出一个子序列，使得在任意一种变化中，这个子序列都是不降的？请你告诉她这个子序列的最长长度即可</div>
<div>。注意：每种变化最多只有一个值发生变化。在样例输入1中，所有的变化是：</div>
<div>1 2 3</div>
<div>2 2 3</div>
<div>1 3 3</div>
<div>1 1 31 2 4</div>
<div>选择子序列为原序列，即在任意一种变化中均为不降子序列在样例输入2中，所有的变化是:3 3 33 2 3选择子序列</div>
<div>为第一个元素和第三个元素，或者第二个元素和第三个元素，均可满足要求</div></div>

# Input

<div class="content"><p> 输入的第一行有两个正整数n, m，分别表示序列的长度和变化的个数。接下来一行有n个数，表示这个数列原始的</p>
<div>状态。接下来m行，每行有2个数x, y，表示数列的第x项可以变化成y这个值。1 &lt;= x &lt;= n。所有数字均为正整数</div>
<div>，且小于等于100,000</div></div>

# Output

<div class="content"><p> <span style="font-family: gbsnu8f; font-size: 9pt;">输<span style="font-family: gbsnu51; font-size: 9pt;">出<span style="font-family: gbsnu4e; font-size: 9pt;">一个<span style="font-family: gbsnu65; font-size: 9pt;">整数<span style="font-family: gbsnuff; font-size: 9pt;">，<span style="font-family: gbsnu88; font-size: 9pt;">表<span style="font-family: gbsnu79; font-size: 9pt;">示<span style="font-family: gbsnu5b; font-size: 9pt;">对<span style="font-family: gbsnu5e; font-size: 9pt;">应<span style="font-family: gbsnu76; font-size: 9pt;">的<span style="font-family: gbsnu7b; font-size: 9pt;">答<span style="font-family: gbsnu68; font-size: 9pt;">案<br style="orphans: 2; text-align: -webkit-auto; widows: 2;"/>
</span></span></span></span></span></span></span></span></span></span></span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 2 3<br/>
1 2<br/>
2 3<br/>
2 1<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

