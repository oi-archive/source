<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　随着社会的不断发展，人与人之间的感情越来越功利化。最近，爱神丘比特发现，爱情也已不再是完全纯洁的了。这使得丘比特很是苦恼，他越来越难找到合适的男女，并向他们射去丘比特之箭。于是丘比特千里迢迢远赴中国，找到了掌管东方人爱情的神——月下老人，向他求教。<br>　　月下老人告诉丘比特，纯洁的爱情并不是不存在，而是他没有找到。在东方，人们讲究的是缘分。月下老人只要做一男一女两个泥人，在他们之间连上一条红线，那么它们所代表的人就会相爱——无论他们身处何地。而丘比特的爱情之箭只能射中两个距离相当近的人，选择的范围自然就小了很多，不能找到真正的有缘人。<br>　　丘比特听了月下老人的解释，茅塞顿开，回去之后用了人间的最新科技改造了自己的弓箭，使得丘比特之箭的射程大大增加。这样，射中有缘人的机会也增加了不少。<br>　　情人节(Valentine's day)的午夜零时，丘比特开始了自己的工作。他选择了一组数目相等的男女，感应到他们互相之间的缘分大小，并依此射出了神箭，使他们产生爱意。他希望能选择最好的方法，使被他选择的每一个人被射中一次，且每一对被射中的人之间的缘分的和最大。<br>　　当然，无论丘比特怎么改造自己的弓箭，总还是存在缺陷的。首先，弓箭的射程尽管增大了，但毕竟还是有限的，不能像月下老人那样，做到“千里姻缘一线牵”。其次，无论怎么改造，箭的轨迹终归只能是一条直线，也就是说，如果两个人之间的连线段上有别人，那么莫不可向他们射出丘比特之箭，否则，按月下老人的话，就是“乱点鸳鸯谱”了。<br>　　作为一个凡人，你的任务是运用先进的计算机为丘比特找到最佳的方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　输入文件第一行为正整数k，表示丘比特之箭的射程，第二行为正整数n(n&lt;30)，随后有2n行，表示丘比特选中的人的信息，其中前n行为男子，后n行为女子。每个人的信息由两部分组成：他的姓名和他的位置。姓名是长度小于20且仅包含字母的字符串，忽略大小写的区别，位置是由一对整数表示的坐标，它们之间用空格分隔。格式为x y Name。输入文件剩下的部分描述了这些人的缘分。每一行的格式为Name1 Name2 p。Name1和Name2为有缘人的姓名，p是他们之间的缘分值(p为小于等于255的正整数)。以一个End作为文件结束标志。每两个人之间的缘分至多只被描述一次。如果没有被描述，则说明他们缘分值为1。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　输出文件仅一个正整数，表示每一对被射中的人之间的缘分的总和。这个和应当是最大的。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>3<br>0 0 Adam<br>1 1 Jack<br>0 2 George<br>1 0 Victoria<br>0 1 Susan<br>1 2 Cathy<br>Adam Cathy 100<br>Susan George 20<br>George Cathy 40<br>Jack Susan 5<br>Cathy Jack 30<br>Victoria Jack 20<br>Adam Victoria 15<br>End</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>65</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;30</p>
<p>p为小于等于255的正整数</p>
</div>
</div>