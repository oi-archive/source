<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小W是一片新造公墓的管理人。公墓可以看成一块<em>N</em>×<em>M</em>的矩形，矩形的每个格点，要么种着一棵常青树，要么是一块还没有归属的墓地。</p>
<p>当地的居民都是非常虔诚的基督徒，他们愿意提前为自己找一块合适墓地。为了体现自己对主的真诚，他们希望自己的墓地拥有着较高的虔诚度。</p>
<p>一块墓地的虔诚度是指以这块墓地为中心的十字架的数目。一个十字架可以看成中间是墓地，墓地的正上、正下、正左、正右都有恰好<em>k</em>棵常青树。</p>
<p>小W希望知道他所管理的这片公墓中所有墓地的虔诚度总和是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包含两个用空格分隔的正整数<em>N</em>和<em>M</em>，表示公墓的宽和长，因此这个矩形公墓共有(<em>N</em>+1) ×(<em>M</em>+1)个格点，左下角的坐标为(0, 0)，右上角的坐标为(<em>N</em>, <em>M</em>)。</p>
<p>第二行包含一个正整数<em>W</em>，表示公墓中常青树的个数。</p>
<p>第三行起共<em>W</em>行，每行包含两个用空格分隔的非负整数<em>x<sub>i</sub></em>和<em>y<sub>i</sub></em>，表示一棵常青树的坐标。输入保证没有两棵常青树拥有相同的坐标。</p>
<p>最后一行包含一个正整数<em>k</em>，意义如题目所示。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅包含一个非负整数，表示这片公墓中所有墓地的虔诚度总和。为了方便起见，答案对2,147,483,648取模。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 6</p>
<p>13</p>
<p>0 2</p>
<p>0 3</p>
<p>1 2</p>
<p>1 3  </p>
<p>2 0</p>
<p>2 1</p>
<p>2 4</p>
<p>2 5</p>
<p>2 6</p>
<p>3 2</p>
<p>3 3</p>
<p>4 3</p>
<p>5 2</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>(<span style="">以墓地(2, 2)和(2, 3)为中心的十字架各有3个，即它们的虔诚度均为3。其他墓地的虔诚度为0。)</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，满足1 ≤ <em>N</em>, <em>M </em>≤ 1,000。</p>
<p>对于60%的数据，满足1 ≤ <em>N</em>, <em>M </em>≤ 1,000,000。</p>
<p>对于100%的数据，满足1 ≤ <em>N</em>, <em>M </em>≤ 1,000,000,000，0 ≤ <em>x<sub>i </sub></em>≤ <em>N</em>，0 ≤ <em>y<sub>i </sub></em>≤ <em>M</em>，1 ≤ <em>W </em>≤ 100,000，1 ≤ <em>k </em>≤ 10。</p>
<p>存在50%的数据，满足1 ≤ <em>k </em>≤ 2。</p>
</div>
</div>