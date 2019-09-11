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
排排坐，吃果果，生果甜嗦嗦，大家笑呵呵。你一个，我一个，大的分给你，小的留给我，吃完果果唱支歌，大家乐和和。<br/>
红星幼儿园的小朋友们排起了长长地队伍，准备吃果果。不过因为小朋友们的身高有所区别，排成的队伍高低错乱，极不美观。设第i个小朋友的身高为h<sub>i</sub>，我们定义一个序列的杂乱程度为：满足i&lt;j且h<sub>i</sub>&gt;h<sub>j</sub>的(i,j)数量。幼儿园阿姨每次会选出两个小朋友，交换他们的位置，请你帮忙计算出每次交换后，序列的杂乱程度。为方便幼儿园阿姨统计，在未进行任何交换操作时，你也应该输出该序列的杂乱程度。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行为一个正整数n，表示小朋友的数量；<br/>
第二行包含n个由空格分隔的正整数h<sub>1</sub>,h<sub>2</sub>,…,h<sub>n</sub>，依次表示初始队列中小朋友的身高；<br/>
第三行为一个正整数m，表示交换操作的次数；<br/>
以下m行每行包含两个正整数a<sub>i</sub>和b<sub>i­</sub>，表示交换位置a<sub>i</sub>与位置b<sub>i</sub>的小朋友。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出文件共m+1行，第i行一个正整数表示交换操作i结束后，序列的杂乱程度。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3<br/>
130 150 140<br/>
2<br/>
2 3<br/>
1 3
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
1<br/>
0<br/>
3
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
未进行任何操作时，(2,3)满足条件；<br/>
操作1结束后，序列为130 140 150，不存在满足i&lt;j且h<sub>i</sub>&gt;h<sub>j</sub>的(i,j)对；<br/>
操作2结束后，序列为150 140 130,(1,2)，(1,3)，(2,3)共3对满足条件的(i,j)。
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于15%的数据，n,m≤15；<br/>
对于30%的数据，n,m≤200；<br/>
在剩下的70%数据中：<br/>
存在15%的数据，h<sub>i</sub>各不相同；<br/>
存在15%的数据，110≤h<sub>i</sub>≤160；<br/>
以上两类数据不存在交集。<br/>
对于100%的数据，1≤m≤2*10<sup>3</sup>，1≤n≤2*10<sup>4</sup>，1≤h<sub>i</sub>≤10<sup>9</sup>，a<sub>i</sub>≠b<sub>i</sub>，1≤a<sub>i</sub>,b<sub>i</sub>≤n。
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p class="NOI">
<span style="font-family:黑体;">【问题描述】</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">排排坐，吃果果，生果甜嗦嗦，大家笑呵呵。你一个，我一个，大的分给你，小的留给我，吃完果果唱支歌，大家乐和和。</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">红星幼儿园的小朋友们排起了长长地队伍，准备吃果果。不过因为小朋友们的身高有所区别，排成的队伍高低错乱，极不美观。设第</span><span lang="EN-US">i</span><span style="font-family:宋体;">个小朋友的身高为</span><span lang="EN-US">h<sub>i</sub></span><span style="font-family:宋体;">，我们定义一个序列的杂乱程度为：满足</span><span lang="EN-US">i&lt;j</span><span style="font-family:宋体;">且</span><span lang="EN-US">h<sub>i</sub>&gt;h<sub>j</sub></span><span style="font-family:宋体;">的</span><span lang="EN-US">(i,j)</span><span style="font-family:宋体;">数量。幼儿园阿姨每次会选出两个小朋友，交换他们的位置，请你帮忙计算出每次交换后，序列的杂乱程度。为方便幼儿园阿姨统计，在未进行任何交换操作时，你也应该输出该序列的杂乱程度。</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【输入格式】</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">第一行为一个正整数</span><span lang="EN-US">n</span><span style="font-family:宋体;">，表示小朋友的数量；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">第二行包含</span><span lang="EN-US">n</span><span style="font-family:宋体;">个由空格分隔的正整数</span><span lang="EN-US">h<sub>1</sub>,h<sub>2</sub>,…,h<sub>n</sub></span><span style="font-family:宋体;">，依次表示初始队列中小朋友的身高；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">第三行为一个正整数</span><span lang="EN-US">m</span><span style="font-family:宋体;">，表示交换操作的次数；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">以下</span><span lang="EN-US">m</span><span style="font-family:宋体;">行每行包含两个正整数</span><span lang="EN-US">a<sub>i</sub></span><span style="font-family:宋体;">和</span><span lang="EN-US">b<sub>i­</sub></span><span style="font-family:宋体;">，表示交换位置</span><span lang="EN-US">a<sub>i</sub></span><span style="font-family:宋体;">与位置</span><span lang="EN-US">b<sub>i</sub></span><span style="font-family:宋体;">的小朋友。</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【输出格式】</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">输出文件共</span><span lang="EN-US">m</span><span style="font-family:宋体;">行，第</span><span lang="EN-US">i</span><span style="font-family:宋体;">行一个正整数表示交换操作</span><span lang="EN-US">i</span><span style="font-family:宋体;">结束后，序列的杂乱程度。</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例输入】</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span lang="EN-US">3</span> 
</p>
<p class="NOI1">
<span lang="EN-US">130 150 140</span> 
</p>
<p class="NOI1">
<span lang="EN-US">2</span> 
</p>
<p class="NOI1">
<span lang="EN-US">2 3</span> 
</p>
<p class="NOI1">
<span lang="EN-US">1 3</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例输出】</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span lang="EN-US">1</span> 
</p>
<p class="NOI1">
<span lang="EN-US">0</span> 
</p>
<p class="NOI1">
<span lang="EN-US">3</span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【样例说明】</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">未进行任何操作时，</span><span lang="EN-US">(2,3)</span><span style="font-family:宋体;">满足条件；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">操作</span><span lang="EN-US">1</span><span style="font-family:宋体;">结束后，序列为</span><span lang="EN-US">130 140 150</span><span style="font-family:宋体;">，不存在满足</span><span lang="EN-US">i&lt;j</span><span style="font-family:宋体;">且</span><span lang="EN-US">h<sub>i</sub>&gt;h<sub>j</sub></span><span style="font-family:宋体;">的</span><span lang="EN-US">(i,j)</span><span style="font-family:宋体;">对；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">操作</span><span lang="EN-US">2</span><span style="font-family:宋体;">结束后，序列为</span><span lang="EN-US">150 140 130,(1,2)</span><span style="font-family:宋体;">，</span><span lang="EN-US">(1,3)</span><span style="font-family:宋体;">，</span><span lang="EN-US">(2,3)</span><span style="font-family:宋体;">共</span><span lang="EN-US">3</span><span style="font-family:宋体;">对满足条件的</span><span lang="EN-US">(i,j)</span><span style="font-family:宋体;">。</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span style="font-family:黑体;">【数据规模和约定】</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">对于</span><span lang="EN-US">15%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">n,m</span><span style="font-family:宋体;">≤</span><span lang="EN-US">15</span><span style="font-family:宋体;">；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">对于</span><span lang="EN-US">30%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">n,m</span><span style="font-family:宋体;">≤</span><span lang="EN-US">200</span><span style="font-family:宋体;">；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">在剩下的</span><span lang="EN-US">70%</span><span style="font-family:宋体;">数据中：</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">存在</span><span lang="EN-US">15%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">h<sub>i</sub></span><span style="font-family:宋体;">各不相同；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">存在</span><span lang="EN-US">15%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">110</span><span style="font-family:宋体;">≤</span><span lang="EN-US">h<sub>i</sub></span><span style="font-family:宋体;">≤</span><span lang="EN-US">160</span><span style="font-family:宋体;">；</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">以上两类数据不存在交集。</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:宋体;">对于</span><span lang="EN-US">100%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">m</span><span style="font-family:宋体;">≤</span><span lang="EN-US">2*10<sup>3</sup></span><span style="font-family:宋体;">，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">n</span><span style="font-family:宋体;">≤</span><span lang="EN-US">2*10<sup>4</sup></span><span style="font-family:宋体;">，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">h<sub>i</sub></span><span style="font-family:宋体;">≤</span><span lang="EN-US">10<sup>9</sup></span><span style="font-family:宋体;">，</span><span lang="EN-US">a<sub>i</sub></span><span style="font-family:宋体;">≠</span><span lang="EN-US">b<sub>i</sub></span><span style="font-family:宋体;">，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">a<sub>i</sub>,b<sub>i</sub></span><span style="font-family:宋体;">≤</span><span lang="EN-US">n</span><span style="font-family:宋体;">。</span><span lang="EN-US"></span> 
</p>
</div>
</div>
