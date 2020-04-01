
# Description

<div class="content"><div>一个简单的网络系统可以被描述成一棵无根树。每个节点为一个服务器。连接服务器与服务器的数据 线则看做一</div>
<div>条树边。两个服务器进行数据交互时，数据会经过连接这两个服务器的路径上的所有服务 器（包括这两个服务器</div>
<div>自身）。每个数据交互请求都有一个非负的重要度，越重要的请求显然需要得 到越高的优先处理权。此外，如果</div>
<div>在某一个时刻存在一条非常重要（可以看作重要度无穷大）、且数 据量巨大的交互请求，则所有被该交互经过的</div>
<div>服务器都会优先处理这条交互并阻塞，从而导致其他通 过这些服务器的交互出现延迟。现在，你作为一个网络系</div>
<div>统的管理员，要监控整个系统的运行状态。 系统的运行也很简单，在每一个时刻，只有可能出现下列二种事件中</div>
<div>的一种：</div>
<div>1、在某两个服务器之间出现一条新的数据交互请求；</div>
<div>2、某个数据交互请求结束；</div>
<div>我们假设这些事件中的交互请求的数据量都足够小。你的任务是在每一个时刻的事件结束后，求出：</div>
<div>如果突然出现一条非常重要、且数据量巨大的交互请求</div>
<div>那么因其造成延迟的数据交互请求的重要度之和最大可能是多少？</div>
<div></div></div>

# Input

<div class="content"><div>输入的第一行包含二个正整数N,M，分别表示服务器的个数、事件（时刻）的个数。</div>
<div>接下来N?1行，每行两个整数u,v，描述一条树边。u和v是服务器的编号，服务器编号1…n。</div>
<div>接下来M行，按发生时刻依次描述每一个事件；即第i行（i=1,2,3,…,m）描述时刻i发生的事件。</div>
<div>事件的描述有两种：</div>
<div>+ u v w 服务器u和v之间出现了一条重要度为w的数据交互请求</div>
<div>? t 时刻tt出现的数据交互请求结束</div>
<div>1≤N,M≤10^5，所有的输入数据均为 int 范围内的非负整数。保证输入合法。</div>
<div></div></div>

# Output

<div class="content"><div>输出M行，每行一个整数，依次描述在每个事件后，如果突然出现一条非常重要、且数据量巨大的交互请求</div>
<div>那么因其造成延迟的数据交互请求的重要度之和的最大值。如果此时没有任何数据交互请求，输出 0。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
1 2<br/>
2 4<br/>
4 3<br/>
2 5<br/>
+ 1 4 7<br/>
+ 5 5 4<br/>
- 1<br/>
+ 3 4 3<br/>
+ 1 1 6<br/>
- 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
11<br/>
4<br/>
7<br/>
10<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

