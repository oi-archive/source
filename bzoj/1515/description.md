
# Description

<div class="content"><div>每天早上邮递员都要走过每条街道来递送邮件. 所有的道路都是单向的. 两个岔路口间最多有两条边并且方向不同. 岔路口从1 到 编号. 邮递员从Byteotian邮政总部出发并且最终回到总部, 他可以自由选择自己喜欢的线路.最近他的上司给了他新的任务. 他被分派了一些路径的片段- 即一些需要依次经过的岔路口序列. 邮递员要选择一条路径使得: </div>
<div>·<span class="Apple-tab-span" style="white-space:pre">	</span>经过每条街道一次, </div>
<div>·<span class="Apple-tab-span" style="white-space:pre">	</span>包含所有给定的路径片段, </div>
<div>·<span class="Apple-tab-span" style="white-space:pre">	</span>从第一个路口出发并回到第一个路口. </div>
<div>很不幸,很可能这样的路径不一定存在. 请你帮邮递员找出一条可行的路径.</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个整数N和M,2&lt;=N&lt;=50000,1&lt;=M&lt;=200000 表示岔路口数目以及街道的数目. 接下来M行每行两个数字a, b,</div>
<div>1&lt;=a,b&lt;=N,a&lt;&gt;b,, 表示一条单向道路. 每一队 a,b在数据中最多出现一次. 接下来一行一个整数t,0&lt;=t&lt;=10000 </div>
<div>表示给定的路径片段数目. 接下来t行用来描述这些路径片段. 每行开始一个整数 k,2&lt;=K&lt;=200000, 并且一个序列</div>
<div> v1,v2…vk表示需要经过的路口总数以及这些路口的编号. 所有路径片段的总长不超过1000000.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行输出: </div>
<div>·<span class="Apple-tab-span" style="white-space: pre;">	</span>TAK - 如果存在一条满足条件的路径, </div>
<div>·<span class="Apple-tab-span" style="white-space: pre;">	</span>NIE – 如果路径不存在.</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 10<br/>
1 5<br/>
1 3<br/>
4 1<br/>
6 4<br/>
3 6<br/>
3 4<br/>
4 3<br/>
5 6<br/>
6 2<br/>
2 1<br/>
4<br/>
3 1 5 6<br/>
3 3 4 3<br/>
4 4 3 6 4<br/>
3 5 6 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img border="0" src="/source/bzoj/1515/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE1MTUuanBn.jpg" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

