# 题目描述


<p>
<span style="font-family:宋体;"><b>问题描述</b></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;"><br/>
</span>请设计一个程序模拟队列，具备入队、出队、置队列为空、输出队列数据的功能。 (队列容量为10,即最多有10个元素在一个队中。)
</p>
<p class="MsoNormal">
【输入格式】
</p>
<p class="MsoNormal">
<span lang="EN-US">输入由若干行组成：</span> 
</p>
<p class="MsoNormal">
<span lang="EN-US">第一行有一个整数，n（1≤n≤2000）；n表示对队列进行操作的次数。</span> 
</p>
<p class="MsoNormal">
<span lang="EN-US">第2--n+1</span><span lang="EN-US">行表示n种操作信息。第行第一个整数代表操作的类型：</span><span lang="EN-US">1表示置队列为空操作，2表示入队操作，3表示出队操作、4表示输出队列信息。</span> 
</p>
<p class="MsoNormal">
对于<span lang="EN-US">置队列为空</span>操作：无论队列中有无元素，有多少元素，都将队列置为空。
</p>
<p class="MsoNormal">
对于入队操作：该行第二个整数表示入队数据，如果队列已满，显示queue out。
</p>
<p class="MsoNormal">
对于出队操作：正常删除队首元素，如果队列中已无任何元素，显示queue empty。
</p>
<p class="MsoNormal">
对于输出操作：第一行输出队列中元素个数，第二行按从队首到队尾的顺序输出队内所有元素。
</p>
<p class="MsoNormal">
<span lang="EN-US"><o:p></o:p></span>【输出格式】
</p>
<p class="MsoNormal">
<span lang="EN-US">根据不同的操作，输出不同的操作信息。</span> 
</p>
<p class="MsoNormal">
入队、出队和置队列为空操作如无操作错误（队列溢出等），无输出信息。输出操作：第一行输出队列中元素个数，第二行按从队首到队尾的顺序输出队内所有元素。
</p>
<p class="MsoNormal">
【输入输出样例】
</p>
<p class="MsoNormal">
输入文件名：<span class="SpellE"> queue.in</span> 
</p>
<p class="MsoNormal">
6<br/>
1 <br/>
2 78<br/>
2 88<br/>
2 99<br/>
3<br/>
4
</p>
<p class="MsoNormal">
输出文件名：<span class="SpellE"><span lang="EN-US">queue.out</span></span> 
</p>
<p class="MsoNormal">
<span lang="EN-US"><span lang="EN-US">2 <br/>
88 99 </span></span> 
</p>
