<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在几何课上，老师画了一个圆，圆上有很多条弦，这些弦两两不重合，但是有些是相交的。你本想把图临摹下来回家好好研究，可惜下课后，图被值日生擦掉了。幸运的是，你准确地记录了弦的数量和弦的相交情况。<br/>
　　现在，你想尽量复原这张图。同时，你还想知道，最多能选出多少条弦，使得选出来的弦两两不相交。</div>
# 输入格式

<div class="pdcont">　　第一行包含2个正整数<i>n, m</i>，分别表示弦的条数以及相交弦的对数，所有的弦从1至<i>n</i>编号。<br/>
　　接下来<i>m</i>行每行两个正整数<i>a ,b</i>，表示第<i>a</i>条弦与第<i>b</i>条弦相交。</div>
# 输出格式

<div class="pdcont">　　输出分为两行。<br/>
　　第一行输出<i>2n</i>个正整数，按逆时针方向给出满足题意的圆上每条弦的两个端点的相对顺序，其中第<i>i</i>条弦的两个端点均用数字<i>i</i>来表示。<br/>
　　第二行输出1个正整数，表示最多能选多少条两两不相交的弦。</div>
# 样例输入

<div class="pddata">5 6<br/>
1 2<br/>
1 3<br/>
2 3<br/>
2 4<br/>
3 5<br/>
4 5</div>
# 样例输出

<div class="pddata">1 2 3 1 4 2 5 4 3 5<br/>
2</div>
# 样例说明

<div class="pdcont"><img src="source/tsinsen/A1478/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZzZiQjZBZ04=.do" width="268" height="288"/></div>
# 数据规模和约定

<div class="pdcont">　　本题数据均为随机生成。没有在输入中出现的弦对均不相交。如果输出不合法，不得分。<br/>
　　对于10%的数据，1 ≤ n ≤ 3；<br/>
　　对于30%的数据，1 ≤ n ≤ 8；<br/>
　　对于40%的数据，1 ≤ n ≤ 12；<br/>
　　对于60%的数据，1 ≤ n ≤ 15；<br/>
　　对于75%的数据，1 ≤ n ≤ 17；<br/>
　　对于95%的数据，1 ≤ n ≤ 18；<br/>
　　对于100%的数据，1 ≤ n ≤ 20，1 ≤ m ≤ 40。</div>

</div>