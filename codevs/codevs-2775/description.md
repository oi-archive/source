<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Kerry 是德国的一位电缆商人。因联合国脱贫计划的邀请，他准备负责在土鲁齐亚埃萨亚克斯乌托斯邦建立电缆网络，以满足这个国家的用电需求。当然，现在土鲁齐亚埃萨亚克斯乌托斯邦没有任何电缆。已知土鲁齐亚埃萨亚克斯乌托斯邦一共有n个城镇，已经编号为1到n。其中任意两个城镇可能有一条路，也可能没有。如果两个城镇之间有一条路pi，那么这条路有一个长度si，则Kerry可以在这两个城市之间建立一条电缆线，电缆线的长度也就是这条路的长度si。<br> 现在Kerry准备了s长的电缆线，电缆线可以任意拆断，拆断不损失任何电缆线。他需要将土鲁齐亚埃萨亚克斯乌托斯邦所有城镇都能够连入这个电缆网络。那么，Kenny能不能使用这s长度的电缆线完成这项工作；如果能够完成，那么Kerry最少耗用多少长度的电缆线呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正实数S；<br> 第二行一个正整数n；<br> 接下来一共有m行，第i行有两个整数xi,yi和一个实数si，表示编号为xi个村庄和编号为yi个村庄之间有一条路，路的长度为si。<br> 输入保证xi不等于yi，两个城镇之间不会有两条路。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若能够完成（建立这样的电缆网络），则输出（其中&lt;X&gt;代表最少的电缆线长度，保留两位小数）：<br />Need &lt;X&gt; miles of cable<br />否则输出：<br />Impossible</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>100.0<br>4<br>1 2 2.0<br>1 3 4.2<br>1 4 6.7<br>3 4 4.0<br>2 4 10.0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Need 10.20 miles of cable</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n,m&lt;=100000</p>
</div>
</div>