# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
痛过以后 才知情已难寻
</p>
<p>
吾爱至斯 只剩飞花梦影
</p>
<p>
回首再望 蜀山依旧伫立
</p>
<p>
看尽浮沉 独饮回忆
</p>
<p>
——《少年情》
</p>
<p>
旋律动听的曲子，伴着意境深远的lyric而显得更加优美。要想学会一首歌，没有一份装订精美的歌词，你让我情何以堪。
</p>
<p>
你的任务是，将一份歌词，按照给出规则整理好。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
若干行文字（包括按规定格式给出歌曲名，歌词）
</p>
<p>
每一行格式为 标识+内容
</p>
<p>
标识[name]表示后接歌曲名
</p>
<p>
标识[mm:ss]表示后接歌词，其中?,?表示每一位数字，为歌词出现的时间。保证符合正常的计时方式。
</p>
<p>
若存在时间相同的歌词，则应按规则依次首尾相连在同一行输出，规则如下：
</p>
<p>
长度短的靠前；
</p>
<p>
长度相同则字典序小的靠前。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
第一行八个空格+歌曲名
</p>
<p>
第二行及以后按时间顺序列出歌词
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>[00:02]she is the heaven-sent angel you met 
[00:05]=.=.=.=.= 
[00:04]she is so pretty all over the world 
[00:01]she is the one that you never forget 
[name]she 
[00:03]oh,she must be the reason why God made a girl </pre>
<h3>
【样例输出】
</h3>
<pre>        she 
she is the one that you never forget 
she is the heaven-sent angel you met 
oh,she must be the reason why God made a girl 
she is so pretty all over the world 
=.=.=.=.= 

</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
保证歌曲名和歌词均为英文字母,字符。
</p>
<p>
不能保证每一行不超过256个字符
</p>
<p>
保证输入不超过2000行
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
