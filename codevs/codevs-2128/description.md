<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了在即将到来的晚会上有更好的演出效果，作为 AAA 合唱队负责人的小 A 需要将合唱队</p>
<p>的人根据他们的身高排出一个队形。假定合唱队一共有 N 个人，第 i 个人的身高为 Hi 毫米</p>
<p>(1000≤Hi≤2000)，并且已知任何两个人的身高都不同。假定最终排出的队形是 N 个人站成一</p>
<p>排，为了简化问题，小 A 想出了如下排队的方式：他让所有的人先按任意顺序站成一个初始队</p>
<p>形，然后从左到右按以下原则依次将每个人插入最终排出的队形中：</p>
<p>-  第一个人直接插入空的当前队形中。</p>
<p>-  对从第二个人开始的每个人，</p>
<p>  如果他比前面那个人高(H较大)，那么将他插入当前队形的最右边。</p>
<p>  如果他比前面那个人矮(H较小)，那么将他插入当前队形的最左边。</p>
<p>当 N个人全部插入当前队形后便获得最终排出的队形。</p>
<p>例如，有6个人站成一个初始队形，身高依次为 1850、1900、1700、1650、1800和1750，</p>
<p>那么小A会按以下步骤获得最终排出的队形：</p>
<p>-  1850</p>
<p>-  1850, 1900                          因为 1900 &gt; 1850</p>
<p>-  1700, 1850, 1900                    因为 1700 &lt; 1900</p>
<p>-  1650, 1700, 1850, 1900              因为 1650 &lt; 1700</p>
<p>-  1650, 1700, 1850, 1900, 1800        因为 1800 &gt; 1650</p>
<p>-  1750, 1650, 1700, 1850, 1900, 1800  因为 1750 &lt; 1800</p>
<p>因此，最终排出的队形是1750, 1650, 1700, 1850, 1900, 1800。</p>
<p>小 A 心中有一个理想队形，他想知道从多少种初始队形出发能通过上述排队的方式获得他</p>
<p>心中的理想队形作为最终排出的队形？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是一个正整数N，表示总人数。输入文件第</p>
<p>二行是用空格隔开的N个正整数，从左到右表示小A心中的理想队形：H1, H2, „, HN。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅包含一个数， 表示从多少种初始队形出发能通过上述排队的方式获</p>
<p>得输入文件中指定的小 A 心中的理想队形。因为满足条件的初始队形数可能很大，所以规定只</p>
<p>要输出满足条件的初始队形数 mod 19650827 的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 </p>
<p>1701 1702 1703 1704 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的数据保证1000≤Hi≤2000且没有相同的H值，其中30%的数据满足1≤N≤100，100%的数据满足</p>
<p>1≤N≤1000。</p>
</div>
</div>