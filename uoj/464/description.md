# 题目描述

<p>在 DoubleDog 和SinglePig 所在的宇宙中，物理法则与我们并不相同。在年复一年的宅化过程中，SinglePig 开发出了简单的 pig 计算机，DoubleDog 通过揣摩其变化，观察出其数学模型如下：</p>
<p>这些 pig 计算机有且仅有一个长为 $ n(n\ge 3) $ 的布尔数组 $ a $ （下标从 $ 0 $ 开始），操作者可以为计算机写一个程序，程序即为一个固定长度的操作序列，每个操作形如：从 $ a $ 中选择三个不同的位置 $ i,j,k $ ，对他们执行一个门操作 $ g $ ，其中 $ g $ 是一个输入三个布尔值且输出三个布尔值的一一映射（即对于不同的两组输入， $ g $ 产生不同的两组输出）。</p>
<p>DoubleDog 也想使用 pig 计算机来进行加法运算，但是苦于没有 SinglePig 们提供的程序，于是只好拜托你。如果我们视数组 $ a $ 的前 $ l $ 位为一个二进制数的话，其数值为 $ \sum_{i = 0}^{l - 1} a_i 2^i $  。现在 DoubleDog 想实现一个程序，完成对数组 $ a $ 的前 $ l $ 
位所表示的二进制数进行模 $ 2^l $ 的意义下加一个常数 $ c $ 的操作。你需要对 DoubleDog 提供的常数 $ c $ 设计出一个 pig 计算机上的程序。</p>
<p>根据测试点的不同，数组 $ a $ 的后 $ n-l $ 位中的初值和输出值为不同类型的值。对于每个测试点，你都需要提供一个给定格式的长度不超过 $ m $ 的程序。有数个测试数据作为输入，如果你的程序能通过该测试点下的所有测试数据，则你通过此测试点。</p>

# 输入格式


<p>第一行包括一个正整数，表示子任务编号。</p>
<p>第二行包括三个正整数 $ n, m, l ​$，表示数组的长度，你的输出的最多行数和数字的长度。</p>
<p>接下来一行一个长度为 $ l $ 的 01 字符串，<strong>从低到高</strong>表示 $ c $ 的每一位。</p>

# 输出格式


<p>输出第一行包含一个数 $ L ​$，表示你的程序的行数，你必须保证 $ L \le m ​$ 。</p>
<p>接下来共输出 $ L $ 行，每行四个整数，前三个为操作位 $ i,j,k $，你必须保证 $ i, j, k $ 互不相同。第四个整数由一个长度 $ 24 ​$ 的 01 串表示，每三位表示真值表中一个输入的对应输出。</p>
<p>给定一个输入三个布尔值 $ a, b, c ​$ 且输出三个布尔值 $ x, y, z ​$ 的门 <code>gate</code>，我们可以通过以下函数得到该门所对应的输出：</p>
<pre><code class="sh_cpp">void gate(bool a, bool b, bool c, bool &amp;x, bool &amp;y, bool &amp;z);
string gate_str(){
    string res = &#34;&#34;;
    for (int w = 0; w &lt; 8; ++w) {
        bool a = (w &amp; 4) &gt; 0;
        bool b = (w &amp; 2) &gt; 0;
        bool c = (w &amp; 1) &gt; 0;
        bool x, y, z;
        gate(a, b, c, x, y, z);
        res += char(x) + &#39;0&#39;;
        res += char(y) + &#39;0&#39;;
        res += char(z) + &#39;0&#39;;
    }
    return res;
}</code></pre>

# 样例一


<h4>input</h4>
<pre><code>0
10 50000 1
1</code></pre>
<h4>output</h4>
<pre><code>1
0 1 2 100101110111000001010011</code></pre>
<h4>explanation</h4>
<p>对于任意的 $ a $，该程序都会将 $ a_0 $ 取反 (0 变 1, 1 变 0)。</p>

# 限制与约定


<p>对于 $ 100\% ​$ 的数据，$ l = 100, c &lt; 2^l ​$ 。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>$n=$</th><th>$m=$</th><th>输入后$n-l$位</th><th>输出后$n-l$位</th><th>约定</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$300$</td><td>$50000$</td><td>为$0$</td><td>不限</td><td></td><td>$13$</td></tr><tr><td>$2$</td><td>$200$</td><td>$20000$</td><td>为$0$</td><td>不限</td><td></td><td>$8$</td></tr><tr><td>$3$</td><td>$300$</td><td>$50000$</td><td>为$0$</td><td>为$0$</td><td></td><td>$20$</td></tr><tr><td>$4$</td><td>$200$</td><td>$20000$</td><td>为$0$</td><td>为$0$</td><td>$c=1$</td><td>$17$</td></tr><tr><td>$5$</td><td>$200$</td><td>$20000$</td><td>未知</td><td>与输入相同</td><td>$c=1$</td><td>$13$</td></tr><tr><td>$6$</td><td>$101$</td><td>$20000$</td><td>为$0$</td><td>为$0$</td><td></td><td>$19$</td></tr><tr><td>$7$</td><td>$101$</td><td>$20000$</td><td>未知</td><td>与输入相同</td><td></td><td>$10$</td></tr></tbody></table></div>



<p>在下发文件中我们下发了模拟器的源代码。</p>
<p>模拟器从 <code>in.txt</code> 中读入一个数 $ n $ 和一个长度为 $ n $ 的数组 $ a $ 表示输入，从 <code>out.txt</code> 中读入你的程序，向 <code>ans.txt</code> 输出最终的 $ a $ 数组。</p>
<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=464">样例数据及模拟器下载</a></p>
