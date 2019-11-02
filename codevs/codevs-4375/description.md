<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>xdz 觉得树是一种非常神秘、美妙的东西。所以他提出了一个他<br>认为无人能做的题目给你一棵初始根为 1 的有根树,每个节点有一个<br>权值让你维护以下几个操作。<br>1、将树根换为 x<br>2、将一个节点权值改为 v<br>3、询问一个子树中的所有节点的最小值。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行两个数 n,T, 表示树的节点个数和操作总数<br>接下来 n 行,<br>第 i 行两个数 x,y,表示 i 结点的父亲为 x,权值为 y。节点 1 的<br>父亲为 0,且保证开始时每个节点的父亲标号小于他自己。<br>在接下来 T 行<br>每行第一个读入一个字符 opt 表示操作类型<br>opt<br>如果 opt=“E”,再读入一个数 x,表示将树的根节点换为 x。<br>如果 opt=“V”,再读入两个数 x,v,表示将标号 x 节点值换为 v。<br>如果 opt=“Q”,再读入一个数 x,表示询问 x 节点为根的子树。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若干行,依次表示对每个询问的回答。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 8</p><p>0 1</p><p>1 2</p><p>1 3</p><p>Q 1</p><p>V 1 6</p><p>Q 1</p><p>V 2 5</p><p>Q 1</p><p>V 3 4</p><p>E 3</p><p>Q 1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p><p>2</p><p>3</p><p>5<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>测试点<br>1、2 数据规模n&lt;=1000,T&lt;=1000 <br></p><p>3、4 n&lt;=100000,T&lt;=100000 树为一条链<br>5、6、7、8 n&lt;=100000,T&lt;=100000 树的形态随机,换根操作个数不超过 20<br>9、10 n&lt;=100000,T&lt;=100000 没有换根操作<br>11、12 n&lt;=200000,T&lt;=200000 没有换根操作<br>13、14 n&lt;=100000,T&lt;=100000 无<br>15、16 n&lt;=200000,T&lt;=200000 无<br>17、18 n&lt;=500000,T&lt;=500000 无<br>19、20 n&lt;=1000000,T&lt;=1000000 无</p><p>所有权值不超过long long，且为正整数<br></p>
</div>
</div>