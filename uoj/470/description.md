# 题目描述

<p>九条可怜是一个喜欢规律的女孩子。按照规律，第二题应该是一道和数据结构有关的题。</p>
<p>在一个遥远的国度，有 $n$ 个城市。城市之间有 $n-1$ 条双向道路，这些道路保证了任何两个城市之间都能直接或者间接地到达。</p>
<p>在上古时代，这 $n$ 个城市之间处于战争状态。在高度闭塞的环境中，每个城市都发展出了自己的语言。而在王国统一之后，语言不通给王国的发展带来了极大的阻碍。为了改善这种情况，国王下令设计了 $m$ 种通用语，并进行了 $m$ 次语言统一工作。在第 $i$ 次统一工作中，一名大臣从城市 $s_i$ 出发，沿着最短的路径走到了 $t_i$，教会了沿途所有城市（包括 $s_i,t_i$） 使用第 $i$ 个通用语。</p>
<p>一旦有了共通的语言，那么城市之间就可以开展贸易活动了。两个城市 $u_i,v_i$ 之间可以开展贸易活动当且仅当存在一种通用语 $L$满足 $u_i$ 到 $v_i$ 最短路上的所有城市（包括 $u_i,v_i$），都会使用 $L$。</p>
<p>为了衡量语言统一工作的效果，国王想让你计算有多少对城市$ (u,v)(u &lt; v)$，他们之间可以开展贸易活动。</p>

# 输入格式


<p>第一行输入两个正整数 $n,m$，表示城市数和通用语的数量。</p>
<p>接下来 $n-1$ 行，每行两个整数 $x_i,y_i(1 \leq x_i,y_i \leq n)$，表示了一条连接城市 $x_i,y_i$ 的道路。</p>
<p>接下来 $m$ 行，每行两个整数 $s_i,t_i(1 \leq s_i,t_i \leq n,s_i \neq t_i)$，表示一次语言普及工作。</p>

# 输出格式


<p>输出一行一个整数，表示可以开展贸易活动的城市对数量。</p>

# 样例一


<h4>input</h4>
<pre><code>5 3
1 2
1 3
3 4
3 5
3 4
1 4
2 5</code></pre>
<h4>output</h4>
<pre><code>8</code></pre>
<h4>explanation</h4>
<p>可以开展贸易活动的城市对为 $(1,2),(1,3),(1,4),(1,5),(2,3),(2,5),(3,4),(3,5)$。</p>

# 样例二


<p>见样例数据下载</p>

# 限制与约定


<p>对于 $100\%$ 的数据，有 $1 \leq s_i,y_i,s_i,t_i \leq n, m \geq 1, s_i \neq t_i, x_i \neq y_i$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点</th>
    <th>$n$</th>
    <th>$m$</th>
    <th>其他限制</th>
  </tr></thead><tbody><tr><td>1</td>
    <td rowspan="2">$\leq 300$</td>
    <td rowspan="2">$\leq 300$</td>
    <td rowspan="4">无</td>
  </tr><tr><td>2</td>
  </tr><tr><td>3</td>
    <td rowspan="2">$\leq 5000$</td>
    <td rowspan="2">$\leq 5000$</td>
  </tr><tr><td>4</td>
  </tr><tr><td>5</td>
    <td rowspan="6">$\leq 10^5$</td>
    <td rowspan="6">$\leq 10^5$</td>
    <td rowspan="2">$y_i=x_i+1$</td>
  </tr><tr><td>6</td>
  </tr><tr><td>7</td>
    <td rowspan="4">无</td>
  </tr><tr><td>8</td>
  </tr><tr><td>9</td>
  </tr><tr><td>10</td>
  </tr></tbody></table></div>

<p><strong>时间限制</strong>：$3\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=470">样例数据下载</a></p>
