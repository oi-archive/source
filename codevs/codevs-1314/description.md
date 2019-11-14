<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>传说很遥远的藏宝楼顶层藏着诱人的宝藏。小明历尽千辛万苦终于找到传说中的这个藏宝楼，藏宝楼的门口竖着一个木板，上面写有几个大字：寻宝说明书。说明书的内容如下：</p>
<p>藏宝楼共有N+1层，最上面一层是顶层，顶层有一个房间里面藏着宝藏。除了顶层外，藏宝楼另有N层，每层M个房间，这M个房间围成一圈并按逆时针方向依次编号为0，…，M-1。其中一些房间有通往上一层的楼梯，每层楼的楼梯设计可能不同。每个房间里有一个指示牌，指示牌上有一个数字x，表示从这个房间开始按逆时针方向选择第x个有楼梯的房间（假定该房间的编号为k），从该房间上楼，上楼后到达上一层的k号房间。比如当前房间的指示牌上写着2，则按逆时针方向开始尝试，找到第2个有楼梯的房间，从该房间上楼。如果当前房间本身就有楼梯通向上层，该房间作为第一个有楼梯的房间。</p>
<p>    寻宝说明书的最后用红色大号字体写着：“寻宝须知：帮助你找到每层上楼房间的指示牌上的数字（即每层第一个进入的房间内指示牌上的数字）总和为打开宝箱的密钥”。</p>
<p>请帮助小明算出这个打开宝箱的密钥。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行2个整数N和M，之间用一个空格隔开。N表示除了顶层外藏宝楼共N层楼，M表示除顶层外每层楼有M个房间。</p>
<p>接下来N*M行，每行两个整数，之间用一个空格隔开，每行描述一个房间内的情况，其中第(i-1)*M+j行表示第i层j-1号房间的情况（i=1,2,…, N；j=1,2,…,M）。第一个整数表示该房间是否有楼梯通往上一层（0表示没有，1表示有），第二个整数表示指示牌上的数字。注意，从<strong>j</strong>号房间的楼梯爬到上一层到达的房间一定也是<strong>j</strong>号房间。</p>
<p>最后一行，一个整数，表示小明从藏宝楼底层的几号房间进入开始寻宝（注：房间编号从0开始）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，一个整数，表示打开宝箱的密钥，这个数可能会很大，请输出对20123取模的结果即可。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>
<p>1 2</p>
<p>0 3</p>
<p>1 4</p>
<p>0 1</p>
<p>1 5</p>
<p>1 2</p>
<p>1</p>

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
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例说明】</p>
<p>第一层：</p>
<p>0号房间，有楼梯通往上层，指示牌上的数字是2；</p>
<p>1号房间，无楼梯通往上层，指示牌上的数字是3；</p>
<p>2号房间，有楼梯通往上层，指示牌上的数字是4；</p>
<p>第二层：</p>
<p>0号房间，无楼梯通往上层，指示牌上的数字是1；</p>
<p>1号房间，有楼梯通往上层，指示牌上的数字是5；</p>
<p>2号房间，有楼梯通往上层，指示牌上的数字是2；</p>
<p>小明首先进入第一层（底层）的1号房间，记下指示牌上的数字为3，然后从这个房间开始，沿逆时针方向选择第3个有楼梯的房间2号房间进入，上楼后到达第二层的2号房间，记下指示牌上的数字为2，由于当前房间本身有楼梯通向上层，该房间作为第一个有楼梯的房间。因此，此时沿逆时针方向选择第2个有楼梯的房间即为1号房间，进入后上楼梯到达顶层。这时把上述记下的指示牌上的数字加起来，即3+2=5，所以打开宝箱的密钥就是5。</p>
<p>【数据范围】</p>
<p>对于50%数据，有0&lt;N≤1000，0&lt;x≤10000；</p>
<p>对于100%数据，有0&lt;N≤10000，0&lt;M≤100，0&lt;x≤1,000,000。</p>
</div>
</div>