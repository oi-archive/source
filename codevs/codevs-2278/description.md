<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个吉他手准备参加一场演出。他不喜欢在演出时始终使用同一个音量，所以他决定每一首歌之前他都要改变一次音量。在演出开始之前，他已经做好了一个列表，里面写着在每首歌开始之前他想要改变的音量是多少。每一次改变音量，他可以选择调高也可以调低。</p>
<p>音量用一个整数描述。输入文件中给定整数beginLevel，代表吉他刚开始的音量，以及整数maxLevel，代表吉他的最大音量。音量不能小于0也不能大于maxLevel。输入文件中还给定了n个整数c<sub>1</sub>,c<sub>2</sub>,...,c<sub>n</sub>，表示在第i首歌开始之前吉他手想要改变的音量是多少。</p>
<p>吉他手想以最大的音量演奏最后一首歌，你的任务是找到这个最大音量是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行依次为三个整数：n, beginLevel, maxlevel。</p>
<p>第二行依次为n个整数：c<sub>1</sub>,c<sub>2</sub>,...,c<sub>n</sub>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出演奏最后一首歌的最大音量。如果吉他手无法避免音量低于0或者高于maxLevel，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><em><strong>Sample 1</strong></em><br>3 5 10<br>5 3 7</p>
<p><em><strong>Sample 2</strong></em><br>4 8 20<br>15 2 9 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><em><strong>Sample 1</strong></em><br>10</p>
<p><em><strong>Sample 2</strong></em><br>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 ≤ n ≤ 50，1 ≤ c<sub>i </sub>≤ maxLevel ≤ 1000，0 ≤ beginLevel ≤ maxLevel</p>
</div>
</div>