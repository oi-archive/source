
# Description

<div class="content"><div>绘画家小Q正在他的数位板上作画。当他在作画的时候，他的设备突然故障了！此时他的笔变成了擦除模式。在小Q</div>
<div>的脑海中，有一副漂亮的图案，他希望最后能将它呈现在板子上。他按照自己的创作风格，一步一步地绘画。他每</div>
<div>一步只可能是4种指令上(up)下(down)左(left)右(right)中的一种，同时指定一个距离d，每秒往那个方向移动一</div>
<div>步。在创作的一开始，他的笔位于数位板的左下角，且任意时刻他的笔都不会离开数位板。考虑6*8的数位板以及</div>
<div>如下图所示的指令集，如果笔在第17秒末故障了，数位板最终会变成第二幅图的样子。</div>
<div><img src="/source/bzoj/4879/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNS9waWNCLnBuZw==.png" width="663" height="220" alt=""/></div>
<div>小Q想知道最早和最晚的时刻t，满足如果数位板在第t秒末故障了，最终显示出来的图案与他预想的一致。注意数</div>
<div>位板可以在第0秒末故障，此时小Q的笔还没有触碰到数位板。</div></div>

# Input

<div class="content"><div>第一行包含三个正整数h,w,n(1&lt;=h,w,n&lt;=10^6,1&lt;=w*h&lt;=10^6)，分别表示数位板的高度与宽度以及指令的条数。</div>
<div>接下来h行，每行w个字符</div>
<div>每个字符要么是“#”，要么是“.”。表示小Q预想的效果，其中“#”表示有颜色，“.”表示空白。</div>
<div>接下来n行</div>
<div>每行一个字符串s和一个正整数d(1&lt;=d&lt;=10^6)，分别表示方向和距离，输入数据保证操作不会使笔离开数位板。</div></div>

# Output

<div class="content"><div>输出一行两个整数x与y，其中x表示最小的合法的t，y表示最大的合法的t</div>
<div>注意y不能超过最后一条指令执行完毕时的时间。若无解则输出“-1 -1”。</div></div>

# Sample Input

<div class="content"><span class="sampledata">6 8 5<br/>
........<br/>
........<br/>
###.####<br/>
#......#<br/>
#..#####<br/>
#.......<br/>
up 3<br/>
right 7<br/>
down 2<br/>
left 4<br/>
up 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">17 17<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获得">本OJ付费获得</a></p></div>

