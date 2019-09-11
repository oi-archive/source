# 题目描述


<p>
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
</p>
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<h3>
【问题描述】
</h3>
<div class="pdcont">
设sum(S)表示集合S中所有元素的和。如果对于S的任意两个不相交子集A和B，如果他们满足：<br/>
<img src="/upload/image/20141210/20141210152719_18664.bmp" alt=""/><br/>
则称S是R集合。<br/>
现在我们假设有一个大小为N，元素互不相等的集合，已经满足了条件(2)，问最坏情况下最少需要几次比较才能确定它是不是R集合。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含一个整数N。N&lt;=1000。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示最少比较次数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
4
</div>
<h3>
【样例输出】
</h3>
<p>
1
</p>
<h3>
【数据说明】
</h3>
<p>
设这个4 元集的元素是a1 &lt; a2 &lt; a3 &lt; a4，那么我们只需要比较
</p>
<p>
sum(a1, a4) 和sum(a2, a3)。别是：3-9、2-10、2-8、1-9、3-11、4-12。
</p>
<h3>
【数据规模】
</h3>
<p>
一共有20 个数据，对于第i (1 ≤ i ≤ 20) 个数据， N = i * 50。
</p>
