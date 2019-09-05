# 题目描述


<div>
	<b><span><span style="font-weight:normal;font-size:12pt;line-height:173%;">【问题描述】</span></span></b>
</div>
<div>
	<span style="font-size:12pt;">已知一棵特殊的二叉查找树。根据定义，该二叉查找树中每个结点的<b><u>数据值</u></b>都比它左<span style="color:blue;">子树</span>结点的<b><u>数据值</u></b>大，而比它右<span style="color:blue;">子树</span>结点的<b><u>数据值</u></b>小。</span>
</div>
<div>
	<span style="font-size:12pt;">另一方面，这棵查找树中每个结点都有一个<b><u>权值</u></b>，每个结点的<b><u>权值</u></b>都比它的儿子结点的<b><u>权值</u></b>要小。</span>
</div>
<div>
	<span style="font-size:12pt;">已知树中所有结点的<b><u>数据值</u></b>各不相同；所有结点的<b><u>权值</u></b>也各不相同。这时可得出这样一个有趣的结论：如果能够确定树中每个结点的<b><u>数据值</u></b>和<b><u>权值</u></b>，那么树的形态便可以唯一确定。因为这样的一棵树可以看成是按照<b><u>权值</u></b>从小到大顺序插入结点所得到的、按照<b><u>数据值</u></b>排序的二叉查找树。</span>
</div>
<div>
	<span style="font-size:12pt;">一个结点在树中的<b><u>深度</u></b>定义为它到树根的距离加</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">。因此树的根结点的深度为</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">。</span>
</div>
<div>
	<span style="font-size:12pt;">每个结点除了<b><u>数据值</u></b>和<b><u>权值</u></b>以外，还有一个<b><u>访问频度</u></b>。我们定义一个结点<b><u>在树中的访问代价</u></b>为它的<b><u>访问频度</u></b>乘以它在树中的<b><u>深度</u></b>。<b><u>整棵树的访问代价</u></b>定义为所有结点<b><u>在树中的访问代价</u></b>之和。</span>
</div>
<div>
	<span style="font-size:12pt;">       </span><span style="font-size:12pt;">现在给定每个结点的<b><u>数据值</u>、<u>权值</u></b>和<b><u>访问频度</u>，</b>你可以根据需要修改某些结点的<b><u>权值</u></b>，但每次修改你会付出</span><i><span style="font-size:12pt;">K</span></i><span style="font-size:12pt;">的<b><u>额外修改代价</u></b>。你可以把结点的<b><u>权值</u></b>改为任何实数，但是修改后所有结点的<b><u>权值</u></b>必须仍保持互不相同。现在你要解决的问题是，<b><u>整棵树的访问代价</u></b>与<b><u>额外修改代价</u></b>的和最小是多少？</span>
</div>
<div style="margin:13pt 0cm;">
	<b><span><span style="font-weight:normal;font-size:12pt;line-height:173%;">【输入文件】</span></span></b>
</div>
<div>
	<span style="font-size:12pt;">输入文件名为</span><span style="font-size:12pt;">treapmod.in</span><span style="font-size:12pt;">。</span>
</div>
<div>
	<span style="font-size:12pt;">输入文件第一行包含两个正整数</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">和</span><i><span style="font-size:12pt;">K</span></i><span style="font-size:12pt;">。</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">为结点的个数，</span><i><span style="font-size:12pt;">K</span></i><span style="font-size:12pt;">为每次修改所需的<b><u>额外修改代价</u></b>。</span>
</div>
<div>
	<span style="font-size:12pt;">接下来一行包含</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">个非负整数，是每个结点的<b><u>数据值</u></b>。</span>
</div>
<div>
	<span style="font-size:12pt;">再接下来一行包含</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">个非负整数，是每个结点的<b><u>权值</u></b>。</span>
</div>
<div>
	<span style="font-size:12pt;">再接下来一行包含</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">个非负整数，是每个结点的<b><u>访问频度</u></b>。</span>
</div>
<div>
	<span style="font-size:12pt;">所有的数据值、权值、访问频度均不超过</span><span style="font-size:12pt;">400000</span><span style="font-size:12pt;">。每两个数之间都有一个空格分隔，且行尾没有空格。</span>
</div>
<div style="margin:13pt 0cm;">
	<b><span><span style="font-weight:normal;font-size:12pt;line-height:173%;">【输出文件】</span></span></b>
</div>
<div>
	<span style="font-size:12pt;">输出文件名为</span><span style="font-size:12pt;">treapmod.out</span><span style="font-size:12pt;">。输出文件只有一个数字，即你所能得到的<b><u>整棵树的访问代价</u></b>与<b><u>额外修改代价</u></b>之和的最小值。</span>
</div>
<div style="margin:13pt 0cm;">
	<b><span><span style="font-weight:normal;font-size:12pt;line-height:173%;">【输入样例】</span></span></b>
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	<span style="font-size:12pt;">4 10</span>
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	<span style="font-size:12pt;">1 2 3 4</span>
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	<span style="font-size:12pt;">1 2 3 4</span>
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	<span style="font-size:12pt;">1 2 3 4</span>
</div>
<div style="margin:13pt 0cm;">
	<b><span><span style="font-weight:normal;font-size:12pt;line-height:173%;">【输出样例】</span></span></b>
</div>
<div>
	<span style="font-size:12pt;">29</span>
</div>
<div style="margin:13pt 0cm;">
	<b><span><span style="font-weight:normal;font-size:12pt;line-height:173%;">【样例说明】</span></span></b>
</div>
<div>
	<span style="font-size:12pt;">输入的原图是左图，它的<b><u>访问代价</u></b>是</span><span style="font-size:12pt;">1×1+2×2+3×3+4×4=30</span><span style="font-size:12pt;">。最佳的修改方案是把输入中的第</span><span style="font-size:12pt;">3</span><span style="font-size:12pt;">个结点的权值改成</span><span style="font-size:12pt;">0</span><span style="font-size:12pt;">，得到右图，<b><u>访问代价</u></b>是</span><span style="font-size:12pt;">1×2+2×3+3×1+4×2=19</span><span style="font-size:12pt;">，加上<b><u>额外修改代价</u></b></span><span style="font-size:12pt;">10</span><span style="font-size:12pt;">，一共是</span><span style="font-size:12pt;">29</span><span style="font-size:12pt;">。</span>
</div>
<p>
	<img height="263" alt="" width="501" src="/images/treapmod1.bmp"/>
</p>
<div style="margin:13pt 0cm;">
	<b><span><span style="font-weight:normal;font-size:12pt;line-height:173%;">【数据规模】</span></span></b>
</div>
<div>
	<span style="font-size:12pt;">40%</span><span style="font-size:12pt;">的数据满足</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;"> ≤ 30;</span>
</div>
<div>
	<span style="font-size:12pt;">70%</span><span style="font-size:12pt;">的数据满足</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;"> ≤ 50;</span>
</div>
<div>
	<span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据满足</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;"> ≤ 70, 1 ≤ <i>K </i>≤ 30000000</span><span style="font-size:12pt;">。</span>
</div>
