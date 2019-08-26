
# Description

<div class="content"><div style="punctuation-wrap: simple"><span style="font-size: medium"><span style="color: black">    </span><span style="color: black">话说世界上有很多被大神狂虐的水题，比如说上面第二题，在很久很久以前就被很多很多大神在某</span><span style="color: black">OJ</span><span style="color: black">上直接</span><span style="color: black">AC</span><span style="color: black">。本题也是一道水题，自从</span><span style="color: black">2012</span><span style="color: black">年二月份以来，全国的</span><span style="color: black">Oier</span><span style="color: black">就没有没在半小时之内水过这道题的。</span></span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium"><span style="color: black">    </span><span style="color: black">其实本题就是这么一道水题：话说某题库，在某些神题中掺了很多道水题，一位大神突发奇想，想在尽可能短的时间内把水题全部</span><span style="color: black">AC</span><span style="color: black">。大神一般是这么做题的，他会在一秒钟之内把第</span><span style="color: black">i</span><span style="color: black">题到第</span><span style="color: black">i+L</span><span style="color: black">题全部</span><span style="color: black">AC</span><span style="color: black">。大神早就把水题的分布全都摸透了，所以说水题被切是其从诞生起就注定了的命运。不过大神还有别的神题去做，没有太多时间花在水题上，所以他得在尽可能少的时间内将水题切完。为了合理安排水题的切题计划，大神写了个程序来规划。</span></span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium"><span style="color: black">但题库的管理员恶意地想拖慢大神刷水题的速度，于是他老是更改水题的位置，试图使大神的程序判断失误，从而延误大神的时间。当然了，大神的程序是无敌的，管理员每更改水题的位置，大神的程序多可以在极短的时间内判断出大神切水题的时间。而本题也就是这么个问题。</span></span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium"><span style="color: black">    </span><span style="color: black">你就是那位大神</span><span style="color: black">——</span><span style="color: black">湖南</span><span style="color: black">Oier</span><span style="color: black">中的精英。你得为你的切水题计划重新写一个程序了。当然，作为大神的你自然不屑于做这种水题。你可以选择不做此题，而在程序中打出“</span><span style="color: black">I am a godlike cowcowcow!</span><span style="color: black">”，从而积蓄</span><span style="color: black">RP</span><span style="color: black">，在</span><span style="color: black">NOI</span><span style="color: black">上虐爆全场吧！</span></span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium"><span style="color: black">    </span><span style="color: black">注意，管理员可没有保证水题不会在一个位置重合。</span></span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="punctuation-wrap: simple"><span style="font-size: medium">    第一行三个正整数n，L，m。n是水题数目，m是管理员更改水题位置的数目。 </span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium">    接下来n个数，表示n道水题的初始位置。</span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium">    接下来m行，每行两个数i(0&lt;=i&lt;n)，y(0&lt;=y&lt;=1000000000)。表示将第i+1道水题改到y（按输入顺序排名）。</span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="punctuation-wrap: simple"><span style="font-size: medium">    输出共m行，表示第i次管理员改变水题的位置后大神切题所需时间(以秒为单位)。</span></div>
<div style="punctuation-wrap: simple"><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 10 5<br/>
10 15 17 20<br/>
2 16<br/>
1 25<br/>
3 35<br/>
0 38<br/>
2 0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
2<br/>
2<br/>
3 <br/>
 <br/>
 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p>对100%的数据满足，n，m &lt;= 150000，L &lt;= 1000000000。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

