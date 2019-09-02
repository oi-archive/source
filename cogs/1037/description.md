# 题目描述


<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">数列谜题</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">【问题描述】</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">ZYN是个非常可爱的OIer，他正享受着暑假美好的生活。这一天，他百般聊</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">赖地找来了同样为OIer的好朋友LHC，开始研究数学课程。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">其中有一讲专题，内容就是有关数列的。上面列有最基本的等差、等比数列，</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">以及求和、求通项等等。可是LHC反应比较慢，ZYN便趁机欺负他，随手写了几</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">个数列，让LHC去判断分别属于哪种数列。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">渐渐的，LHC找到了诀窍，很快就能答出ZYN的问题。ZYN也不满足于写简</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">单的等差、等比数列，便自己发明了一个数列，该数列的递推式如下：</span> 
<p style="text-align:center;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="line-height:19.2px;font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">$A_{i+1}=(A_i+F_i)*F_i$</span></span> 
</p>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">其中i≥1，$F_i$为第i个质数，数列共有N项</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">就在ZYN乐呵呵地欣赏自己的“大作”时，LHC突然喊了一句“你这个数列</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">写错了”。ZYN：“怎么可能，哪里写错了，唔。。。我来看看”。ZYN找了半</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">天，也没有找到错误所在，可他也不想直接去问LHC，因为好没面子。于是他便</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">找到了你，而你只需要判断，该数列的最后一项是否正确。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">【输入格式】</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">从文件sequencea.in中读入数据。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">第1行有1个数为T，表示共有T个数列。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">第2行到第T+1行，每行共有3个数，$N$，$A_i$、$A_N$，分别表示该数列的</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">长度以及数列中的两项。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">【输出格式】</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">输出到文件sequencea.out中。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">输出T行，如果该数列的最后一项正确，则输出“YES”，否则输出“NO”。</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">【样例输入】</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">2</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">3 3 39</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">4 4 24</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">【样例输出】</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">YES</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">NO</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">【样例解释】</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">对于T=1:</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">$A_1$=3</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">$A_2$=(3+2)*2=10</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">$A_3$=(10+3)*3=39</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">【数据范围】</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">对于40%数据，1≤$N、A_1$  &lt;= 10</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">对于80%数据，1≤$N、A_1$≤100</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">对于100%数据，1≤N</span><span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">、A1≤1000，T≤10</span><br/>
<span style="font-family: &#39;Microsoft YaHei&#39;; font-size: 16px; " yahei?;font-size:16px;?="" microsoft="">输入数据大小≤20kb</span><br/>
<span style="font-family: ;" yahei?;font-size:16px;?="" microsoft=""></span><br/>
