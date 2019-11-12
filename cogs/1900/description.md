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
墨墨的妈妈热爱炒股，她要求墨墨为她编写一个软件，预测某只股票未来的走势。<br/>
<img src="/upload/image/20141224/20141224105402_95031.png" alt=""/><br/>
股票折线图是研究股票的必备工具，它通过一张时间与股票的价位的函数图像清晰地展示了股票的走势情况。经过长时间的观测，墨墨发现很多股票都有如下的规律：之前的走势很可能在短时间内重现！如图可以看到这只股票A部分的股价和C部分的股价的走势如出一辙。通过这个观测，墨墨认为他可能找到了一个预测股票未来走势的方法。进一步的研究可是难住了墨墨，他本想试图统计B部分的长度与发生这种情况的概率关系，不过由于数据量过于庞大，依赖人脑的力量难以完成，于是墨墨找到了善于编程的你，请你帮他找一找给定重现的间隔（B部分的长度），有多少个时间段满足首尾部分的走势完全相同呢？当然，首尾部分的长度不能为零。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含两个整数N、M，分别表示需要统计的总时间以及重现的间隔（B部分的长度）。<br/>
接下来N行，每行一个整数，代表每一个时间点的股价。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示满足条件的时间段的个数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
12 4<br/>
1 2 3 4 8 9 1 2 3 4 8 9
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
6
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
6个时间段分别是：3-9、2-10、2-8、1-9、3-11、4-12。
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于20%的数据， 4≤N≤100。<br/>
对于40%的数据， 4≤N≤5000。<br/>
对于100%的数据，4≤N≤50000 1≤M≤10  M≤N 所有出现的整数均不超过32位含符号整数。<br/>
时间限制：1s。
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<div class="pdsec">
问题描述
</div>
<div class="pdcont">
墨墨的妈妈热爱炒股，她要求墨墨为她编写一个软件，预测某只股票未来的走势。
</div>
<div class="pdcont">
<img width="254" height="131" alt="" src="/RequireFile.do?fid=YL5nfLqr"/><br/>
股票折线图是研究股票的必备工具，它通过一张时间与股票的价位的函数图像清晰地展示了股票的走势情况。经过长时间的观测，墨墨发现很多股票都有如下的规律：之前的走势很可能在短时间内重现！如图可以看到这只股票A部分的股价和C部分的股价的走势如出一辙。通过这个观测，墨墨认为他可能找到了一个预测股票未来走势的方法。进一步的研究可是难住了墨墨，他本想试图统计B部分的长度与发生这种情况的概率关系，不过由于数据量过于庞大，依赖人脑的力量难以完成，于是墨墨找到了善于编程的你，请你帮他找一找给定重现的间隔（B部分的长度），有多少个时间段满足首尾部分的走势完全相同呢？当然，首尾部分的长度不能为零。
</div>
<div class="pdsec">
输入格式
</div>
<div class="pdcont">
输入的第一行包含两个整数N、M，分别表示需要统计的总时间以及重现的间隔（B部分的长度）。<br/>
接下来N行，每行一个整数，代表每一个时间点的股价。
</div>
<div class="pdsec">
输出格式
</div>
<div class="pdcont">
输出一个整数，表示满足条件的时间段的个数。
</div>
<div class="pdsec">
样例输入
</div>
<div class="pddata">
12 4<br/>
1 2 3 4 8 9 1 2 3 4 8 9
</div>
<div class="pdsec">
样例输出
</div>
<div class="pddata">
6
</div>
<div class="pdsec">
样例说明
</div>
<div class="pdcont">
6个时间段分别是：3-9、2-10、2-8、1-9、3-11、4-12。
</div>
<div class="pdsec">
数据范围
</div>
<div class="pdcont">
对于20%的数据， 4≤N≤100。<br/>
对于40%的数据， 4≤N≤5000。<br/>
对于100%的数据，4≤N≤50000 1≤M≤10  M≤N 所有出现的整数均不超过32位含符号整数。<br/>
时间限制：1s。
</div>
</div>
</div>
