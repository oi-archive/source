# 题目描述


<p>
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
</p><h3>
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
<div class="pddata" id="inputlist">
</div>
</div>
<p>
</p><h3>
【问题描述】
</h3>
<div class="pdcont">
墨墨购买了一套N支彩色画笔（其中有些颜色可能相同），摆成一排，你需要回答墨墨的提问。墨墨会像你发布如下指令：<br/>
1、	Q L R代表询问你从第L支画笔到第R支画笔中共有几种不同颜色的画笔。<br/>
2、	R P Col 把第P支画笔替换为颜色Col。<br/>
为了满足墨墨的要求，你知道你需要干什么了吗？
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第1行两个整数N，M，分别代表初始画笔的数量以及墨墨会做的事情的个数。<br/>
第2行N个整数，分别代表初始画笔排中第i支画笔的颜色。<br/>
第3行到第2+M行，每行分别代表墨墨会做的一件事情，格式见题干部分。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
对于每一个Query的询问，你需要在对应的行中给出一个数字，代表第L支画笔到第R支画笔中共有几种不同颜色的画笔。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
6 5<br/>
1 2 3 4 5 5<br/>
Q 1 4<br/>
Q 2 6<br/>
R 1 2<br/>
Q 1 4<br/>
Q 2 6
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
4<br/>
4<br/>
3<br/>
4
</div>
<h3>
【数据规模和约定】
</h3>
<p>
对于40%数据，只包含第一类操作（无修改操作），且。
</p>
<p>
除此之外的20%的数据，N，M≤1000
</p>
<p>
对于100%的数据，N≤10000，M≤10000，修改操作不多于1000次，所有的输入数据中出现的所有整数均大于等于1且不超过10^6。
</p>
<p>
时间限制：0.6s
</p>
<p></p>
<div id="pcont2" style="margin-top:20px;display:none;">
<div class="pdsec">
问题描述
</div>
<div class="pdcont">
墨墨购买了一套N支彩色画笔（其中有些颜色可能相同），摆成一排，你需要回答墨墨的提问。墨墨会像你发布如下指令：<br/>
1、	Q L R代表询问你从第L支画笔到第R支画笔中共有几种不同颜色的画笔。<br/>
2、	R P Col 把第P支画笔替换为颜色Col。<br/>
为了满足墨墨的要求，你知道你需要干什么了吗？
</div>
<div class="pdsec">
输入格式
</div>
<div class="pdcont">
第1行两个整数N，M，分别代表初始画笔的数量以及墨墨会做的事情的个数。<br/>
第2行N个整数，分别代表初始画笔排中第i支画笔的颜色。<br/>
第3行到第2+M行，每行分别代表墨墨会做的一件事情，格式见题干部分。
</div>
<div class="pdsec">
输出格式
</div>
<div class="pdcont">
对于每一个Query的询问，你需要在对应的行中给出一个数字，代表第L支画笔到第R支画笔中共有几种不同颜色的画笔。
</div>
<div class="pdsec">
样例输入
</div>
<div class="pddata">
6 5<br/>
1 2 3 4 5 5<br/>
Q 1 4<br/>
Q 2 6<br/>
R 1 2<br/>
Q 1 4<br/>
Q 2 6
</div>
<div class="pdsec">
样例输出
</div>
<div class="pddata">
4<br/>
4<br/>
3<br/>
4
</div>
<div class="pdsec">
数据范围
</div>
<div class="pdcont">
对于40%数据，只包含第一类操作（无修改操作），且。
除此之外的20%的数据，N，M≤1000
对于100%的数据，N≤10000，M≤10000，修改操作不多于1000次，所有的输入数据中出现的所有整数均大于等于1且不超过106。
时间限制：0.6s
</div>
</div>
<p></p>
