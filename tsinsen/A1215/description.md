<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　艾泽拉斯世界经历一场亘古未有的地震过后，大地和海洋被完全撕裂，旧大陆残缺不全。联盟和部落各种族的居民们被迫离开了世代居住的家园，来寻找新的生存空间。原本平坦的陆地上现在隆起了一座座山峰，暴风城的人类开始在艾尔文山脉重建家园。他们决定在山脉之中建造一座瞭望塔和一个魔法浮空岛，以便于在瞭望塔和浮空岛上可以俯视艾尔文山脉的全貌。<br/>
　　艾尔文山脉被描述为一个折线，给定每个点的坐标（横纵坐标均不小于0），按照横坐标从小到大顺次连接起来就是就是山脉的折线。折线上所有点的横坐标均不相同。如果一个位置与山脉任何一点的连线均不被挡住（但可以与地面相切），那么就说这一点可以望到整个艾尔文山脉。瞭望塔的塔身不会挡住视线，而且瞭望塔和浮空岛可以建造在同一位置。为节省建筑材料，瞭望塔塔身的高度必须尽量小，即从塔顶到塔底的距离尽量小，瞭望塔可以建在山坡上。由于气候因素，浮空岛应建立在海拔尽量低的位置（甚至可以建在地面上），海平面高度为0。如果有多个位置均满足条件，则选择横坐标最小的那个。瞭望塔和浮空岛横坐标范围应在艾尔文山脉横坐标范围之内。给定艾尔文山脉，请你求出瞭望塔和浮空岛的位置。</div>
# 输入格式

<div class="pdcont">　　第1行，一个整数N，表示描述艾尔文山脉的折线的顶点数。<br/>
　　第2-N+1行，每行两个整数，xi，yi表示折线上点的坐标。</div>
# 输出格式

<div class="pdcont">　　第1行，两个保留3位小数的浮点数x1,y1，表示瞭望塔顶端的坐标。<br/>
　　第2行，两个保留3位小数的浮点数x2,y2，表示浮空岛的坐标。</div>
# 样例输入

<div class="pddata">6<br/>
2 2<br/>
6 1<br/>
8 6<br/>
10 3<br/>
16 5<br/>
20 2</div>
# 样例输出

<div class="pddata">8.00 11.00<br/>
9.54 9.85</div>
# 样例说明

<div class="pdcont">　　样例中描述的艾尔文山脉各个顶点，按照横坐标顺序顺次连接后的折线如下图所示：<br/>
<img width="677" height="176" src="source/tsinsen/A1215/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OGZGOUVHbmI=.do"/><br/>
<br/>
　　瞭望塔应建造在山峰(8,6)处，塔顶端为(8,11)，高度为5，此时瞭望塔的高度最小。<br/>
<img width="939" height="387" src="source/tsinsen/A1215/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TTk4MjI0Zk4=.do"/><br/>
<br/>
　　浮空岛建立在(9.54,9.85)处，海拔高度最低。<br/>
<br/>
<img width="939" height="363" src="source/tsinsen/A1215/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NDlmQTVNSGU=.do"/></div>
# 数据规模和约定

<div class="pdcont">　　40%的数据2&lt;=N&lt;=10<br/>
　　100%的数据2&lt;=N&lt;=1 000 000；0&lt;=xi,yi&lt;=5 000 000</div>
# 评分方式

<div class="pdcont">　　对于每个测试点，如果输出的结果与答案文件完全相同，得该测试点100%的分数，如果仅有一行与答案文件相同，得该测试点50%的分数，否则得0%的分数。</div>

</div>