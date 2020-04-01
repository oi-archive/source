<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>果园里有<em>n</em>颗果树，每棵果树都有一个编号<em>i</em>(1≤<em>i</em>≤<em>n</em>)。小明已经把每棵果树上的果子都摘下来堆在了这棵树的下方，每棵树下方的果子体积为<em>a<sub>i</sub></em>。</p>
<p>现在小明将拿来<em>m</em>个袋子把这些果子都装进袋子里。每个袋子的体积为<em>v</em>。小明会按照如下规则把果子装进袋子里：</p>
<p>(a)从第1棵果树开始装起，由1到<em>n</em>一直装到第<em>n</em>棵果树。</p>
<p>(b)如果这棵果树下的果子能全部装进当前这个袋子，就装进去；如果不能，就关上当前这个袋子，打开一个新的袋子开始装。</p>
<p><strong>小明希望在能把所有果子都装进袋子里的前提下，<em>v</em>尽量小。<em>m</em>个袋子并不一定都要装进果子。</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第1行，包含两个整数<em>n</em>和<em>m</em>。</p>
<p>第2行，包含<em>n</em>个整数<em>a<sub>i</sub></em>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅1行，表示最小的<em>v</em>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>#1</p>
<p>3 3</p>
<p>1 2 3</p>
<p>#2</p>
<p>5 3</p>
<p>1 3 6 1 7</p>
<p>#3</p>
<p>6 3</p>
<p>1 2 1 3 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>#1</p>
<p>3</p>
<p>#2</p>
<p>7</p>
<p>#3</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例解释1】</p>
<p>每个袋子的体积为3即可。前2棵果树的果子装在第一个袋子里，第3棵果树的果子装在第二个袋子里。第三个袋子不用装了。</p>
<p> </p>
<p>【输入输出样例解释2】</p>
<p>每个袋子的体积为7即可。前2棵果树的果子装在第一个袋子里，此时第一个袋子已经装了4单位体积的果子，第3棵果树的果子装不下了，所以装进第二个袋子里，第4棵果树的果子刚好装进第二个袋子，第5棵果树的果子装进第三个袋子里。</p>
<p> </p>
<p> 【输入输出样例解释3】</p>
<p>每个袋子的体积为4即可。前3棵果树的果子装在第一个袋子里，第4~5棵果树的果子装在第二个袋子里，第6棵果树的果子装在第三个袋子里。</p>
<p> 【数据范围】</p>
<p>对于40%的数据，0&lt;<em>m</em>≤<em>n</em>≤1,000，0&lt;<em>a<sub>i</sub></em>≤1,000；</p>
<p>对于70%的数据，0&lt;<em>m</em>≤<em>n</em>≤100,000，0&lt;<em>a<sub>i</sub></em>≤100,000；</p>
<p>对于100%的数据，0&lt;<em>m</em>≤<em>n</em>≤100,000，0&lt;<em>a<sub>i</sub></em>≤1,000,000,000。</p>
</div>
</div>