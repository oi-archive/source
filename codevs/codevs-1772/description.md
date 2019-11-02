<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>35<br>痛过以后才知情已难寻<br>吾爱至斯只剩飞花梦影<br>回首再望蜀山依旧伫立<br>看尽浮沉独饮回忆<br>——《少年情》</p>
<p><br>旋律动听的曲子，伴着意境深远的歌词 而显得更加优美。要想学会一首歌，没有<br>一份装订精美的歌词，你让我情何以堪。<br>你的任务是，将一份歌词，按照给出规则整理好。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>若干行文字（包括按规定格式给出歌曲名，歌词）<br>每一行格式为标识+内容<br>标识[name]表示后接歌曲名<br>标识[mm:ss]表示后接歌词，其中m,s表示每一位数字，为歌词出现的时间。保证符<br>合正常的计时方式。<br>若存在时间相同的歌词，则应按规则依次首尾相连在同一行输出，规则如下：<br>长度短的靠前；<br>长度相同则字典序小的靠前。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行八个空格+歌曲名<br />第二行及以后按时间顺序列出歌词</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>[00:02]she is the heaven-sent angel you met<br>[00:05]=.=.=.=.=<br>[00:04]she is so pretty all over the world<br>[00:01]she is the one that you never forget<br>[name]she<br>[00:03]oh,she must be the reason why God made a girl</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>        she<br>she is the one that you never forget<br>she is the heaven-sent angel you met<br>oh,she must be the reason why God made a girl<br>she is so pretty all over the world<br>=.=.=.=.=</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>保证歌曲名和歌词均为英文字母,字符。<br>保证每一行不超过256 个字符<br>保证输入不超过2000 行</p>
</div>
</div>