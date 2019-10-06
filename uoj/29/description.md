# 题目描述

<p>健佳正在制定下个假期去台湾的游玩计划。在这个假期，健佳将会在城市之间奔波，并且参观这些城市的景点。</p>
<p>在台湾共有 $n$ 个城市，它们全部位于一条高速公路上。这些城市连续地编号为 $0$ 到 $n - 1$。对于城市 $i$ ($0 &lt; i &lt; n - 1$) 而言，与其相邻的城市是 $i - 1$ 和 $i + 1$。但是对于城市 $0$，唯一与其相邻的是城市 $1$。而对于城市 $n - 1$，唯一与其相邻的是城市 $n - 2$。</p>
<p>每个城市都有若干景点。健佳有 $d$ 天假期并且打算要参观尽量多的景点。健佳已经选择了假期开始要到访的第一个城市。在假期的每一天，健佳可以选择去一个相邻的城市，或者参观所在城市的所有景点，但是不能同时进行。即使健佳在同一个城市停留多次，他也不会去重复参观该城市的景点。请帮助健佳策划这个假期，以便能让他参观尽可能多的景点。</p>

# 任务


<p>请实现函数 findMaxAttraction，以计算健佳最多可以参观多少个景点。</p>
<ul><li>findMaxAttraction(n, start, d, attraction)<ul><li>$n$: 城市数。</li>
<li>start: 起点城市的编号。</li>
<li>$d$: 假期的天数。</li>
<li>attraction: 长度为 $n$ 的数组；attraction[i] 表示城市 $i$ 的景点数目，其中 $0 \leq i \leq n - 1$。</li>
<li>该函数应返回健佳最多可以参观的景点数。</li>
</ul></li>
</ul>
# 子任务


<p>在所有的子任务中，有 $0 \leq d \leq 2n + \lfloor n / 2 \rfloor$。而且，每个城市中的景点数都是非负整数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>$n$</th><th>各城市景点数的最大值</th><th>起点城市</th></tr></thead><tbody><tr><td>1</td><td>7</td><td>$2 \leq n \leq 20$</td><td>$10^9$</td><td>无限制</td></tr><tr><td>2</td><td>23</td><td>$2 \leq n \leq 100000$</td><td>$100$</td><td>城市 $0$</td></tr><tr><td>3</td><td>17</td><td>$2 \leq n \leq 3000$</td><td>$10^9$</td><td>无限制</td></tr><tr><td>4</td><td>53</td><td>$2 \leq n \leq 100000$</td><td>$10^9$</td><td>无限制</td></tr></tbody></table></div>


# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现上述的函数，其命名与接口需遵循下面的要求。你还要在该文件中包含头文件holiday.h。</p>
<p>注意，计算的结果可能会很大，所以函数 findMaxAttraction 的返回值类型是一个64位整数。</p>
<pre><code class="sh_cpp">long long int findMaxAttraction(int n, int start, int d, int attraction[]);</code></pre>

# 评测方式


<p>评测系统需要读入如下格式的输入数据:</p>
<ul><li>第 $1$ 行: $n$, start, $d$。</li>
<li>第 $2$ 行: $\text{attraction[0]}, \dots, \text{attraction[n-1]}$。</li>
</ul><p>评测系统将会输出 findMaxAttraction 的返回值。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$5\texttt{s}$</p>
<p><strong>空间限制：</strong>$64\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=29">样例及测评库下载</a></p>
