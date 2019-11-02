<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在物质发达</span>A<span style="">国首都，有着若干个公司。其中有着一个叫做</span>WAKA<span style="">的公司，这个公司的老板</span>Mr.Li<span style="">是你的中学同学，你来到他的公司，正准备好好玩耍时，</span>Mr.Li<span style="">抓住了你的手</span>……</p><p style=""><span style="">事情是这样的，在他的公司中，有着</span>n<span style="">个员工，在这些员工之中，两两之间都有着“互利共赢”的关系，表示这两个员工可以在事业上互相帮助，而这样的关系一共有</span>m<span style="">条。</span></p><p style=""><span style="">当然，</span>Mr.Li<span style="">的员工都是些心高气傲的人，他们之间的互相帮助也是要收取代价的，并且他们觉得他们帮助过的人没有他们优越，而他们又绝对不会容忍不优越的人来帮助自己，即使代价很低。当然，在还没有互相帮助的时候，彼此之间的关系还是十分融洽的，并没有人觉得自己比别人优越。</span></p><p style=""><span style="">当然，</span>Mr.Li<span style="">的员工都是些很有才华的人，他们在公司之外结实了各种各样的人，如果向这人求取帮助所需花费可能更少。这样的帮助所需代价全都为</span>d<span style="">，这样的人很多，根本不愁找不到。当然，如果公司中也有代价为</span>d<span style="">且满足条件的人，则优先选择公司中的。</span></p><p style=""><span style="">一号总是那么臭屁，他只能容忍外援。</span></p><p style=""><span style="">当然，</span>Mr.Li<span style="">的员工都是些狡诈的人，他们在互相帮助后都会向上司提出要“报账”的申请，而公司希望所有员工都有人来帮助，因此公司的支出大大提高。</span>Mr.Li<span style="">满脸愁容的望着你，希望你给予他帮助。</span></p><p style=""><span style="">要求：在满足条件的情况下，求最小代价。</span></p><p style=""><span style="">这样就完了吗？当然没有。</span></p><p style=""><span style="">在</span>Mr.Li<span style="">的一再要求下，所有有关系的员工都组成一个块，统一管理，</span>Mr.Li<span style="">又给出了以下定义：</span></p><p style=""><strong><span style="">【块】：</span></strong><span style="">几个或者一个员工有帮助关系，则统一起来，集合成一个块，统一处理。</span></p><p style=""><strong><span style="">【块的和】：</span></strong><span style="">在一个块里的所有员工的代价和（当然是最优情况下）。</span></p><p style=""><strong><span style="">【块的编号】：</span></strong><span style="">块的编号从</span>1<span style="">开始，之后依次递增，编号按照块中编号最小的员工的编号来编号。</span></p><p style=""><span style="">【<strong>块的最小值】：</strong>块中员工的代价的最小值。</span></p><p style=""><span style="">【</span><strong>Mr.Li</strong><strong><span style="">和】：</span></strong><span style="">对于一段个数为</span>n<span style="">的块区间，有</span></p><p style=""><span style=""></span>∑（i=1 i&lt;=n）∑(j=1 j&lt;=C(i,n)) (-1)^(i+n) ∏(k=1;k&lt;=i) aq(q∈[1,n])  (没有图片我也很痛苦啊，试了好久都不行)</p><p style="">如：n=1 展开为 a1。</p><p style="">     n=2 展开为 a1a2-a1-a2。</p><p style=""><span style=""></span>其中，每个组合中aq不重复，每一个组合不重复。</p><p style=""><span style="">其中，</span>aq<span style="">为块的和，</span>a1a2a3<span style="">和</span>a2a3a1<span style="">算作重复。</span></p><p style=""><span style="">在这样的定义下，有了这样几个操作：</span></p><p style=""><strong>M </strong><strong><span style="">：</span></strong><strong>a  c</strong>   <span style="">块</span>a<span style="">的所有员工代价都加上</span>c,<span style="">最小值也相应变化。</span></p><p style=""><strong>A </strong><strong><span style="">：</span></strong><strong>a  b</strong>  <span style="">查询块区间</span>[a,b]<span style="">上的块的和的和。由于其值很大，要</span>mod 1000000007</p><p style=""><strong>Q </strong><strong><span style="">：</span></strong><strong>a  b</strong>  <span style="">查询块区间</span>[a,b]<span style="">中员工代价的最小值。</span></p><p style=""><strong>Y </strong><strong><span style="">：</span></strong><strong>a  b</strong>  <span style="">查询块区间</span>[a,b]<span style="">中的</span>Mr.Li<span style="">和。由于其值很大，要</span>mod 1000000007</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行有三个整数<span style="font-family: Times New Roman;">n,m,d</span><span style="">。表示人数，关系数和外援代价。其后</span><span style="font-family: Times New Roman;">m</span><span style="">行每行有三个整数</span><span style="font-family: Times New Roman;">a,b,c</span><span style="">。表示</span><span style="font-family: Times New Roman;">a,b可以</span><span style="">互相帮助，代价为</span><span style="font-family: Times New Roman;">c</span><span style="">。即：a帮助b为c；b帮助a也为c。之后一行一个整数</span><span style="font-family: Times New Roman;">k,</span><span style="">表示操作个数，之后</span><span style="font-family: Times New Roman;">k</span><span style="">行分别为一个操作。</span></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style=";font-family:宋体;font-size:14px">对于每一个询问，输出一个答案，一个答案一行，输出完毕后，有一个多余的空行。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">6   8   4</span></p><p><span style="">1   2   1</span></p><p><span style="">1   3   7</span></p><p><span style="">2   3   4</span></p><p><span style="">2   4   5</span></p><p><span style="">2   5   3</span></p><p><span style="">3   5   2</span></p><p><span style="">4   6   2</span></p><p><span style="">5   6   7</span></p><p><span style="">9</span></p><p><span style="">Q   1   2</span></p><p><span style="">A   1   2</span></p><p><span style="">Q   2   2</span></p><p><span style="">Y   1   2</span></p><p><span style="">M   1   2</span></p><p><span style="">Q   1   2</span></p><p><span style="">Q   2   2</span></p><p><span style="">A   1   1</span></p><p><span style="">Y   2   2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">1</span></p><p><span style="">16</span></p><p><span style="">2</span></p><p><span style="">44</span></p><p><span style="">2</span></p><p><span style="">2</span></p><p><span style="">18</span></p><p><span style="">6</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于<span style="font-family: Times New Roman;">10%</span><span style="">的数据：</span><span style="font-family: Times New Roman;">0&lt;=n&lt;=100 , 0&lt;=m&lt;=1000 , 0&lt;=k&lt;=100</span><span style="">。</span></span></p><p><span style="">对于<span style="font-family: Times New Roman;">30%</span><span style="">的数据：</span><span style="font-family: Times New Roman;">0&lt;=n&lt;=1000 , 0&lt;=m&lt;=10000 , 0&lt;=k&lt;=1000</span><span style="">。</span></span></p><p><span style="">对于另外<span style="font-family: Times New Roman;">10%</span><span style="">的数据：没有</span><span style="font-family: Times New Roman;">Y</span><span style="">操作。</span></span></p><p><span style="">对于另外<span style="font-family: Times New Roman;">10%</span><span style="">的数据：没有</span><span style="font-family: Times New Roman;">M</span><span style="">操作。</span></span></p><p><span style="">对于另外<span style="font-family: Times New Roman;">10%</span><span style="">的数据：没有</span><span style="font-family: Times New Roman;">Y</span><span style="">和</span><span style="font-family: Times New Roman;">M</span><span style="">操作。</span></span></p><p><span style="">对于另外<span style="font-family: Times New Roman;">10%</span><span style="">的数据：只有一个块。</span><span style="font-family: Times New Roman;">0&lt;=n&lt;=500000, 0&lt;=m&lt;=700000, 0&lt;=k&lt;=700000</span><span style="">。</span></span></p><p><span style="">对于其余数据：<span style="font-family: Times New Roman;">0&lt;=n&lt;=200000 , 0&lt;=m&lt;=400000 </span><span style="">，</span><span style="font-family: Times New Roman;">0&lt;=k&lt;=300000(</span><span style="">除了只有一个块的数据</span><span style="font-family: Times New Roman;">)</span><span style="">。</span></span></p><p><span style="">对于<span style="font-family: Times New Roman;">100%</span><span style="">的数据：</span><span style="font-family: Times New Roman;">0&lt;=n&lt;=500000 , 0&lt;=m&lt;=700000 </span><span style="">，</span><span style="font-family: Times New Roman;">0&lt;=k&lt;=700000 , 0&lt;=a,b&lt;=n </span><span style="">，</span><span style="font-family: Times New Roman;">0&lt;c,d&lt;=1000000000</span><span style="">。</span></span></p><p><br></p>
</div>
</div>