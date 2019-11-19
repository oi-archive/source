<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小猪<span style="font-family: 'Times New Roman';">iPig</span><span style="">来到了一个叫做</span>pigsty的城市里，pigsty是一座专门为小猪所准备的城市，城市里面一共有<span style="font-family: 'Times New Roman';">n</span><span style="">个小区给小猪们居住，并且存在许多条无向边连接着许多小区。因为这里是一个和谐的城市，所以</span>小猪<span style="font-family: 'Times New Roman';">iPig</span><span style="">准备在这个城市里面度过他的余生。</span></p>
<p>若干年之后小猪<span style="font-family: 'Times New Roman';">iPig</span><span style="">当上了规划局长，这件事令他非常开心。不过与此同时</span>pigsty城市里面出现了许多反和谐主义者，他们已经厌烦了这样和谐的生活，在城市里到处闹事。小猪<span style="font-family: 'Times New Roman';">iPig</span><span style="">为了更好地控制局面，他把城市改造成了另外一个样子：</span><span style="font-family: 'Times New Roman';">iPig</span><span style="">把道路全部摧毁之后重新修建了</span><span style="font-family: 'Times New Roman';">m</span><span style="">条无向边，并且保证每一个小区最多存在于一个由无向边组成的环中。</span></p>
<p>iPig<span style="">以为这样做就让那些反和谐主义者不敢继续猖狂下去了，谁知到在新的城市道路修建好以后反和谐主义者宣言要对城市的小区进行一次洗脑！</span></p>
<p>这下可麻烦了，<span style="font-family: 'Times New Roman';">iPig</span><span style="">赶紧收集了许多的情报。</span><span style="font-family: 'Times New Roman';">iPig</span><span style="">给每个小区标记了一个和谐值</span><span style="font-family: 'Times New Roman';">HX_i</span><span style="">，用它来表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个小区的和谐程度。</span></p>
<p>通过地下消息<span style="font-family: 'Times New Roman';">iPig</span><span style="">又得知那些反和谐主义者进攻时有个规律：他们会选择若干个小区下手，这些小区都派一只猪过去，把这些小区的和谐值归零。在这个过程中，每个选择的小区所直接连接着的几个小区都派了一只猪去看守——以防被警猪给干扰。这个计划看似完美但是还是存在一个漏洞：因为人员之间都是在网络上认识的，互相没有见过面，为了防止不必要的麻烦（认错猪之类），每个小区最多只会有一头猪存在。</span></p>
<p>iPig<span style="">突然感到了莫大的压力，他想知道在最坏情况下会丢失多少和谐值。但是不懂计算机的他不知道应该怎样计算。你能帮帮他吗？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行有两个整数<span style="font-family: 'Times New Roman';">n</span><span style="">和</span><span style="font-family: 'Times New Roman';">m</span><span style="">，表示</span>pigsty城市里面有<span style="font-family: 'Times New Roman';">n</span><span style="">个小区，在</span><span style="font-family: 'Times New Roman';">iPig</span><span style="">修整城市后有</span><span style="font-family: 'Times New Roman';">m</span><span style="">条无向边连接着</span><span style="font-family: 'Times New Roman';">n</span><span style="">个小区。</span></p>
<p>接下来一行有<span style="font-family: 'Times New Roman';">n</span><span style="">个正整数，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个正整数</span><span style="font-family: 'Times New Roman';">HX_i</span><span style="">表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个小区的和谐值为</span><span style="font-family: 'Times New Roman';">HX_i</span><span style="">。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">m</span><span style="">行，每行两个正整数</span><span style="font-family: 'Times New Roman';">a</span><span style="">和</span><span style="font-family: 'Times New Roman';">b</span><span style="">（</span><span style="font-family: 'Times New Roman';">1&lt;=a,b&lt;=n</span><span style="">），表示存在一条连接着小区</span><span style="font-family: 'Times New Roman';">a</span><span style="">和小区 </span><span style="font-family: 'Times New Roman';">b</span><span style="">的无向边。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp; 输出只有一行一个整数，表示最坏情况下损失的和谐值为多少。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 9</p>
<p>2 2 3 4 1 2 3 10 11</p>
<p>1 2</p>
<p>2 3</p>
<p>1 3</p>
<p>3 5</p>
<p>5 4</p>
<p>5 6</p>
<p>4 7</p>
<p>6 7</p>
<p>8 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>【样例解释】</p>
<p>反和谐主义者选择的小区分别是小区<span style="font-family: 'Times New Roman';">3</span><span style="">（看守的小区是小区</span><span style="font-family: 'Times New Roman';">1</span><span style="">、小区</span><span style="font-family: 'Times New Roman';">2</span><span style="">和小区</span><span style="font-family: 'Times New Roman';">5</span><span style="">）、小区</span><span style="font-family: 'Times New Roman';">7</span><span style="">（看守的小区是小区</span><span style="font-family: 'Times New Roman';">4</span><span style="">和小区</span><span style="font-family: 'Times New Roman';">6</span><span style="">）和小区</span><span style="font-family: 'Times New Roman';">9</span><span style="">（看守的小区是小区</span><span style="font-family: 'Times New Roman';">8</span><span style="">），这样会损失的总和谐值为</span><span style="font-family: 'Times New Roman';">3+3+11=17</span><span style="">。</span></p>
<p>或者选择的小区分别是小区<span style="font-family: 'Times New Roman';">1</span><span style="">（看守的小区是小区</span><span style="font-family: 'Times New Roman';">2</span><span style="">和小区</span><span style="font-family: 'Times New Roman';">3</span><span style="">）、小区</span><span style="font-family: 'Times New Roman';">4</span><span style="">（看守的小区是小区</span><span style="font-family: 'Times New Roman';">5</span><span style="">和小区</span><span style="font-family: 'Times New Roman';">7</span><span style="">）和小区</span><span style="font-family: 'Times New Roman';">9</span><span style="">（看守的小区是小区</span><span style="font-family: 'Times New Roman';">8</span><span style="">），这样会损失的总和谐值为</span><span style="font-family: 'Times New Roman';">2+4+11=17</span><span style="">。</span></p>
<p>如果同时选择小区<span style="font-family: 'Times New Roman';">3</span><span style="">、小区</span><span style="font-family: 'Times New Roman';">4</span><span style="">和小区</span><span style="font-family: 'Times New Roman';">9</span><span style="">，虽然损失的总和谐值为</span><span style="font-family: 'Times New Roman';">18</span><span style="">，但是小区</span><span style="font-family: 'Times New Roman';">3</span><span style="">和小区</span><span style="font-family: 'Times New Roman';">4</span><span style="">都要派猪来看守小区</span><span style="font-family: 'Times New Roman';">5</span><span style="">，这不符合条件，故此方案不可行。</span></p>
<p> </p>
<p>【数据约定】</p>
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，保证每个点不存在于任何一个环中；</span></p>
<p>对于另外<span style="font-family: 'Times New Roman';">3</span>0%的数据，保证图中只存在一个环；</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，有</span><span style="font-family: 'Times New Roman';">N&lt;=1000000</span><span style="">，</span><span style="font-family: 'Times New Roman';">M&lt;=2000000</span><span style="">，所有的权值不超过</span><span style="font-family: 'Times New Roman';">1000</span><span style="">。</span></p>
</div>
</div>
</div>