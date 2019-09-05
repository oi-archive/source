# 题目描述


<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">来源：1) </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><a href="http://acmpj.zstu.edu.cn/JudgeOnline/showproblem?problem_id=2579" target="_blank">浙江理工大学 2579 </a></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">    2) </span><a href="http://acm.sdut.edu.cn/sdutoj/problem.php?action=showproblem&amp;problemid=1402" target="_blank"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">山东理工大学 1402</span></a> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【问题描述】</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">很久以前，有一个医术非常高明的医生，曾经医治好了很多怪病。但是，他开出的药方的字迹却是十分难辨认的，只有他自己和他自己的药剂师才能够读懂他的药方。有时候，甚至是两个不同的药方的同一种药都是难以鉴别出的。</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">不过，这个医生在开药方的时候，习惯有一个固定的标准模式。他有一个药材库，里面共有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">种药，除了这</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">种药，他不会使用任何其他的药。对于每一种药，都有一个关于它的后续药的集合，只有这种药的后续药才能够直接出现在这种药的下一个位置。当然，任何一种药都可能同时是几种药的后续药。</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">这个医生开出的药方是一个列表的形式。在他的一个药方中，一种药只可能出现一次。更奇怪的是，当他开出一种药和它的后续药以后，这种药的其他后续药就不可能出现在之后的序列中。</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">后来，一些<span style="color:#337FE5;">书法家</span>和医生共同分析了这个医生的大量的药方，写出了他的所有药的清单。这里我们用</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">个</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，…，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">来依次表示他的</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">种药。同时，他们也分析出了每一种药的可能的后续药的药单。</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">现在，有一个关于这个医生的药方，药方中写有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">p</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">种药。可惜的是，药方中有一些药并没有具体辨别出。那么，请你写一个程序，帮忙辨别出药方中不确认的药。当然，对于不确定的药方，可能可以构造出多种不同的药方，那么请你找出所有的情况。</span> 
</p>
<p style="text-indent:24pt;">
<span> </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入】</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入格式</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入文件名</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">doctor</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">．</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">in)</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行只有一个正整数</span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n(O</span><n< span=""><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">500)</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，表示所有药的总数。在接下来的</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行中，每行有若干个数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">中间用空格分开</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">)</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">i</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行表示的是第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">i</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">种药的后续药的集合。</span></n<></span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">再接下来的一行，又有一个正整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">p</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，表示具体的一个药方的药的数目。继续下来的</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">p</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行，每行有一个整数，表示这个</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">药方第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">i</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">个</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">药被鉴别出是</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">k</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">；如果</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">k</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">0</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，表示这个药还没有鉴别出来。</span> 
</p>
<p style="text-indent:24pt;">
<span> </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出】</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出格式</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出文件名</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">doctor</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">．</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">out)</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">、</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行是一个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">m</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，表示总共可以构造出</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">m</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">种不同的药方。</span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">接下来的</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">m</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行，每行应该有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">p</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">个数，具体输出每一种情况的药方，中间用一个空格</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">格</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">开。所有的</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">m</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行的输出，必须按照整数排序顺序输出。行首行末无空格。</span> 
</p>
<p style="text-indent:24pt;">
<span></span><span> </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入输出样例】</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入</span> 
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 4 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 1 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 1 2 
4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 0</span> 
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 3 5 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 4 3 5 1</span> 
</p>
