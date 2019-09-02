
<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->

# 试题来源


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

# 问题描述


<div class="pdcont">
话说Nan在海边等人，预计还要等上M分钟。为了打发时间，他玩起了石子。<br/>
Nan搬来了N堆石子，编号为1到N，每堆包含Ai颗石子。<br/>
每1分钟，Nan会在编号在[Li,Ri]之间的石堆中挑出任意Ki颗扔向大海（好疼的玩法），如果[Li,Ri]剩下石子不够Ki颗，则取尽量地多。<br/>
为了保留扔石子的新鲜感，Nan保证任意两个区间[Li,Ri]和[Lj,Rj] ，不会存在Li&lt;=Lj &amp; Rj&lt;=Ri的情况，即任意两段区间不存在包含关系。<br/>
可是，如果选择不当，可能无法扔出最多的石子，这时NN就会不高兴了。所以他希望制定一个计划，他告诉你他m分钟打算扔的区间[Li,Ri]以及Ki。<br/>
现在他想你告诉他，在满足前i-1分钟都取到你回答的颗数的情况下，第i分钟最多能取多少个石子。
</div>

# 输入格式


<div class="pdcont">
第一行正整数N，表示石子的堆数；<br/>
第二行正整数x,y,z,P，(1&lt;=x,y,z&lt;=N;P&lt;=500)<br/>
有等式A[i]=[(i-x)^2+(i-y)^2+(i-z)^2] mod P；<br/>
第三行正整数M，表示有M分钟；<br/>
第四行正整数K[1],K[2],x,y,z,P，(x,y,z&lt;=1000;P&lt;=10000)<br/>
有等式K[i]=(x*K[i-1]+y*K[i-2]+z)mod P。<br/>
接下来M行，每行两个正整数L[i],R[i]。
</div>

# 输出格式


<div class="pdcont">
有M行，第i行表示第i分钟最多能取多少石子。
</div>

# 样例输入


<div class="pddata">
5<br/>
3 2 4 7<br/>
3<br/>
2 5 2 6 4 9<br/>
2 4<br/>
1 2<br/>
3 5
</div>

# 样例输出


<div class="pddata">
2<br/>
5<br/>
5
</div>

# 样例说明


<div class="pdcont">
石子每堆个数分别为0,5,2,5,0。<br/>
第1分钟，从第2到第4堆中选2个；<br/>
第2分钟，从第1到第2堆中选5个；<br/>
第3分钟，从第3到第5堆中选8个，但最多只能选5个。
</div>

# 数据规模和约定


<div class="pdcont">
20%   N&lt;=10<br/>
50%   N&lt;=2000<br/>
100%  N&lt;=40000   M&lt;=N   1&lt;=L[i]&lt;=R[i]&lt;=N   A[i]&lt;=500
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;">【问题描述】</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    话说</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Nan</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">在海边等人，预计还要等上</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟。为了打发时间，他玩起了石子。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>Nan</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">搬来了</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">堆石子，编号为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，每堆包含</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Ai</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">颗石子。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">每</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Nan</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">会在编号在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">[Li,Ri]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">之间的石堆中挑出任意</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Ki</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">颗扔向大海（好疼的玩法），如果</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">[Li,Ri]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">剩下石子不够</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Ki</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">颗，则取尽量地多。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>为了保留扔石子的新鲜感，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Nan</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">保证任意两个区间</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">[Li,Ri]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">[Lj,Rj] </span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，不会存在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Li&lt;=Lj &amp; Rj&lt;=Ri</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的情况，即任意两段区间不存在包含关系。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>可是，如果选择不当，可能无法扔出最多的石子，这时</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">NN</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">就会不高兴了。所以他希望制定一个计划，他告诉你他</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">m</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟打算扔的区间</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">[Li,Ri]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">以及</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Ki</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>现在他想你告诉他，在满足前</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i-1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟都取到你回答的颗数的情况下，第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟最多能取多少个石子。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;">【输入格式】</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第一行正整数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，表示石子的堆数；</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第二行正整数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">x,y,z,P</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(1&lt;=x,y,z&lt;=N;P&lt;=500)<o:p></o:p></span></span></span> 
</p>
<p style="text-indent:48pt;margin:0cm 0cm 0pt;mso-char-indent-count:4.0;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">有等式</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A[i]=[(i-x)^2+(i-y)^2+(i-z)^2] mod P</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">；</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第三行正整数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，表示有</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟；</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第四行正整数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K[1],K[2],x,y,z,P</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(x,y,z&lt;=1000;P&lt;=10000)<o:p></o:p></span></span></span> 
</p>
<p style="text-indent:48pt;margin:0cm 0cm 0pt;mso-char-indent-count:4.0;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">有等式</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K[i]=(x*K[i-1]+y*K[i-2]+z)mod P</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>接下来</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行两个正整数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L[i],R[i]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;">【输出格式】</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>有</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行表示第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟最多能取多少石子。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;">【样例输入】</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>5<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>3 2 4 7<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>3<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>2 5 2 6 4 9<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>2 4<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>1 2<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>3 5<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;">【样例输出】</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>2<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>5<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>5<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;">【样例说明】</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>石子每堆个数分别为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">0,5,2,5,0</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟，从第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">4</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">堆中选</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个；</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟，从第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">堆中选</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">5</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个；</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">3</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分钟，从第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">3</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">5</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">堆中选</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">8</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个，但最多只能选</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">5</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><o:p><span style="font-size:small;font-family:&#39;Times New Roman&#39;;"> </span></o:p></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;">【数据范围】</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>20%<span style="mso-spacerun:yes;">   </span>N&lt;=10<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>50%<span style="mso-spacerun:yes;">   </span>N&lt;=2000<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>100%<span style="mso-spacerun:yes;">  </span>N&lt;=40000<span style="mso-spacerun:yes;">   </span>M&lt;=N<span style="mso-spacerun:yes;">   </span>1&lt;=L[i]&lt;=R[i]&lt;=N<span style="mso-spacerun:yes;">   </span>A[i]&lt;=500<o:p></o:p></span></span></span> 
</p>

# "ret"

");
			if (canUseFile)
			{
				newT("span", divS, "", " &nbsp; &nbsp; &nbsp; ");
				var l2 = newT("a", divS, "", "上传文件提交");
				l2.href = "###";
				l2.onclick = function() {
					setDivS2();
				};
			}
		}
		function toLangDesc(lang)
		{
			if (lang=="CPP") return "C++ (MinGW g++ 4.7.2)";
			if (lang=="C") return "C (MinGW gcc 4.7.2)";
			if (lang=="C0X") return "C++0x (MinGW g++ 4.7.2 --std=c++0x)";
			if (lang=="VC9") return "VC (Microsoft Visual C++ 2008)";
			if (lang=="PAS") return "PAS (Free Pascal Compiler 2.4.0)";
			if (lang=="CS") return "C# (Microsoft .NET 3.5)";
			if (lang=="JAVA") return "Java (Java 1.7.0_15)";
			if (lang=="RUBY") return "Ruby (Ruby 1.8.6)";
			if (lang=="PERL") return "Perl (Perl v5.16.3)";
			if (lang=="PYTHON") return "Python (Python 3.3.0)";
			if (lang=="PYTHON27") return "Python (Python 2.7.3)";
			if (lang=="PHP") return "PHP (PHP 5.4.13)";
			return lang;
		}
		function setDivS2()
		{
			if (canUsePaste && !canUseFile)
			{
				setDivS1()
				return ;
			}
			div.style.display = "none";
			fdiv.style.display = "block";
			divS.innerHTML = "";
			if (canUsePaste)
			{
				var l1 = newT("a", divS, "", "粘贴代码提交");
				l1.href = "###";
				l1.onclick = function() {
					setDivS1();
				};
				newT("span", divS, "", " &nbsp; &nbsp; &nbsp; ");
			}
			var l2 = newT("span", divS, "", "
# la


