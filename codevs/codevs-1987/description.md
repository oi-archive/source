<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Candyfand有一座糖果公园，公园里不仅有美丽的风景、好玩的游乐项目，还有许多免费糖果的发放点，这引来了许多贪吃的小朋友来糖果公园游玩。</p>
<p>糖果公园的结构十分奇特，它由n个游览点构成，每个游览点都有一个糖果发放处，我们可以依次将游览点编号为1至n。有n一1条双向道路连接着这些游览点，并且整个糖果公园都是联通的，即从任何一个游览点出发都可以通过这些道路到达公园里的所有其它游览点。<br>糖果公园所发放的糖果种类非常丰富，总共有m种，它们的编号依次为1至m。每一个糖果发放处都只发放某种特定的糖果，我们用Ci来表示i号游览点的糖果。<br>来到公园里游玩的游客都不喜欢走回头路，他们总是从某个特定的游览点出发前往另一个特定的游览点，并游览途中的景点，这条路线一定是唯一的。他们经过每个游览点，都可以品尝到一颗对应种类的糖果。<br>大家对不同类型糖果的喜爱程度都不尽相同。根据游客们的反馈打分，我们得到了糖果的美味指数，第i种糖果的美味指数为Vi。另外，如果一位游客反复地品尝同一种类的糖果，他肯定会觉得有一些腻。根据量化统计，我们得到了游客第i次品尝某类糖果的新奇指数Wi。如果一位游客第i次品尝第j种糖果，那么他的愉悦指数H将会增加对应的美味指数与新奇指数的乘积，即VjWi。这位游客游览公园的愉悦指数最终将是这些乘积的和。<br>当然，公园中每个糖果发放点所发放的糖果种类不一定是一成不变的。有时，一些糖果点所发放的糖果种类可能会更改（也只会是m种中的一种），这样的目的是能够让游客们总是感受到惊喜。<br>糖果公园的工作人员小A接到了一个任务，那就是根据公园最近的数据统计出每位游客游玩公园的愉悦指数.但数学不好的小A一看到密密麻麻的数字就觉得头晕，作为小A最好的朋友，你决定帮他一把。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含三个正整数n,m,q，分别表示游览点个数、糖果种类数和操作次数。<br>第二行包含m个正整数V1,V2,…,Vm<br>第三行包含n个正整数W1,W2,…,Wn<br>第四行到第n+2行，每行包含两个正整数Ai,Bi，表示这两个游览点之间有路径可以直接到达。<br>第n+3行包含n个正整数Cl,C2，…，Cn。<br>接下来q行，每行包含三个整数Type,x,y，表示一次操作：<br>若Type为O，则l≤x≤n,1≤y≤m，表示将编号为x的游览点发放的糖果类型改为y;<br>若Type为1，则1≤x,y≤n，表示对出发点为x，终止点为y的路线询问愉悦指数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>按照输入的先后顺序,对于每个Type为1的操作输出一行，用一个正整数表示答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 5<br>1 9 2<br>7 6 5 1<br>2 3<br>3 1<br>3 4<br>1 2 3 2<br>1 1 2<br>1 4 2<br>0 2 1<br>1 1 2<br>1 4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>84<br>131<br>27<br>84</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于所有的数据，1≤Vi,Wi≤10^6，1≤Ai,Bi≤n，1≤Ci≤m，W1,W2,…,Wn是非递增序列。</p>
</div>
</div>