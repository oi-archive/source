# 

 
 # 题目描述 
<p><span style="font-family: SimSun; font-size: 12pt; color: rgb(0, 0, 0);">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;安安参加研究性学习，他们小组研究噪音对于人们生活和学习影响的课题。课题需<span style="font-size: 12pt;">&nbsp;要分析某一天噪音强度的最大值和最小值，以及最小值与最大值发生的时刻。安安已经<span style="font-size: 12pt;">&nbsp;拿到这一天每一秒的噪音强度信息，一共有&nbsp;<span style="font-family: Consolas; font-size: 12pt;">86400&nbsp;<span style="font-family: SimSun; font-size: 12pt;">条信息，这可是<span style="font-family: Consolas; font-size: 12pt;">&ldquo;<span style="font-family: SimSun; font-size: 12pt;">大数据<span style="font-family: Consolas; font-size: 12pt;">&rdquo;<span style="font-family: SimSun; font-size: 12pt;">。现在请<span style="font-size: 12pt;">&nbsp;你用计算机程序挖掘出他们需要的信息。<span style="font-size: 12pt;">&nbsp;给定一整天各时刻的噪音强度，分析出全天噪音强度的最大值和最小值，以及最小<span style="font-size: 12pt;">&nbsp;值与最大值发生的时刻。</span></span></span></span></span></span></span></span></span></span></span></span><br style="line-height: normal; orphans: 2; text-align: -webkit-auto; widows: 2;" />
&nbsp;</p> 

 
 # 输入格式 
<p><span style="font-family: SimSun; font-size: 12pt; color: rgb(0, 0, 0);">共&nbsp;<span style="font-family: Consolas; font-size: 12pt;">24*60*60&nbsp;<span style="font-family: SimSun; font-size: 12pt;">行，每行一个整数，为按照时间先后顺序，各时刻噪音强度。</span></span>输入样例<br />
<span style="font-family: Consolas; font-size: 12pt;">37&nbsp;<span style="font-size: 12pt; color: rgb(0, 0, 255);">//0:00:0<br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);">36&nbsp;<span style="font-size: 12pt; color: rgb(0, 0, 255);">//0:00:0</span></span></span></span></span></p>

<p><span style="font-family: SimSun; font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-family: Consolas; font-size: 12pt;"><span style="font-size: 12pt; color: rgb(0, 0, 255);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 255);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">。&nbsp;。&nbsp;。<br />
<span style="font-size: 12pt;">65&nbsp;<span style="font-size: 12pt; color: rgb(0, 0, 255);">//23:59:58<br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);">35&nbsp;<span style="font-size: 12pt; color: rgb(0, 0, 255);">//23:59:59<span style="font-size: 12pt; color: rgb(0, 0, 0);">&nbsp;</span></span></span></span></span></span></span></span></span></span></span><br style="line-height: normal; orphans: 2; text-align: -webkit-auto; widows: 2;" />
&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p> 

 
 # 输出格式 
<p><span style="font-family: SimSun; font-size: 12pt; color: rgb(0, 0, 0);">&nbsp;&nbsp;&nbsp;&nbsp;若干行，前面的若干行，为最小值及发生的时刻；紧接着一个空行，后面还有若干<span style="font-size: 12pt;">&nbsp;行，为最大值及发生的时刻。<span style="font-size: 12pt;">&nbsp;无论是噪音最小值还是最大值，&nbsp;都有可能在多个不同的时刻发生，&nbsp;若出现这样情况，<span style="font-size: 12pt;">&nbsp;按照时间先后输出。<span style="font-size: 12pt;">&nbsp;除中间的空行外，其他各行都有两部分组成，中间有一个空格隔开。第一部分为一<span style="font-size: 12pt;">&nbsp;个整数，为最小<span style="font-family: Consolas; font-size: 12pt;">/<span style="font-family: SimSun; font-size: 12pt;">大噪音强度，第二部分为该噪音发生的时刻。</span></span></span></span></span></span></span></span><span style="font-family: SimSun; font-size: 12pt; color: rgb(0, 0, 0);">时间格式要符合如图所示规范：分秒都是两位表示。</span><br style="line-height: normal; orphans: 2; text-align: -webkit-auto; widows: 2;" />
<span style="font-family: SimSun; font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-family: Consolas; font-size: 12pt;"><span style="font-size: 12pt; color: rgb(0, 0, 255);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 255);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt;"><span style="font-size: 12pt; color: rgb(0, 0, 255);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 255);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">输出样例<br />
<span style="font-size: 12pt;">20&nbsp;2:00:30<br />
<span style="font-size: 12pt;">20&nbsp;3:30:21<br />
<span style="font-size: 12pt;">78&nbsp;18:29:03</span></span></span></span></span></span></span></span></span></span></span></span></span></span><br style="line-height: normal; orphans: 2; text-align: -webkit-auto; widows: 2;" />
&nbsp;</p> 

 
 # 提示 
<p><br style="line-height: normal; orphans: 2; text-align: -webkit-auto; widows: 2;" />
&nbsp;</p> 
