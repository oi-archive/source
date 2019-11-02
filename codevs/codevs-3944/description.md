<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在不为人知的幻影里，存在着一群幻影世界。幻影阁有着守护幻影世界群的职责，拥有连接不同幻影世界的能力，Rainbow</span><span style=""></span><span style="">王国和Freda</span><span style="">王国就存在于不同的幻影世界，通过幻影阁这个中转站进行友好地交流。</span></p><p style=""><span style="">有一天，他们向幻影阁提出了为两国建立点对点传送门的请求，然而幻影阁每天要处理数量达long long</span><span style="">级别的事务，幻影阁只能帮助两个王国建立一个传送门，如何在两个王国内选择一对合适的城市成了两国商讨的重点。</span></p><p style=""><span style=""><span style=""></span></span><span style="">Rainbow王国有n</span><span style=""></span><span style="">个互相可达的城市，编号1</span><span style=""></span><span style="">到n</span><span style=""></span><span style="">，n</span><span style=""></span><span style="">个城市之间由n-1</span><span style=""></span><span style="">条双向通行的道路连接，通过每条道路都相应地需要花费一定的时间。同样地，<span style="">Freda</span></span><span style=""></span><span style="">王国有m</span><span style=""></span><span style="">个互相可达的城市，编号1</span><span style="">到m</span><span style=""></span><span style="">，</span><span style=""></span><span style="">个城市之间由m-1</span><span style=""></span><span style="">条双向通行的道路连接，通过每条道路都相应地需要花费一定的时间。传送门可以在两个王国之间双向地通行，两端分别固定在两个国家的某个城市，通过传送门也需要花费一定的时间。</span></p><p style=""><span style="">这些时间是早已经测算好的，两国之间还存在两个问题：</span></p><ol style=""><li><p style="FONT-WEIGHT: normal;"><span style="">最好的一个建立传送门的策略能使这n+m</span><span style=""></span><span style="">个城市中从一个城市到达另一个城市的最长时间变得有多短？</span></p></li><li><p style=""><span style="">如果从Rainbow</span><span style=""></span><span style="">王国等概率地选一个城市，再从Freda</span><span style=""></span><span style="">王国等概率的选一个城市，以这两个城市为端点建立传送门，这n+m</span><span style=""></span><span style="">个城市中从一个城市到达另一个城市的最长时间期望是多少？</span></p></li></ol><p style=""><span style="">幻影阁都觉得这个问题很简单，于是把问题交给了你。</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行三个正整数n,m</span><span style=""></span><span style="">和t</span><span style=""></span><span style="">，分别表示Rainbow</span><span style=""></span><span style="">王国和Freda</span><span style=""></span><span style="">王国的城市数量，以及通过传送门花费的时间。</span></p><p style=""><span style="">接下来n+m-2</span><span style=""></span><span style="">行，每行三个正整数u,v</span><span style=""></span><span style="">和w</span><span style=""></span><span style="">，表示从城市u</span><span style=""></span><span style="">到城市v</span><span style=""></span><span style="">需要w</span><span style=""></span><span style="">个单位时间，其中前n-1</span><span style=""></span><span style="">行描述的是Rainbow</span><span style="">王国的道路情况，后m-1</span><span style=""></span><span style="">行描述的是Freda</span><span style="">王国的道路情况。</span></p><p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体">第一行一个正整数ans1</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">，表示第一个问题的答案。</span></p><p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体">第二行一个正最简分数ans21/ans22</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">，表示第二个问题的答案ans2=ans21/ans22</span><span style="FONT-FAMILY: 宋体">，其中ans21</span><span style="FONT-FAMILY: 宋体">和ans22</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">互质，ans22</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">等于1</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">时不省略。</span></p><p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">1 5 1</span></p><p style=""><span style="">1 2 1</span></p><p style=""><span style="">2 3 1</span></p><p style=""><span style="">3 4 1</span></p><p style=""><span style="">4 5 1</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">4</span></p><p style=""><span style="">22/5</span></p><p style=""><span style=""><span style=""><br></span></span></p><p style=""><span style="">【样例解释】</span></p><p><span style=""></span></p><p style=""><span style=""><br></span></p><p style=""><span style=""><span style=""></span></span><span style="">Rainbow王国有1</span><span style=""></span><span style="">个城市，Freda</span><span style="">王国有5</span><span style=""></span><span style="">个城市，则必然选择Rainbow</span><span style=""></span><span style="">王国的城市</span><span style=""></span><span style="">1作为传送门的一端，而对<span style="">于</span>Freda</span><span style="">王国的每个城市作为传送门的另一端，分别会使这6</span><span style=""></span><span style="">个城市之间一个到另一个移动的最长时间变成{5,4,4,4,5}</span><span style="">，于是ans1=min{5,4,4,4,5}=4</span><span style=""></span><span style="">，而ans2=(5+4+4+4+5)/(1*5)=22/5</span><span style="">。</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于20%</span><span style=""></span><span style="">的数据，有n,m≤50</span><span style="">。</span></p><p style=""><span style="">对于40%</span><span style=""></span><span style="">的数据，有n,m<span style="">≤</span>500</span><span style="">。</span></p><p style=""><span style="">对于60%</span><span style=""></span><span style="">的数据，有n,m<span style="">≤</span>5000</span><span style=""></span><span style="">。  </span></p><p><span style="">    对于100%</span><span style=""></span><span style="">的数据，有n,m<span style="">≤</span>200000,t,w<span style="">≤</span>min{1000,4*10<sup>6</sup>/max{n,m}。</span></p><p> </p>
</div>
</div>