
# Description

<div class="content"><div>有一个有点问题的24小时制电子表，电子表有些显示区烧坏了不会显示，有些显示区会一直显示。给定一个电子表</div>
<div>上的n个连续的时刻，求出表中每一格的状态(正常，肯定发光，肯定不发光，未知)。n&lt;=100。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个整数，表示时钟显示的连续时间。</div>
<div>接下来8n-1行包含了时钟显示的n个大小为7*21的图片，用一个空行分隔。</div>
<div>所有的数字段用两个字符表示，所有的交界段用一个字符表示。字符&#34;X&#34;表示开，字符&#34;.&#34;表示关或者不显示区）。</div>
<div></div></div>

# Output

<div class="content"><div>输出一张7*21的图片，&#34;0&#34;表示烧坏的，&#34;1&#34;表示持续发亮的，&#34;W&#34;表示正常工作的，&#34;?&#34;表示未知的，&#34;.&#34;表示非显示区。</div>
<div>如果给出的连续时间不合法，输出&#34;impossible&#34;。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
.XX...XX.....XX...XX.<br/>
...X.X..X...X..X....X<br/>
...X.X..X.X.X..X....X<br/>
.XX..........XX...XX.<br/>
X....X..X......X.X..X<br/>
X....X..X......X.X..X<br/>
.XX...XX.....XX...XX.<br/>
<br/>
.XX...XX.....XX...XX.<br/>
...X.X..X...X..X....X<br/>
...X.X..X.X.X..X....X<br/>
.XX..........XX...XX.<br/>
X....X..X......X.X..X<br/>
X....X..X......X.X..X<br/>
.XX...XX.....XX...XX.<br/>
<br/>
.XX..........XX...XX.<br/>
...X....X...X..X....X<br/>
...X....X.X.X..X....X<br/>
.XX..........XX......<br/>
X.......X...X..X.X..X<br/>
X.......X...X..X.X..X<br/>
.XX...XX.....XX...XX.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">.??...WW.....??...??.<br/>
?..?.W..?...?..1.0..?<br/>
?..?.W..?.?.?..1.0..?<br/>
.??...??.....11...WW.<br/>
?..?.W..?.0.W..?.1..?<br/>
?..?.W..?...W..?.1..?<br/>
.??...11.....??...??.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Yts1999上传，lbn187提供译文">鸣谢Yts1999上传，lbn187提供译文</a></p></div>

