
# Description

<div class="content"><p><span style="font-size: medium">机器人刚刚探查归来，探险队员们突然发现自己的脚下出现了一朵朵白云，把他们托向了空中。一阵飘飘然的感觉过后，队员们发现自己被传送到了一座空中花园。<br/>
“远道而来的客人，我们是守护Nescafe之塔的精灵。如果你们想拜访护法和圣主的话，就要由我们引路。因此，你们是不是该给我们一点礼物呢T_T？”<br/>
队员们往远处一看，发现花园中有N个木箱，M条柔软的羊毛小路，每条小路的两个端点都是木箱，并且通过它需要ti的时间。队员们需要往每个木箱中放一份礼物，不过由于精灵们不想让花园被过多地踩踏，因此运送礼物的任务最多只能由两位探险队员完成。<br/>
两位探险队员同时从1号木箱出发，可以在任意木箱处结束运送。运送完毕时，每只木箱应该被两位队员中至少一人访问过。运送任务所用的时间是两人中较慢的那个人结束运送任务的时间。请问这个时间最快是多少呢？</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行两个正整数N、M。<br/>
接下来M行每行三个整数xi、yi、ti，表示xi和yi之间有一条用时为ti的小路，小路是双向的。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
输出所需的最短时间。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6<br/>
1 2 10<br/>
2 3 10<br/>
3 4 5<br/>
4 5 10<br/>
5 6 20<br/>
2 5 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">40<br/>
</span></div>

# Hint

<div class="content"><p></p><p>1&lt;=N&lt;=18，1&lt;=ti&lt;=1000，1&lt;=xi,yi&lt;=N，两个木箱之间最多只有一条小路，不会有自己到自己的小路，保证所有木箱是连通的。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize10">Poetize10</a></p></div>

