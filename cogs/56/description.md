# 题目描述


<b><span style="font-size:large;">题目描述</span></b> 
<div>
DD 和<span> MM 正在玩取石子游戏。他们的游戏规则是这样的：桌上有若干石子，DD 先取，轮流取，每次必须取质数个。如果某一时刻某一方无法从桌上的石子中取质数个，比如说剩下 0 个或 1 个石子，那么他/她就输了。</span> 
</div>
<div>
DD 和<span> MM 都很聪明，不管哪方存在一个可以必胜的最优策略，他/她都会按照最优策略保证胜利。于是，DD 想知道，对于给定的桌面上的石子数，他究竟能不能取得胜利呢？</span> 
</div>
<p>
当<span> DD 确定会取得胜利时，他会说：“不管 MM 选择怎样的取石子策略，我都能保证至多 X 步以后就能取得胜利。”那么，最小的满足要求的 X 是多少呢？注意，不管是<span> DD </span>取一次石子还是 MM 取一次石子都应该被计算为“一步”。</span> 
</p>
<div>
<b><span style="font-size:large;">输入格式</span></b> 
</div>
<div>
第一行有一个整数<span> N，表示这个输入文件中包含 N 个测试数据。</span> 
</div>
<div>
第二行开始，每行有一个测试数据，其中仅包含一个整数，表示桌面上的石子数。
</div>
<div>
<b><span style="font-size:large;">输出格式</span></b> 
</div>
<div>
你需要对于每个输入文件中的<span> N 个测试数据输出相应的 N 行。</span> 
</div>
<div>
如果对于该种情形是<span> DD 一定取得胜利，那么输出最小的 X。否则该行输出 -1。</span> 
</div>
<div>
<b><span style="font-size:large;">样例输入</span></b> 
</div>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">3</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">8</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">9</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">16</pre>
<div>
<b><span style="font-size:large;">样例输出</span></b> 
</div>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">1</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">-1</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">3</pre>
<div>
<b><span style="font-size:large;">样例说明</span></b> 
</div>
<div>
当桌上有<span> 8 个石子时，先取的 DD 只需要取走 7 个石子剩下 1 个就可以在一步之后保证胜利，输出 1。</span> 
</div>
<div>
当桌上有<span> 9 个石子时。若 DD 取走 2 个，MM 会取走 7 个，剩下 0 个，DD 输。若 DD 取走 3 个，MM 会取走 5 个，剩下 1 个，DD 输。DD 取走 5 个或者 7 个的情况同理可知。所以当桌上有 9 个石子时，不管 DD 怎么取，MM 都可以让 DD 输，输出 -1。</span> 
</div>
<p>
当桌上有<span> 16 个石子时，DD 可以保证在 3 步以内取得胜利。可以证明，为了在<span> 3 </span>步内取得胜利，DD 第一步必须取 7 个石子。剩下 9 个石子之后，不管第二步 MM 怎么取，DD 取了第三步以后可以保证胜利，所以输出 3。</span> 
</p>
<div>
<b><span style="font-size:large;">数据范围</span></b> 
</div>
<div>
输入文件中的数据数<span> N&lt;=10。</span> 
</div>
<div>
每次桌上初始的石子数都不超过<span> 20000。</span> 
</div>
<p>
 
</p>
