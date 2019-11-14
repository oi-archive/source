
# Description

<div class="content"><div>小强要在N个孤立的星球上建立起一套通信系统。这套通信系统就是连接N个点的一个树。</div>
<div>这个树的边是一条一条添加上去的。在某个时刻，一条边的负载就是它所在的当前能够</div>
<div>联通的树上路过它的简单路径的数量。</div>
<div><img src="/source/bzoj/4530/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9mZi5wbmc=.png" width="352" height="277" alt=""/></div>
<div>例如，在上图中，现在一共有了5条边。其中，(3,8)这条边的负载是6，因</div>
<div>为有六条简单路径2-3-8,2-3-8-7,3-8,3-8-7,4-3-8,4-3-8-7路过了(3,8)。</div>
<div>现在，你的任务就是随着边的添加，动态的回答小强对于某些边的负载的</div>
<div>询问。</div></div>

# Input

<div class="content"><div>第一行包含两个整数N,Q，表示星球的数量和操作的数量。星球从1开始编号。</div>
<div>接下来的Q行，每行是如下两种格式之一：</div>
<div>A x y 表示在x和y之间连一条边。保证之前x和y是不联通的。</div>
<div>Q x y 表示询问(x,y)这条边上的负载。保证x和y之间有一条边。</div>
<div>1≤N,Q≤100000</div></div>

# Output

<div class="content"><div>对每个查询操作，输出被查询的边的负载。</div></div>

# Sample Input

<div class="content"><span class="sampledata">8 6<br/>
A 2 3<br/>
A 3 4<br/>
A 3 8<br/>
A 8 7<br/>
A 6 5<br/>
Q 3 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

