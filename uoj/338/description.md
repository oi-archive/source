# 题目描述


# 题目描述


<p>小Y是一个爱好旅行的OIer。一天，她来到了一个新的城市。由于不熟悉那里的交通系统，她选择了坐地铁。</p>
<p>她发现每条地铁线路可以看成平面上的一条曲线，不同线路的交点处一定会设有换乘站 <img src="//img.uoj.ac/problem/338/huancheng.webp" alt="换成站"/> 。通过调查得知，没有线路是环线，也没有线路与自身相交。任意两条不同的线路只会在若干个点上相交，没有重合的部分，且没有三线共点的情况。即，如图所示的情况都是不存在的：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/338/example.webp" alt="例子" style="width:812px;"/></p>
<p>小Y坐着地铁 $0$ 号线，路上依次经过了 $n$ 个换乘站。她记下了每个换乘站可以换乘的线路编号，发现每条线路与她所乘坐的线路最多只有 $2$ 个换乘站。现在小Y想知道，除掉她经过的换乘站以外，这个城市里最少有几个换乘站。只有你告诉她正确的答案，她才会答应下次带你去玩呢。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p><strong>请注意本题有多组输入数据。</strong></p>
<p>输入数据的第一行是一个整数 $T$，表示输入数据的组数。接下来依次给出每组数据。</p>
<p>对于每组数据，第一行是一个整数 $n$，表示小Y经过的换乘站的数目。第二行为 $n$ 个用空格隔开的整数，依次表示每个换乘站的可以换乘的线路编号。这些编号都在 $1$ ~ $n$ 之内。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>对于每组输入数据，输出一行一个整数，表示除掉这 $n$ 个换乘站之外，最少有几个换乘站。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">4
4
1 2 1 2
8
1 2 3 4 1 2 3 4
5
5 4 3 3 5
8
1 2 3 4 1 3 2 4</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">0
0
0
1</code></pre>
<h4>explanation</h4>
<p>对于样例的前两组数据，一种可能的最优答案如下图所示。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/338/338-exp.png" alt="解释" style="width:500px;"/></p>

# 限制与约定


<p>一共有 50 个测试点，每个测试点 2 分。你只有在答案完全正确时才能得到该测试点的全部分数，否则不得分。</p>
<p>对于所有测试点，以及对于样例，$1 \le T \le 100, 1 \le n \le 44$。对于每个测试点，$n$ 的范围如下表：</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$1 \le n \le$</th><th rowspan="1">测试点编号</th><th rowspan="1">$1 \le n \le$</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">2</td><td rowspan="1">26</td><td rowspan="1">32</td></tr><tr><td rowspan="1">2</td><td rowspan="1">3</td><td rowspan="1">27</td><td rowspan="1">33</td></tr><tr><td rowspan="1">3</td><td rowspan="1">4</td><td rowspan="1">28</td><td rowspan="1">33</td></tr><tr><td rowspan="1">4</td><td rowspan="1">5</td><td rowspan="1">29</td><td rowspan="1">34</td></tr><tr><td rowspan="1">5</td><td rowspan="1">6</td><td rowspan="1">30</td><td rowspan="1">34</td></tr><tr><td rowspan="1">6</td><td rowspan="1">8</td><td rowspan="1">31</td><td rowspan="1">35</td></tr><tr><td rowspan="1">7</td><td rowspan="1">9</td><td rowspan="1">32</td><td rowspan="1">35</td></tr><tr><td rowspan="1">8</td><td rowspan="1">10</td><td rowspan="1">33</td><td rowspan="1">36</td></tr><tr><td rowspan="1">9</td><td rowspan="1">11</td><td rowspan="1">34</td><td rowspan="1">36</td></tr><tr><td rowspan="1">10</td><td rowspan="1">12</td><td rowspan="1">35</td><td rowspan="1">37</td></tr><tr><td rowspan="1">11</td><td rowspan="1">13</td><td rowspan="1">36</td><td rowspan="1">37</td></tr><tr><td rowspan="1">12</td><td rowspan="1">14</td><td rowspan="1">37</td><td rowspan="1">38</td></tr><tr><td rowspan="1">13</td><td rowspan="1">15</td><td rowspan="1">38</td><td rowspan="1">38</td></tr><tr><td rowspan="1">14</td><td rowspan="1">16</td><td rowspan="1">39</td><td rowspan="1">39</td></tr><tr><td rowspan="1">15</td><td rowspan="1">17</td><td rowspan="1">40</td><td rowspan="1">39</td></tr><tr><td rowspan="1">16</td><td rowspan="1">20</td><td rowspan="1">41</td><td rowspan="1">40</td></tr><tr><td rowspan="1">17</td><td rowspan="1">22</td><td rowspan="1">42</td><td rowspan="1">40</td></tr><tr><td rowspan="1">18</td><td rowspan="1">24</td><td rowspan="1">43</td><td rowspan="1">41</td></tr><tr><td rowspan="1">19</td><td rowspan="1">26</td><td rowspan="1">44</td><td rowspan="1">41</td></tr><tr><td rowspan="1">20</td><td rowspan="1">28</td><td rowspan="1">45</td><td rowspan="1">42</td></tr><tr><td rowspan="1">21</td><td rowspan="1">30</td><td rowspan="1">46</td><td rowspan="1">42</td></tr><tr><td rowspan="1">22</td><td rowspan="1">30</td><td rowspan="1">47</td><td rowspan="1">43</td></tr><tr><td rowspan="1">23</td><td rowspan="1">31</td><td rowspan="1">48</td><td rowspan="1">43</td></tr><tr><td rowspan="1">24</td><td rowspan="1">31</td><td rowspan="1">49</td><td rowspan="1">44</td></tr><tr><td rowspan="1">25</td><td rowspan="1">32</td><td rowspan="1">50</td><td rowspan="1">44</td></tr></tbody></table><p><strong>时间限制</strong>：$7\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=338">样例数据下载</a></p>
