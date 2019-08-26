
# Description

<div class="content"><p>　　在一个r行c列的网格地图中有一些高度不同的石柱，一些石柱上站着一些蜥蜴，你的任务是让尽量多的蜥蜴逃<br/>
到边界外。 每行每列中相邻石柱的距离为1，蜥蜴的跳跃距离是d，即蜥蜴可以跳到平面距离不超过d的任何一个石<br/>
柱上。石柱都不稳定，每次当蜥蜴跳跃时，所离开的石柱高度减1（如果仍然落在地图内部，则到达的石柱高度不<br/>
变），如果该石柱原来高度为1，则蜥蜴离开后消失。以后其他蜥蜴不能落脚。任何时刻不能有两只蜥蜴在同一个<br/>
石柱上。</p></div>

# Input

<div class="content"><p>　　输入第一行为三个整数r，c，d，即地图的规模与最大跳跃距离。以下r行为石竹的初始状态，0表示没有石柱<br/>
，1~3表示石柱的初始高度。以下r行为蜥蜴位置，“L”表示蜥蜴，“.”表示没有蜥蜴。</p></div>

# Output

<div class="content"><p>　　输出仅一行，包含一个整数，即无法逃离的蜥蜴总数的最小值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 8 2<br/>
00000000<br/>
02000000<br/>
00321100<br/>
02000000<br/>
00000000<br/>
........<br/>
........<br/>
..LLLL..<br/>
........<br/>
........</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p><p><span style="color: rgb(255, 0, 0);"><span style="font-size: medium;">100%的数据满足：1&lt;=r, c&lt;=20, 1&lt;=d&lt;=4</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Pku 2711 Leapin" lizards'="">Pku 2711 Leapin&#39; Lizards</a></p></div>

