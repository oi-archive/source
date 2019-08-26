
# Description

<div class="content"><div>For Bessie the cow’s birthday, Farmer John has given her free reign over one of his best fields to eat grass.</div>
<div>The field is covered in N patches of grass (1≤N≤1000), conveniently numbered 1…N, that each have a distinct</div>
<div>quality value. If Bessie eats grass of quality Q, she gains Q units of energy. Each patch is connected to up to 10</div>
<div>neighboring patches via bi-directional paths, and it takes Bessie E units of energy to move between adjacent</div>
<div>patches (1≤E≤1,000,000). Bessie can choose to start grazing in any patch she wishes, and she wants to stop</div>
<div>grazing once she has accumulated a maximum amount of energy.</div>
<div>Unfortunately, Bessie is a picky bovine, and once she eats grass of a certain quality, she’ll never eat grass at or</div>
<div>below that quality level again! She is still happy to walk through patches without eating their grass; in fact, she</div>
<div>might find it beneficial to walk through a patch of high-quality grass without eating it, only to return later for a tasty snack.</div>
<div>Please help determine the maximum amount of energy Bessie can accumulate.</div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">为了庆祝贝茜的生日,FJ给她吃草的自由. N块草地,标号1到N(1&lt;=N&lt;=1000),草地有营养价值.当贝茜走到这个草地,可以获得等于这块草地的营养价值的能量. 每块草地最多有10条双向边,每走一条边,贝茜花费E的能量. 贝茜拿可以从任何地方出发,当她不能获得更多的能量的时候她就会停止. 然而因为贝茜挑食,她每次不会吃低于或等于上次的营养价值的草地,所以她获得的能量是严格上升的,当然她可以选择只是经过一块草地而不吃草.</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">算出贝茜能够获得的最大能量.</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div>
</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N and E. Each of the remaining N lines describe a patch of grass.</div>
<div>They contain two integers Q and D giving the quality of the patch (in the range 1…1,000,000) and</div>
<div>its number of neighbors. The remaining D numbers on the line specify the neighbors.</div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">第一排两个数 N和E</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">剩下N排,每排包含Q,D两个数字,Q代表这个草地的营养价值,D代表这个点的边数,剩下D个数表示于这块草地相邻的草地.</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output the maximum amount of energy Bessie can accumulate.</div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">一个整数</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">最大权值</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
4 1 2<br/>
1 3 1 3 4<br/>
6 2 2 5<br/>
5 2 2 5<br/>
2 2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
Bessie starts at patch 4 gaining 5 units of energy from the grass there. She then takes the path to patch 5 losing 2 units of energy during her travel. She refuses to eat the lower quality grass at patch 5 and travels to patch 3 again losing 2 units of energy. Finally she eats the grass at patch 3 gaining 6 units of energy for a total of 7 energy.<br/>
Note tha the sample case above is different from test case 1 when you submit.<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 求译文!请发至lydsy2012@163.com</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver 鸣谢yeguanghao提供译文">Silver 鸣谢yeguanghao提供译文</a></p></div>

