# 题目描述


<h1>
<a name="_Toc241035975"></a><span style="font-family:宋体;">问题描述</span>
</h1>
<p class="MsoNormal">
<span style="font-family:宋体;">艾泽拉斯世界经历一场亘古未有的地震过后，大地和海洋被完全撕裂，旧大陆残缺不全。联盟和部落各种族的居民们被迫离开了世代居住的家园，来寻找新的生存空间。原本平坦的陆地上现在隆起了一座座山峰，暴风城的人类开始在<u>艾尔文山脉</u>重建家园。他们决定在山脉之中建造一座<u>瞭望塔</u>和一个魔法<u>浮空岛</u>，以便于在<u>瞭望塔</u>和<u>浮空岛</u>上可以俯视<u>艾尔文山脉</u>的全貌。</span>
</p>
<p class="MsoNormal">
<u><span style="font-family:宋体;">艾尔文山脉</span></u><span style="font-family:宋体;">被描述为一个折线，给定每个点的坐标（横纵坐标均不小于</span><span lang="EN-US">0</span><span style="font-family:宋体;">），按照横坐标从小到大顺次连接起来就是就是山脉的折线。折线上所有点的横坐标均不相同。如果一个位置与山脉任何一点的连线均不被挡住（但可以与地面相切），那么就说这一点可以望到整个<u>艾尔文山脉</u>。<u>瞭望塔</u>的塔身不会挡住视线，而且<u>瞭望塔</u>和<u>浮空岛</u>可以建造在同一位置。为节省建筑材料，<u>瞭望塔</u>塔身的高度必须尽量小，即从塔顶到塔底的距离尽量小，瞭望塔可以建在山坡上。由于气候因素，<u>浮空岛</u>应建立在海拔尽量低的位置（甚至可以建在地面上），海平面高度为</span><span lang="EN-US">0</span><span style="font-family:宋体;">。如果有多个位置均满足条件，则选择横坐标最小的那个。<u>瞭望塔</u>和<u>浮空岛</u>横坐标范围应在<u>艾尔文山脉</u>横坐标范围之内。给定<u>艾尔文山脉</u>，请你求出<u>瞭望塔</u>和<u>浮空岛</u>的位置。</span>
</p>
<h1>
<span style="font-family:宋体;">输入文件</span>
</h1>
<p class="MsoNormal">
<span style="font-family:宋体;">文件名</span><span lang="EN-US">cataclysm.in</span>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;">第</span><span lang="EN-US">1</span><span style="font-family:宋体;">行，一个整数</span><span lang="EN-US">N</span><span style="font-family:宋体;">，表示描述<u>艾尔文山脉</u>的折线的顶点数。</span>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;">第</span><span lang="EN-US">2-N+1</span><span style="font-family:宋体;">行，每行两个整数，</span><span lang="EN-US">xi</span><span style="font-family:宋体;">，</span><span lang="EN-US">yi</span><span style="font-family:宋体;">表示折线上点的坐标。</span>
</p>
<h1>
<span style="font-family:宋体;">输出文件</span>
</h1>
<p class="MsoNormal">
<span style="font-family:宋体;">文件名</span><span lang="EN-US">cataclysm.out</span>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;">第</span><span lang="EN-US">1</span><span style="font-family:宋体;">行，两个保留</span><span lang="EN-US">2</span><span style="font-family:宋体;">位小数的浮点数</span><span lang="EN-US">x1,y1</span><span style="font-family:宋体;">，表示<u>瞭望塔</u>顶端的坐标。</span>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;">第</span><span lang="EN-US">2</span><span style="font-family:宋体;">行，两个保留</span><span lang="EN-US">2</span><span style="font-family:宋体;">位小数的浮点数</span><span lang="EN-US">x2,y2</span><span style="font-family:宋体;">，表示<u>浮空岛</u>的坐标。</span>
</p>
<h1>
<span style="font-family:宋体;">输入样例</span>
</h1>
<p class="MsoNormal">
<span lang="EN-US">6</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">2 2</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">6 1</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">8 6</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">10 3</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">16 5</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">20 2</span>
</p>
<h1>
<span style="font-family:宋体;">输出样例</span>
</h1>
<p class="MsoNormal">
<span lang="EN-US">8.00 11.00</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">9.54 9.85</span>
</p>
<h1>
<span style="font-family:宋体;">样例说明</span>
</h1>
<p class="MsoNormal">
<span style="font-family:宋体;">样例中描述的<u>艾尔文山脉</u>各个顶点，按照横坐标顺序顺次连接后的折线如下图所示：</span>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;"><img alt="" src="/images/cataclysm1.png" width="601" height="173"/></span>
</p>
<p class="MsoNormal">
<span lang="EN-US"><br/>
</span>
</p>
<p class="MsoNormal">
<u><span style="font-family:宋体;">瞭望塔</span></u><span style="font-family:宋体;">应建造在山峰</span><span lang="EN-US">(8,6)</span><span style="font-family:宋体;">处，塔顶端为</span><span lang="EN-US">(8,11)</span><span style="font-family:宋体;">，高度为</span><span lang="EN-US">5</span><span style="font-family:宋体;">，此时<u>瞭望塔</u>的高度最小。</span>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;"><img alt="" src="/images/cataclysm2.png" width="601" height="248"/></span>
</p>
<p class="MsoNormal">
<span lang="EN-US"><br/>
</span>
</p>
<p class="MsoNormal">
<u><span style="font-family:宋体;">浮空岛</span></u><span style="font-family:宋体;">建立在</span><span lang="EN-US">(9.54,9.85)</span><span style="font-family:宋体;">处，海拔高度最低。</span>
</p>
<p class="MsoNormal">
<span lang="EN-US"><img alt="" src="/images/cataclysm3.png" width="601" height="232"/><br/>
</span>
</p>
<h1>
<span style="font-family:宋体;">问题限制</span>
</h1>
<p class="MsoNormal">
<b><span style="font-family:宋体;">数据规模</span></b>
</p>
<p class="MsoNormal">
<span lang="EN-US">40%</span><span style="font-family:宋体;">的数据</span><span lang="EN-US">2&lt;=N&lt;=10</span>
</p>
<p class="MsoNormal">
<span lang="EN-US">100%</span><span style="font-family:宋体;">的数据</span><span lang="EN-US">2&lt;=N&lt;=1 000 000</span><span style="font-family:宋体;">；</span><span lang="EN-US">0&lt;=xi,yi&lt;=5 000 000</span>
</p>
