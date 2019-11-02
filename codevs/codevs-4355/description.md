<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="text-decoration: line-through;">/*</span><span style="text-decoration: line-through;">在神秘而遥远的T</span><span style="text-decoration: line-through;">国度生活着一群神奇的物种——DD</span><span style="text-decoration: line-through;">！</span></p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="text-decoration: line-through;">DD</span><span style="text-decoration: line-through;">们有着独特的生活习惯，他们总是喜欢居住在tree</span><span style="text-decoration: line-through;">上，而且只有上层住了DD</span><span style="text-decoration: line-through;">下层才能再住。并且每层住的DD</span><span style="text-decoration: line-through;">最多不超过2n<sup>2</sup></span><span style="text-decoration: line-through;">个。。。</span></p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="text-decoration: line-through;">这一天，DD</span><span style="text-decoration: line-through;">跳下来了！（也就是说刚才的条件一点用都没有~_~</span><span style="text-decoration: line-through;">）*/</span></p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">他们遇到了一只自称为S的dd。但是本身性质为S的DD们不服，于是他们决定进行摔跤，摔跤获胜者成为王！<br></p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">（由于DD和dd们的精力无限，所以每一只DD&amp;&amp;dd都会同另一部落的每一个人进行一次摔跤）两阵营分别有n，m只DD和dd，并且每阵营按照1~n和1~m进行体力值分配（体力值同序号相同）</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">进行比赛时，双方中体力值较大一方会减去另一方的体力值使之作为自己的新体力值，但由于DD和dd们实力雄厚，因此只有当双方的体力值相同时才会停止摔跤。如果此时双方的体力值是一个纯洁的数字，DD和dd会很高兴地退场，并且将这个数作为这场比赛的得分~~~，但如果只是一般的数字，他们会不开心地退场导致这场比赛没有得分。因为DD和dd作为T团队不可或缺的一员，所以获得的分数会加入T团队的总分（一场只有一个得分，不要以为你们是两个人，就可以得两遍分啊！！！）</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">输出T团队最后获得的总分，数据有多组询问。</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">注：纯洁的数字即最后的这个值没有次幂高于1的因子（SFN，无平方因子数）</span></p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><br></span></p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">一句话题意：i从1到n,j从1到m,如果gcd(i,j)为sfn,那么就加起来，求最终答案……</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">第一行一个正整数N表示一共N组数据，接下来N行每行两个正整数n，m</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: &#39;Microsoft YaHei UI&#39;, &#39;Microsoft YaHei&#39;, &#39;Segou UI&#39;; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);">输出有N行，每行一个正整数，表示T团队的总分</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">1 </span><br style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">5 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">33</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">对于样例：</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">1 代表一组数据；</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">下面1行两个数5 5</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">1和1~5摔跤；2和1~5摔跤；3和1~5摔跤；4和1~5摔跤；5和1~5摔跤；</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">1和任何人摔跤返回的得分总是1，因为1是最小的。</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">2和1摔跤得1,2和2摔跤得2,2和3摔跤得1,2和4摔跤得2,2和5摔跤得1；</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">3和1摔跤得1；3和2摔跤得1；3和3摔跤得3；3和4摔跤得1；3和5摔跤得1；</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">4和1摔跤得1；4和2摔跤得2；4和3摔跤得1；4和4摔跤得4；5和4摔跤得1；</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">5和1摔跤得1；5和2摔跤得1；5和3摔跤得1；5和4摔跤得1；5和5摔跤得5；</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">最后把满足square free number的数加起来（4不是square free number）</p><p><br style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">30%的数据：N&lt;=10,n&lt;=m&lt;=1000</span><br style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">60%的数据： N&lt;=300,n&lt;=m&lt;=600000</span><br style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">100%的数据： N&lt;=10000,n&lt;=m&lt;=1500000</span></p><p><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">请尽可能水分~</span></p>
</div>
</div>