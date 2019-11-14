# 题目描述


<h3>
【题目描述】
</h3>
<p>
    
</p>
<p>
<strong>  </strong> 在即将到来的跨年祭前夕，镜音铃和镜音连仍在准备着明天的演唱任务，他们被大姐“失误什么的…都是不可原谅的呢~”的由于不可抗力因素导致无法违背的话命令:
</p>
<p>
<br/>
</p>
<p>
<strong>   要在跨年祭上在观众们要求的n首歌中选取k首进行演唱，并要求在时间不超过t的前提下带给观众的hi度达到m。</strong> 
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
<strong>   </strong>但让他们发愁的是，铃和连熟悉的音频范围不同，所以他们对每首歌都有自己的演唱方式，因此很难达到同步，这将在很大程度上降低每首歌的hi度，为达到更好的效果，<strong>铃和连同意两人开始演唱的时间可以不同，但同步部分必须是镜音铃的歌曲高潮部分起始点（连是有多可怜…），双子希望能在第i首歌从h[i]处(从0编号)进入高潮部分后，同步时间尽量长，使达到的hi度 i*x (i表示演唱曲目的序号)的总和尽量大。</strong> 
</p>
<p>
 
</p>
<img alt="" src="/upload/image/20141010/20141010062123_39028.jpg" height="718" width="984"/> 
<p>
 
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
第一行三个整型：n,m,t;
</p>
<p>
以下n组，每组代表一首曲目，
</p>
<p>
第一行为当前歌曲i的高潮部分起始位置h[i]和歌曲时间l[i];
</p>
<p>
以下为两个长度l[i]字符串，都以\n结束，代表铃和连风格的歌。
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
假如无法达到要求，输出QwQ。
</p>
<p>
否则第一行输出k和所能达到的最大hi度;
</p>
<p>
第二行输出歌曲的演唱顺序;
</p>
<p>
（假设情况不唯一，输出字典序最小）
</p>
<p>
<strong>【样例输入】</strong><strong></strong> 
</p>
<p>
<strong> </strong> 
</p>
<p>
<strong>2 10 30</strong> 
</p>
<p>
<strong>5 12</strong> 
</p>
<p>
<strong>ccbaacbaccba</strong> 
</p>
<p>
<strong>abbcaaacbacc</strong> 
</p>
<p>
<strong>7 15</strong> 
</p>
<p>
<strong>bbbbbcccccccccc</strong> 
</p>
<p style="display:inline !important;">
<strong>aaaaabbbbbccccc</strong> 
</p>
<p>
<br/>
</p>
<p>
<strong> </strong> 
</p>
<p style="display:inline !important;">
<strong><br/>
</strong> 
</p>
<p>
<br/>
</p>
<p>
<strong>【样例输出</strong><strong>】</strong> 
</p>
<p>
<br/>
</p>
<p>
<strong>2 15</strong> 
</p>
<p>
<strong>1 2</strong> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<div>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【提示】
</h3>
<p>
（样例解释：曲目1从高潮部分起的最长重叠部分cbacc长度为5;曲目2从高潮部分起的最长重叠部分ccccc长度为5，最大hi度为5*1+5*2=15）
</p>
<p>
<br/>
</p>
<p>
1&lt;=n&lt;=10;
</p>
<p>
1&lt;=t&lt;=20000;
</p>
<p>
1&lt;=m&lt;=50000;
</p>
<p>
单首曲目最长长度为17000;
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
  AiKy
</p>
<p>
<br/>
</p>
</div>
