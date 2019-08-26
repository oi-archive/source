
# Description

<div class="content"><div style="text-indent: 21pt">你小时候玩过弹珠吗？</div>
<div style="text-indent: 21pt">小朋友A有一些弹珠，A喜欢把它们排成队列，从左到右编号为1到N。为了整个队列鲜艳美观，小朋友想知道某一段连续弹珠中，不同颜色的弹珠有多少。当然，A有时候会依据个人喜好，替换队列中某个弹珠的颜色。但是A还没有学过编程，且觉得头脑风暴太浪费脑力了，所以向你来寻求帮助。</div></div>

# Input

<div class="content"><div style="text-indent: 21pt">输入文件第一行包含两个整数N和M。</div>
<div style="text-indent: 21pt">第二行N个整数，表示初始队列中弹珠的颜色。</div>
<div style="text-indent: 21pt">接下来M行，每行的形式为“Q L R”或“R x c”，“Q L R”表示A想知道从队列第L个弹珠到第R个弹珠中，一共有多少不同颜色的弹珠，“R x c”表示A把x位置上的弹珠换成了c颜色。</div></div>

# Output

<div class="content"><div style="text-indent: 21pt">对于每个Q操作，输出一行表示询问结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
2 3<br/>
1 2<br/>
Q 1 2<br/>
R 1 2<br/>
Q 1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，有1 ≤ N ≤ 10000, 1 ≤ M ≤ 10000，小朋友A不会修改超过1000次，所有颜色均用1到10^6的整数表示。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

