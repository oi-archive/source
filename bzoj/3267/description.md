
# Description

<div class="content"><div>KC在公园里种了一排花，一共有n朵，游手好闲的KC常常在公园里采花。他对每朵花都有一个美丽度鉴赏。由于对</div>
<div>花的喜好不同，有的花分数很高，有的花分数很低，甚至会是负数。KC很忙，每次采花的时候，不可能从第一朵花</div>
<div>，走到第n朵。所以他会先选定一个区间[l,r](1&lt;=l&lt;=r&lt;=n)，作为当天的采花范围。同时为了方便采花，他总是从</div>
<div>[l,r]中最多选出k个互不相交的子区间，将这些子区间的花全部采光。当然，他希望美丽度总和最大。KC对花的鉴</div>
<div>赏随着他对世界观人生观的改变而改变，他会不时地对每朵花的美丽度进行修改，可能改低，也可能提高。KC的行</div>
<div>为持续m天，每天的行为要么是采花，要么是改变花的美丽度。注：(1)[l,r]的最多k个互不相同子区间可以表示成</div>
<div>：[x1,y1],[x2,y2],...,[xt,yt]，满足l&lt;=x1&lt;=y1&lt;x2&lt;=y2&lt;...&lt;xt&lt;=yt&lt;=r，且0&lt;=t&lt;=k。(2)由于是KC种的花，一</div>
<div>朵花采掉第二天会立刻生出来。</div></div>

# Input

<div class="content"><div>
<div>第一行一个正整数n,n&lt;=100000。</div>
<div>第二行n个整数a1,a2...an，表示n朵花的美丽度。|ai|&lt;=500。</div>
<div>第三行一个正整数m,m&lt;=100000。</div>
<div>第四行开始，接下来m行，每行表示该天KC的行为。</div>
<div>修改美丽度的行为用0 i val描述，表示将ai修改为val,|val|&lt;=500。</div>
<div>采花行为用1 l r k描述,k&lt;=20意义如题面。</div>
<div>n,m&lt;=50000,k&lt;=20,ai以及修改的val的绝对值不超过500。</div>
</div></div>

# Output

<div class="content"><div>对于每个采花行为，每行一个整数表示最大的美丽度总和</div></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
9 -8 9 -1 -1 -1 9 -8 9<br/>
3<br/>
1 1 9 1<br/>
1 1 9 2<br/>
1 4 6 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
25<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

