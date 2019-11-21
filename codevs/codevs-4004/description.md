<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">YJY拥有一个很大的野生动物园。这个动物园坐落在一个狭长的山谷内，（动物园内部口号：每日膜拜陈靖邦,NOIP拿满分,GDKOI拿满分,APIO拿满分,GDOI拿满分,NOI拿满分,IOI拿满分。今天你膜拜了吗?）这个区域从南到北被划分成N个区域，每个区域都饲养着一头狮子。这些狮子从北到南编号为1,2,3,…,N。每头狮子都有一个觅食能力值Ai，Ai越小觅食能力越强。饲养员YJY决定对狮子进行M次投喂，每次投喂都选择一个区间[I,J]，从中选取觅食能力值第K强的狮子进行投喂。值得注意的是，YJY不愿意对某些区域进行过多的投喂，他认为这样有悖公平。因此YJY的投喂区间是互不包含的。你的任务就是算出每次投喂后，食物被哪头狮子吃掉了。</span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入第一行有两个数N和M。此后一行有N个数，从南到北描述狮子的觅食能力值。此后M行，每行描述一次投喂。第t+2的三个数I,J,K表示在第t次投喂中，YJY选择了区间[I,J]内觅食能力值第K强的狮子进行投喂。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Lucida Grande&#39;, Lucida, &#39;Lucida Sans Unicode&#39;, &#39;Lucida Sans&#39;, Tahoma, &#39;Segoe UI&#39;, Verdana, 微软雅黑, &#39;Microsoft YaHei&#39;, 宋体; font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">输出有M行，每行一个整数。第i行的整数表示在第i次投喂中吃到食物的狮子的觅食能力值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 2</p><p>1 5 2 6 3 7 4</p><p>1 5 3</p><p>2 7 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【数据范围】</span></p><p style=""><span style="">对于100%的数据，有1&lt;=N&lt;=100000，1&lt;=M&lt;=50000。</span></p><p style=""><span style="">【类型】</span></p><p>标签：数据结构 平衡树</p><p>【来源】</p><p style="">来源：vijos1080，有更改。我把它复制了过来......</p><p style="">【测试数据】</p><p style=""><strong>如果发现测试数据有误，请联系管理员！(自己提交一次，好像没问题)</strong></p>
</div>
</div>