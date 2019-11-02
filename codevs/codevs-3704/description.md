<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在某一天，你有了一个女性朋友。</span></p><p style=""><span style="">你打算利用</span>k<span style="">天时间陪她，每天有很多种娱乐方式可供选择，你需要从中选择一种进行（一天只能进行一个项目），比如说一起去看电影、一起去主题公园，一起去逛街等等，一共</span>n<span style="">种项目。当然每个项目重复太多次你都会觉得无聊，因此第</span>i<span style="">个项目最多进行</span>c[i]<span style="">次。你虽然智商很高，但是情商堪忧，即使这些你准备的活动都是希望让她开心的，不过由于你笨拙的语言表达和过于理智的行动，可能使这些活动出现意外。经过你悉心的计算，你发现如果某一天进行了第</span>i<span style="">个项目，如果一切顺利的话她应该是很高兴的，但她会有</span>a[i]<span style="">的概率不高兴。如果她本来是很高兴的，但突然今天你让她不高兴了，她就会觉得很失落，并且对你的好感度大大下降。你希望尽可能避免这种情况发生，因此你要安排这</span>k<span style="">天之内每天进行的项目，最小化她感到失落的期望次数。</span></p><p style=""><span style="">你的女性朋友十分在意你，所以她的心情只会因为你发生改变。第一天之前，因为你没有邀请她进行任何活动，所以她是不高兴的。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行有一个非负整数</span>t<span style="">，表示一共有</span>t<span style="">组数据。</span></p><p style=""><span style="">对于每组数据，第一行有两个非负整数</span>n,k<span style="">，分别表示你准备的项目个数和你用来陪她的天数。（</span>n&lt;=10<sup>5</sup>, k&lt;=10<sup>9</sup><span style="">）</span></p><p style=""><span style="">接下来</span>n<span style="">行，每一行描述一个项目，形如</span>“x[i]/y[i] c[i]”<span style="">且三个数均为非负整数，表示进行完这个项目之后她有</span>x[i]/y[i]<span style="">的概率不高兴，并且这个项目只能进行不超过</span>c[i]<span style="">次。（</span>x[i],y[i] &lt;= 10<sup>4</sup>,c[i] &lt;= 10<sup>9</sup><span style="">）</span></p><p> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">一共</span>t<span style="font-family:宋体">行，对于每组数据输出使她感到失落的最小期望次数，四舍五入保留</span>6<span style="font-family:宋体">位小数。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>1 2</p><p>0/1 3</p><p>1 2</p><p>1/1 3</p><p>1 2</p><p>1/2 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.000000</p><p>0.000000</p><p>0.250000</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">考虑第三组数据，因为只有一个项目所以只好每天都安排这个。</span></p><p><span style="">在第一天之前她总是不高兴的，一共有：</span></p><p><span style="">第一天不高兴，第二天也不高兴、</span></p><p><span style="">第一天高兴，第二天不高兴、</span></p><p><span style="">第一天不高兴，第二天高兴、</span></p><p><span style="">第一天不高兴，第二天也不高兴，</span></p><p><span style="">这四种情况，又因为每天的项目让她高兴或者是不高兴的概率都是</span>0.5<span style="">，因此这四种情况是等概率发生的。</span></p><p><span style="">只有在第二种情况下，她会感到失落一次。</span></p><p><span style="">因此答案是</span>(1*1+0*3)/4=0.25.</p><p><span style="">对于前</span>10%<span style="">的数据，</span>n,k&lt;=5.</p><p><span style="">对于前</span>30%<span style="">的数据，</span>n,k&lt;=7.</p><p><span style="">对于前</span>40%<span style="">的数据，</span>n,k&lt;=10.</p><p><span style="">对于前</span>60%<span style="">的数据，</span>n&lt;=1000,k&lt;=10<sup>5</sup>.</p><p><span style="">对于</span>100%<span style="">的数据，</span>n&lt;=10<sup>5</sup><span style="">，</span>k&lt;=10<sup>9</sup><span style="">，数据组数不会太多，大概不超过</span>10<span style="">组，数据保证分数有意义并且∑</span>c[i]&gt;=k<span style="">。</span></p><p><br></p>
</div>
</div>