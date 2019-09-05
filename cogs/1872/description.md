# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
一年一度的圣诞节快要来到了。每年的圣诞节小E都会收到许多礼物，当然他也会送出许多礼物。不同的人物在小E心目中的重要性不同，在小E心中分量越重的人，收到的礼物会越多。小E从商店中购买了n件礼物，打算送给m个人，其中送给第i个人礼物数量为w<sub>i</sub>。请你帮忙计算出送礼物的方案数（两个方案被认为是不同的，当且仅当存在某个人在这两种方案中收到的礼物不同）。由于方案数可能会很大，你只需要输出模P后的结果。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含一个正整数P，表示模；<br/>
第二行包含两个整整数n和m，分别表示小E从商店购买的礼物数和接受礼物的人数；<br/>
以下m行每行仅包含一个正整数w<sub>i</sub>，表示小E要送给第i个人的礼物数量。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
若不存在可行方案，则输出“Impossible”，否则输出一个整数，表示模P后的方案数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
100<br/>
4 2<br/>
1<br/>
2
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
12
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
100<br/>
2 2<br/>
1<br/>
2
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
Impossible
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
下面是对样例1的说明。<br/>
以“/”分割，“/”前后分别表示送给第一个人和第二个人的礼物编号。12种方案详情如下：<br/>
1/23 1/24 1/34<br/>
2/13 2/14 2/34<br/>
3/12 3/14 3/24<br/>
4/12 4/13 4/23
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
设P=p<sub>1</sub>^c<sub>1</sub> * p<sub>2</sub>^c<sub>2</sub> * p<sub>3</sub>^c<sub>3</sub> * … *p<sub>t</sub> ^ c<sub>t</sub>，p<sub>i</sub>为质数。<br/>
对于15%的数据，n≤15，m≤5，p<sub>i</sub>^c<sub>i</sub>≤10<sup>5</sup>；<br/>
在剩下的85%数据中，约有60%的数据满足t≤2，c<sub>i</sub>=1，p<sub>i</sub>≤10<sup>5</sup>，约有30%的数据满足p<sub>i</sub>≤200。<br/>
对于100%的数据，1≤n≤10<sup>9</sup>，1≤m≤5，1≤p<sub>i</sub>^c<sub>i</sub>≤10<sup>5，1</sup>≤P≤10<sup>9</sup>。
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p class="NOI">
<span style="font-family:黑体;">【问题描述】</span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">一年一度的圣诞节快要来到了。每年的圣诞节小</span><span lang="EN-US">E</span><span style="font-family:宋体;">都会收到许多礼物，当然他也会送出许多礼物。不同的人物在小</span><span lang="EN-US">E</span><span style="font-family:宋体;">心目中的重要性不同，在小</span><span lang="EN-US">E</span><span style="font-family:宋体;">心中分量越重的人，收到的礼物会越多。小</span><span lang="EN-US">E</span><span style="font-family:宋体;">从商店中购买了</span><span lang="EN-US">n</span><span style="font-family:宋体;">件礼物，打算送给</span><span lang="EN-US">m</span><span style="font-family:宋体;">个人，其中送给第</span><span lang="EN-US">i</span><span style="font-family:宋体;">个人礼物数量为</span><span lang="EN-US">w<sub>i</sub></span><span style="font-family:宋体;">。请你帮忙计算出送礼物的方案数（两个方案被认为是不同的，当且仅当存在某个人在这两种方案中收到的礼物不同）。由于方案数可能会很大，你只需要输出模</span><span lang="EN-US">P</span><span style="font-family:宋体;">后的结果。</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【输入格式】</span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">输入的第一行包含一个正整数</span><span lang="EN-US">P</span><span style="font-family:宋体;">，表示模；</span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">第二行包含两个整整数</span><span lang="EN-US">n</span><span style="font-family:宋体;">和</span><span lang="EN-US">m</span><span style="font-family:宋体;">，分别表示小</span><span lang="EN-US">E</span><span style="font-family:宋体;">从商店购买的礼物数和接受礼物的人数；</span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">以下</span><span lang="EN-US">m</span><span style="font-family:宋体;">行每行仅包含一个正整数</span><span lang="EN-US">w<sub>i</sub></span><span style="font-family:宋体;">，表示小</span><span lang="EN-US">E</span><span style="font-family:宋体;">要送给第</span><span lang="EN-US">i</span><span style="font-family:宋体;">个人的礼物数量。</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【输出格式】</span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">若不存在可行方案，则输出“</span><span lang="EN-US">Impossible”</span><span style="font-family:宋体;">，否则输出一个整数，表示模</span><span lang="EN-US">P</span><span style="font-family:宋体;">后的方案数。</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例输入</span><span lang="EN-US">1</span><span style="font-family:黑体;">】</span> 
</p>
<p class="NOI1">
<span lang="EN-US">100</span> 
</p>
<p class="NOI1">
<span lang="EN-US">4 2</span> 
</p>
<p class="NOI1">
<span lang="EN-US">1</span> 
</p>
<p class="NOI1">
<span lang="EN-US">2</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例输出</span><span lang="EN-US">1</span><span style="font-family:黑体;">】</span> 
</p>
<p class="NOI1">
<span lang="EN-US">12</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例输入</span><span lang="EN-US">2</span><span style="font-family:黑体;">】</span> 
</p>
<p class="NOI1">
<span lang="EN-US">100</span> 
</p>
<p class="NOI1">
<span lang="EN-US">2 2</span> 
</p>
<p class="NOI1">
<span lang="EN-US">1</span> 
</p>
<p class="NOI1">
<span lang="EN-US">2</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例输出</span><span lang="EN-US">2</span><span style="font-family:黑体;">】</span> 
</p>
<p class="NOI1">
<span lang="EN-US">Impossible</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例说明】</span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">下面是对样例</span><span lang="EN-US">1</span><span style="font-family:宋体;">的说明。</span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">以“</span><span lang="EN-US">/</span><span style="font-family:宋体;">”分割，“</span><span lang="EN-US">/</span><span style="font-family:宋体;">”前后分别表示送给第一个人和第二个人的礼物编号。</span><span lang="EN-US">12</span><span style="font-family:宋体;">种方案详情如下：</span> 
</p>
<p class="NOI0">
<span lang="EN-US">1/23 1/24 1/34</span> 
</p>
<p class="NOI0">
<span lang="EN-US">2/13 2/14 2/34</span> 
</p>
<p class="NOI0">
<span lang="EN-US">3/12 3/14 3/24</span> 
</p>
<p class="NOI0">
<span lang="EN-US">4/12 4/13 4/23 </span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【数据规模和约定】</span> 
</p>
<p class="NOI0" style="text-indent:21pt;">
<span style="font-family:宋体;">设</span><span lang="EN-US">P=p<sub>1</sub>^c<sub>1</sub> * p<sub>2</sub>^c<sub>2</sub> * p<sub>3</sub>^c<sub>3</sub> * … *p<sub>t</sub> ^ c<sub>t</sub></span><span style="font-family:宋体;">，</span><span lang="EN-US">p<sub>i</sub></span><span style="font-family:宋体;">为质数。</span> 
</p>
<p class="NOI0" style="text-indent:21pt;">
<span style="font-family:宋体;">对于</span><span lang="EN-US">15%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">n</span><span style="font-family:宋体;">≤</span><span lang="EN-US">15</span><span style="font-family:宋体;">，</span><span lang="EN-US">m</span><span style="font-family:宋体;">≤</span><span lang="EN-US">5</span><span style="font-family:宋体;">，</span><span lang="EN-US">p<sub>i</sub>^c<sub>i</sub></span><span style="font-family:宋体;">≤</span><span lang="EN-US">10<sup>5</sup></span><span style="font-family:宋体;">；</span> 
</p>
<p class="NOI0" style="text-indent:21pt;">
<span style="font-family:宋体;">在剩下的</span><span lang="EN-US">85%</span><span style="font-family:宋体;">数据中，约有</span><span lang="EN-US">60%</span><span style="font-family:宋体;">的数据满足</span><span lang="EN-US">t</span><span style="font-family:宋体;">≤</span><span lang="EN-US">2</span><span style="font-family:宋体;">，</span><span lang="EN-US">c<sub>i</sub>=1</span><span style="font-family:宋体;">，</span><span lang="EN-US">p<sub>i</sub></span><span style="font-family:宋体;">≤</span><span lang="EN-US">10<sup>5</sup></span><span style="font-family:宋体;">，约有</span><span lang="EN-US">30%</span><span style="font-family:宋体;">的数据满足</span><span lang="EN-US">p<sub>i</sub></span><span style="font-family:宋体;">≤</span><span lang="EN-US">200</span><span style="font-family:宋体;">。</span> 
</p>
<p class="NOI0" style="text-indent:21pt;">
<span style="font-family:宋体;">对于</span><span lang="EN-US">100%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">n</span><span style="font-family:宋体;">≤</span><span lang="EN-US">10<sup>9</sup></span><span style="font-family:宋体;">，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">m</span><span style="font-family:宋体;">≤</span><span lang="EN-US">5</span><span style="font-family:宋体;">，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">p<sub>i</sub>^c<sub>i</sub></span><span style="font-family:宋体;">≤</span><span lang="EN-US">10<sup>5，1</sup></span><span class="Apple-style-span" style="font-family:宋体;">≤P</span><span class="Apple-style-span" style="font-family:宋体;">≤10</span><sup>9</sup><span class="Apple-style-span" style="font-family:宋体;">。</span> 
</p>
<p class="NOI0" style="text-indent:21pt;">
 
</p>
</div>
</div>
