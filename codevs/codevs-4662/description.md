<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>符鹤严是个音乐极有天赋的人，自称符爷爷，符爷爷特别喜欢纯音乐，尤其是钢琴曲，但是他最近他的钢琴谱子有问题，严重影响他撩妹，于是他跪着求你，希望你能解决，现在钢琴上面的n个音符，我们确定<strong>符爷爷</strong>要弹的音符就在这些之中。音符全部用小写字母表示。<strong>符爷爷</strong>只记得有些音乐片段是明显有问题的，这些音乐片段由若干个音符组成。问如果符爷爷要弹由m个音符组成的音乐，但是这段音乐不包括那些有问题的片段（当然也不能就是那些片段），有多少种弹奏的方案？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为三个正整数n,m,p，分别表示音符总个数，<strong>符爷爷</strong>要弹的音乐长度，有问题的音乐片段的个数；</p><p>第二行为一个长度为n的字符串dict，表示n个音符，保证互不相同；</p><p>接下来有p行，对于第i行为一个字符串chi，表示第i个有问题的音乐片段。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:19px;font-family:宋体">一个正整数，表示方案总数。如果什么都不能弹，输出</span><span style="font-size:19px">-1</span><span style="font-size:19px;font-family:宋体">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">2 3 1</span></p><p><span style="font-family: 'Courier New';">ab</span></p><p><span style="font-family: 'Courier New';">aa</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据：1≤n≤5,1≤m≤3,0≤p≤5；</p><p>另外有10%的数据：1≤n≤10,1≤m=len≤10,0≤p≤10，其中len表示每一个有问题的片段长度。</p><p>60%的数据：1≤n≤20,1≤m≤20,0≤p≤10；</p><p>100%的数据：1≤n≤25,1≤m≤50,0≤p≤10。</p><p><br></p>
</div>
</div>