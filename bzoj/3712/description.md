
# Description

<div class="content"><p>化学家吉丽想要配置一种神奇的药水来拯救世界。<br/>
吉丽有n种不同的液体物质，和n个药瓶（均从1到n编号）。初始时，第i个瓶内装着g[i]克的第i种物质。吉丽需要执行一定的步骤来配置药水，第i个步骤是将第a[i]个瓶子内的所有液体倒入第b[i]个瓶子，此后第a[i]个瓶子不会再被用到。瓶子的容量可以视作是无限的。<br/>
吉丽知道某几对液体物质在一起时会发生反应产生沉淀，具体反应是1克c[i]物质和1克d[i]物质生成2克沉淀，一直进行直到某一反应物耗尽。生成的沉淀不会和任何物质反应。当有多于一对可以发生反应的物质在一起时，吉丽知道它们的反应顺序。每次倾倒完后，吉丽会等到反应结束后再执行下一步骤。<br/>
吉丽想知道配置过程中总共产生多少沉淀。</p></div>

# Input

<div class="content"><p>第一行三个整数n,m,k(0&lt;=m&lt;n&lt;=200000,0&lt;=k&lt;=500000)，分别表示药瓶的个数（即物质的种数），操作步数，可以发生的反应数量。<br/>
第二行有n个整数g[1],g[2],…,g[n]（1&lt;=g[i]&lt;=10^9)，表示初始时每个瓶内物质的质量。<br/>
接下来m行，每行两个整数a[i],b[i](1&lt;=a[i],b[i]&lt;=n,a[i]≠b[i])，表示第i个步骤。保证a[i]在以后的步骤中不再出现。<br/>
接下来k行，每行是一对可以发生反应的物质c[i],d[i](1&lt;=c[i],d[i]&lt;=n,c[i]≠d[i])，按照反应的优先顺序给出。同一个反应不会重复出现。</p></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 1<br/>
2 3 4<br/>
1 2<br/>
3 2<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

