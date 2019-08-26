
# Description

<div class="content"><div>众所周知，GFW的出现促进了社会的和谐。Wayne于是想研究一下GFW。</div>
<div>Wayne喜欢网格，所以他把一些网站排成了N_ M的网格，每个格子代表一个网站。每个网</div>
<div>站有一个评分，当然评分可正可负。现在Wayne想用一堵“墙”围住一些网站，使得评分和最大。</div>
<div>所谓“墙”，就是一个由网格的边组成的简单多边形，不能自交，也不能有空洞。</div>
<div>过了一会儿Wayne发现这个模型太一般了。出于一些原因，有些网站必须在“墙”外，我们称之</div>
<div>为“坏网站”；而有些网站必须在“墙”内，我们称之为“好网站”。当然了，“坏网站”的评分不一定</div>
<div>低，“好网站”的评分不一定高。Wayne又想知道，这种情况下，能够得到的最大评分和。注意，并</div>
<div>不总是存在合法的方案，所以当无法实现时，输出“Can not establish GFW.”。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div></div>
<div>第一行两个正整数N和M。</div>
<div>接下来N行，每行M个用空格隔开的整数，表示网站的权值。</div>
<div>最后N行，每行M个用空格隔开的整数，1 表示坏网站，2 表示好网站，0 表示其他网站。</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div>输出两行，第一行一个整数表示一堵“墙”能围住的最大评分和，第二行表示有限制时的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
2 -1 2<br/>
-3 100 -3<br/>
-3 20 -3<br/>
2 0 2<br/>
0 1 0<br/>
0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">123<br/>
17 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><div>对于 100% 的数据，N&lt;=10，M&lt;=10，权值的绝对值不超过 10^6 ，且至少一个权值非负，至少一个好网站。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

