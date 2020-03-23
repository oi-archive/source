# 题目描述


# 题目背景


<p>参加完IOI2018之后就是姚班面试。而你，由于讨厌物理、并且想成为乔布斯一样的创业家，被成功踢回贵系。</p>
<p>转眼，时间的指针被指向2019，大二，12月初，考试周。</p>
<p>你早听学长说，数据结构期中考很难，对竞赛生不友好，集训队选手做不完卷子。</p>
<p>你冷笑。哼，堂堂国际金，这点难度的考试算什么。</p>
<p>两小时，你看完习题解析前五章所有内容，并且倒背如流；</p>
<p>一小时，你看了500页的讲义，并且记忆犹新；</p>
<p>十分钟，你骑车到考场，自信的你只带了一把水笔，虽然考试让带资料；</p>
<p>现在，摊开传说中神级卷子，你定神一看——</p>

# 题目描述


<p>给出一个长度为$N$的序列$A_{1},A_{2},\cdots,A_{N}$，如果$A$中的一个子序列$B_1,B_2,\cdots,B_M$，满足条件：</p>
<ul><li>$1\le M\le N$</li>
<li>$\forall 1\le i &lt; M$，$B_i\Big{|}B_{i+1}$</li>
</ul><p>那么称$B$为$A$的<code>上升倍数子序列</code>。</p>
<p>现在有一个长度为 $N$ 的序列 $A$ 被初始化为$A_{1},A_{2},\cdots,A_{N}$，以及$Q$次对序列$A$的操作。此处要求实现如下四种操作：</p>
<ul><li><code>0 x</code>：在序列$A$的最左端插入一个数字$x$；</li>
<li><code>1 x</code>：在序列$A$的最右端插入一个数字$x$；</li>
<li><code>2</code>：移除序列$A$最左端的一个数字；</li>
<li><code>3</code>：移除序列$A$最右端的一个数字；</li>
</ul><p>在初始化序列$A$和<strong>每次</strong>操作之后，请计算此时序列$A$中<strong>最长</strong>上升倍数子序列的长度MaxLen，以及所有长度为MaxLen的上升倍数子序列的不同的开头数Cnt，输出MaxLen和Cnt。</p>
<p>为了大幅度降低题目难度，保证在<strong>任意时刻</strong>序列$A$<strong>非空</strong>，其中的元素<strong>互不相等</strong>，并且均为$1\sim M$之间的正整数；同一个数字最多只会被插入$C$次。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入第一行包含三个正整数 $N,M,Q$，具体含义见上，保证 $1\le N \le 10^{5}$，$N\le M \le 10^{6}$，$0\le Q \le 10^{5}$；</p>
<p>输入第二行包含$N$个正整数，为$A_1,A_2,\cdots,A_N$，保证$1\le A_i\le M$，并且序列$A$中的元素互不相等；</p>
<p>接下来共$Q$行输入，每行输入格式形如<code>0 x</code>或者<code>1 x</code>或者<code>2</code>或者<code>3</code>，具体含义见上。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出共$Q+1$行，在初始化和每次对序列$A$操作后，输出$A$中最长上升倍数子序列的长度MaxLen和所有长度为MaxLen的上升倍数子序列的不同的开头数Cnt，用一个空格隔开。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">5 10 10
1 2 5 9 10
2
1 7
3
3
0 8
3
2
1 8
3
0 3</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">3 1
2 2
2 2
2 2
1 3
1 4
1 3
1 2
2 1
1 2
1 3</code></pre>
<h4>explanation</h4>
<p>表格中以<code>//</code>隔开不同开头的最长上升子序列。</p>
<table class="table table-bordered"><thead><tr><th rowspan="1">操作次数</th><th rowspan="1">$A$</th><th rowspan="1">输出答案</th><th rowspan="1">可能的解释</th></tr></thead><tbody><tr><td rowspan="1">0</td><td rowspan="1">1 2 5 9 10</td><td rowspan="1">3 1</td><td rowspan="1">1 2 10</td></tr><tr><td rowspan="1">1</td><td rowspan="1">2 5 9 10  </td><td rowspan="1">2 2</td><td rowspan="1">2 10//5 10</td></tr><tr><td rowspan="1">2</td><td rowspan="1">2 5 9 10 7</td><td rowspan="1">2 2</td><td rowspan="1">2 10//5 10</td></tr><tr><td rowspan="1">3</td><td rowspan="1">2 5 9 10  </td><td rowspan="1">2 2</td><td rowspan="1">2 10//5 10</td></tr><tr><td rowspan="1">4</td><td rowspan="1">2 5 9     </td><td rowspan="1">1 3</td><td rowspan="1">2//5//9</td></tr><tr><td rowspan="1">5</td><td rowspan="1">8 2 5 9   </td><td rowspan="1">1 4</td><td rowspan="1">2//5//8//9</td></tr><tr><td rowspan="1">6</td><td rowspan="1">8 2 5     </td><td rowspan="1">1 3</td><td rowspan="1">2//5//8</td></tr><tr><td rowspan="1">7</td><td rowspan="1">2 5       </td><td rowspan="1">1 2</td><td rowspan="1">2//5</td></tr><tr><td rowspan="1">8</td><td rowspan="1">2 5 8     </td><td rowspan="1">2 1</td><td rowspan="1">2 8</td></tr><tr><td rowspan="1">9</td><td rowspan="1">2 5       </td><td rowspan="1">1 2</td><td rowspan="1">2//5</td></tr><tr><td rowspan="1">10</td><td rowspan="1">3 2 5     </td><td rowspan="1">1 3</td><td rowspan="1">2//3//5</td></tr></tbody></table>
# 限制与约定


<p>对于所有的数据，有 $1\le N \le 10^{5}$，$N\le M \le 10^{6}$，$0\le Q \le 10^{5}$，$1\le A_i\le M$，$C= 10$。</p>
<p>下表展示了某些数据点的一些特殊约束，其中<code>只有1</code>表示只有形如<code>1 x</code>的操作，其他表述同理。</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">约束条件</th></tr></thead><tbody><tr><td rowspan="1">1,2,3</td><td rowspan="1">$N,Q\le 100$</td></tr><tr><td rowspan="1">4,5</td><td rowspan="1">$N,Q\le 1000$</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$N=M\le 1000$</td></tr><tr><td rowspan="1">7</td><td rowspan="1">$Q=0$</td></tr><tr><td rowspan="1">8</td><td rowspan="1">只有0</td></tr><tr><td rowspan="1">9</td><td rowspan="1">只有1</td></tr><tr><td rowspan="1">10</td><td rowspan="1">只有2</td></tr><tr><td rowspan="1">11,12</td><td rowspan="1">只有3</td></tr><tr><td rowspan="1">13</td><td rowspan="1">只有0和1</td></tr><tr><td rowspan="1">14,15</td><td rowspan="1">只有0和2</td></tr><tr><td rowspan="1">16</td><td rowspan="1">只有1和3</td></tr><tr><td rowspan="1">17</td><td rowspan="1">只有2和3</td></tr><tr><td rowspan="1">18,19,20</td><td rowspan="1">无限制</td></tr></tbody></table><p><strong>时间限制</strong>：$3\texttt{s}$</p>
<p><strong>空间限制</strong>：$1\texttt{GB}$</p>

# 后记


<p>“奋战两小时，考个四五十”的表情包占领了你的朋友圈：</p>
<ul><li>“啊，感觉自己人生完全了”</li>
<li>“但愿……我真的能拿到四五十”</li>
<li>“我考完了……考完了……完了”</li>
<li>“曾经以为是开玩笑的，原来我还是<em>naïve</em>了”</li>
</ul><p>你冷笑。提前半小时交卷，你自然觉得，数据结构，满分，正常。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=341">样例数据下载</a></p>
