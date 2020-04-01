
# Description

<div class="content"><div>红学姐和黄学长是好朋友。红学姐有一只宠物，叫魔法猪。黄学长也有一只宠物，叫小奇。有 n 个猪圈排成一排</div>
<div>，魔法猪藏在某个猪圈中。为了找到魔法猪，小奇会向你询问一些猪圈中猪的个数和。在询问的过程中，魔法猪可</div>
<div>能会释放魔法来改变这些猪圈。</div>
<div>共有 m 次操作。每次操作是以下三种之一。</div>
<div>Q x y 询问从左到右第 x 个猪圈到第 y 个猪圈中猪的个数和。</div>
<div>C x y 将从左到右第 x 个猪圈中猪的个数变为 y。</div>
<div>M x y 将从左到右第 x 个猪圈移动到第 y 个猪圈的位置，并将第 y 个猪圈到第 x-1 个猪圈全部右移一格。保证</div>
<div> x&gt;y。保证任何时候每个猪圈中猪的数量在 0 至 1000000 之间。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个整数 n，m,其值均小于等于10^5</div>
<div>第二行 n 个整数表示从左到右每个猪圈中猪的个数。</div>
<div>接下来 m 行每行一个操作。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问操作，输出一行一个整数表示答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
1 2 3 4 5<br/>
Q 2 4<br/>
M 4 2<br/>
C 3 10<br/>
C 1 4<br/>
Q 1 3<br/>
Q 3 5<br/>
M 5 3<br/>
Q 1 3<br/>
C 4 1<br/>
Q 1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
18<br/>
18<br/>
13<br/>
17</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

