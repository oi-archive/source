# 题目描述

<pre><code>“悲伤的事和艰辛的事，我不认为它们徒劳无益。  
如果那就是命运的话，就必然有其意义。  
我会全部接受它们并变得坚强。  
所以——请为我驻足。”  
                           ——《回转企鹅罐》</code></pre>
<p>如果命运从一开始就被写好了，那么生存的意义是什么呢？  </p>
<p>我想为了你活下去，我想你为了我活下去。  </p>
<p>只要有一个人需要，那么活着就是有意义的。  </p>
<p>lihua与Rosemary一起分享了命运的果实，一起分担了爱与惩罚。  </p>
<p>命运是一个既定的 $p×s$ 的$01$矩阵 $C$，它是确定的。 </p>
<p>爱是一个$p×q$的$01$矩阵$A$，而惩罚是一个$q×s$的$01$矩阵$B$。</p>
<p>命运的果实由爱与惩罚组成，即满足 $C[i][j]=(\sum\limits_{k=1}^qA[i][k]×B[k][j]) \pmod 2$。</p>
<p>命运即使已经既定，但是爱与惩罚的可能性很多，lihua与Rosemary不禁想要计算。</p>
<p>而他们也不会顺从着搭上命运的列车，到达命运所至之地，他们也会换乘自己的命运。</p>
<p>因此存在$m$次命运换乘，lihua与Rosemary在命运换乘点以爱之名念出了咒语，换乘了命运。</p>
<p>命运换乘会将矩阵$C$的某一行进行修改，每次修改后lihua与Rosemary希望重新计算爱与惩罚的可能性。</p>
<p>由于可能性可能十分多样，他们只希望了解模$1000000007$后的答案。</p>

# 输入格式


<p>第一行五个整数，分别表示$p,q,s,m,k$。</p>
<p>接下来读入矩阵$C$，共$p$行每行$s$个数。</p>
<p>再接下来$m$行表示修改，每一行一开始一个数 $j$表示修改的是矩阵第$j\;xor\;(k∗ans)$行，其中$ans$表示修改前的答案。然后接下来$s$个数表示将这行修改成什么。</p>

# 输出格式


<p>在所有修改前及每次修改后输出一行一个整数表示答案。</p>

# 样例一


<h4>input</h4>
<pre><code>2 2 2 1 0
0 1
1 0
1 1 0</code></pre>
<h4>output</h4>
<pre><code>6
18</code></pre>

# 限制与约定


<p>对于全部数据，都有$1\le p,q,s,m\le 1000$，$k\in\{0,1\}$   。</p>
<p>设$n$表示$p,q,s$的最大值。</p>
<p>特性$A$表示数据随机，初始矩阵、每次修改哪一行以及修改成什么样都是随机生成。如果没有多余限制，则$p,q,s$均在$(n−5,n]$中随机生成（如subtask $10$   ）。若限制$p=q=s=o$，那么$o$在 $(n−100,n]$中随机生成（如subtask $6$）。</p>
<p>特性$B$表示$p=q=s$。</p>
<p>特性$C$表示初始读入的矩阵$C$是单位矩阵。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>数据范围</th><th>数据特性</th><th>该任务分值</th></tr></thead><tbody><tr><td>1</td><td>$n\le 3,m=0$</td><td> </td><td>4</td></tr><tr><td>2</td><td>$n\le 4,m=0$</td><td> </td><td>6</td></tr><tr><td>3</td><td>$n\le 5,m=0$</td><td> </td><td>5</td></tr><tr><td>4</td><td>$n\le 300,m=0$</td><td> </td><td>15</td></tr><tr><td>5</td><td>$n\le 300,m\le 1000$</td><td> </td><td>11</td></tr><tr><td>6</td><td>$n\le 700,m=0$</td><td>AB</td><td>7</td></tr><tr><td>7</td><td>$n\le 1000,m=0,p=s$</td><td>C</td><td>6</td></tr><tr><td>8</td><td>$n\le 1000,m=0$</td><td> </td><td>16</td></tr><tr><td>9</td><td>$p,q,m\le 1000,s\le 100,k=0$</td><td> </td><td>12</td></tr><tr><td>10</td><td>$n,m\le 1000$</td><td>A</td><td>10</td></tr><tr><td>11</td><td>$n,m\le 1000$</td><td> </td><td>8</td></tr></tbody></table></div>


<p><strong>时间限制：$\texttt{1s}$</strong></p>
<p><strong>空间限制：$\texttt{512MB}$</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=453">样例数据下载</a></p>
