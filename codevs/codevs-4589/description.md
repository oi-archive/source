<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""></span></p><p style=""><span style=""></span></p><p style=""><span style="">每到周末，我们的兄弟学校就有多彩的社团活动，然而，在三十三个社团热火朝天的活动背后，也许是三十三项堆积如山的作业。（我夸张了，也许没有<span style="font-family: Calibri;">33</span><span style="">项，但写满一黑板绝对无压力）</span></span></p><p style=""><span style="">可怜的<span style="font-family: Calibri;">XHY</span><span style="">同学也难免深受其害。她给</span><span style="font-family: Calibri;">CYD</span><span style="">大神看了作业短信，足足写满了两条。然而，在令人绝望的一行行文字中，还藏着一点希望：“（周三交）”</span></span></p><p style=""><span style="">CYD<span style="">大神很同情她，于是想帮她减轻一点负担（毕竟他们初中时都能在新西兰惠灵顿时间凌晨两点睡觉）。老师仅有的一点仁慈，给了她使用缓兵之计的条件。她一共有</span><span style="font-family: Calibri;">N</span><span style="">项作业，每项需要</span><span style="font-family: Calibri;">Ti</span><span style="">时间完成，并且要在</span><span style="font-family: Calibri;">Bi</span><span style="">天之内（含）上交。她是个认真的孩子，为了提升作业质量，她每天都只会做一项作业的一部分或全部，而且每天花的时间只会是整数（不要问我为什么，这是她的习惯）。</span></span></p><p style=""><span style="">CYD<span style="">大神想帮她写一个程序，合理分配作业，使得她能按时完成所有作业，并且使每天做作业的最长时间最短。请你帮他完成这个程序，求出这个最短的最长时间。如果不可能完成所有作业，输出“</span><span style="font-family: Calibri;">XYSTDFH</span><span style="">”（小猿搜题大法好）。</span></span></p><p style=""><span style=""><span style=""></span></span><br></p><p style=""><span style=""></span><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""></span></p><p style=""><span style="">第一行，一个正整数<span style="font-family: Calibri;">N</span><span style="">。</span></span></p><p style=""><span style="">之后<span style="font-family: Calibri;">N</span><span style="">行，每行两个空格隔开的正整数</span><span style="font-family: Calibri;">Ti  Bi</span><span style="">。</span></span></p><p style=""><span style=""><span style=""></span></span><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体;font-style: italic;font-size: 16px"></span></p><p style="text-indent:28px"><span style="font-family: 宋体;font-size: 16px"></span></p><p style="text-indent:28px"><span style="font-family: 宋体;font-size: 16px">一行，一个</span><span style="font-family: 宋体;font-size: 16px">正整数表示最短的最长时间。</span></p><p style="text-indent:28px"><span style="font-family: 宋体;font-size: 16px"><span style="font-family:宋体"></span></span><br/></p><p><span style="font-family: 宋体;font-size: 16px"><span style="font-family:宋体"></span></span><br/></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">#1</span></p><p><span style="">2<br></span></p><p><span style="">10 1</span></p><p><span style="">2 1</span></p><p><span style=""><br></span>#2</p><p><span style="">4</span></p><p><span style="">4 3</span></p><p><span style="">2 4</span></p><p><span style="">5 5</span></p><p><span style="">1 2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">#1</span></p><p><span style=""></span></p><p><span style="">XYSTDFH</span></p><p><span style=""></span><br></p><p>#2</p><p>4</p><p><br></p><p><span style=""><br></span></p><p><span style="">/*-----以下为解释-----*/</span></p><p style=""><span style=""></span></p><p><span style="">样例</span><span style="">1:<span style="">一天不能做两项作业。</span></span></p><p><span style="">样例<span style="font-family: Calibri;">2:</span><span style="">第一天做</span><span style="font-family: Calibri;">1</span><span style="">，第二天做</span><span style="font-family: Calibri;">4</span><span style="">，第三天做</span><span style="font-family: Calibri;">2</span><span style="">，四五两天平分</span><span style="font-family: Calibri;">5</span><span style="">（</span><span style="font-family: Calibri;">2+3</span><span style="">）。</span></span></p><p style=""><span style=""><span style=""></span></span><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style=""></span></p><p><span style="">对于</span><span style="">10%<span style="">数据，</span><span style="font-family: Calibri;">N=1</span><span style="">。</span></span></p><p><span style="">另有<span style="font-family: Calibri;">10%</span><span style="">数据，</span><span style="font-family: Calibri;">Bi=i</span><span style="">。</span></span></p><p><span style="">另有<span style="font-family: Calibri;">10%</span><span style="">数据，</span><span style="font-family: Calibri;">Ti=1</span><span style="">。</span></span></p><p><span style="">另有<span style="font-family: Calibri;">10%</span><span style="">数据，</span><span style="font-family: Calibri;">Ti&lt;=2,Bi&lt;=20.</span></span></p><p><span style="">另有<span style="font-family: Calibri;">20%</span><span style="">数据，</span><span style="font-family: Calibri;">Ti&lt;=200,Bi&lt;=300.</span></span></p><p><span style="">对于<span style="font-family: Calibri;">70%</span><span style="">数据，</span><span style="font-family: Calibri;">N&lt;=2000</span><span style="">。</span></span></p><p><span style="">对于全部数据，<span style="font-family: Calibri;">N&lt;=50000,Ti,Bi&lt;=10^9</span><span style="">。</span></span></p><p><span style=""></span><br></p><p><br></p>
</div>
</div>