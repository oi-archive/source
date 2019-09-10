# 题目描述


<p>
	<br/>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">树型网络是最节省材料的网络。所谓树型网络，是指一个无环的连通网络，网络中任意两个结点间有且仅有一条通信道路。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">网络中有一个结点是服务器，负责将信号直接或间接地发送到各终端机。如图<span>6</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4<span>，</span><span>server</span><span>结点发出一个信号给结点</span><span>a</span><span>和</span><span>c</span><span>，</span><span>a</span><span>再转发给</span><span>b</span><span>。如此，整个网络都收到这个信号了。</span></span> 
</p>
<pre>server            a          b
   ●-------------○----------○
   │
   │
   ○
</pre>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">但是，实际操作中，信号从一个结点发到另一个结点，会出现信号强度的衰减。衰减量一般由线路长度决定。</span> 
</p>
<pre>server       3    a    2     b
   ●-------------○----------○
   │
   │1
   ○
</pre>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如上图，边上所标的数字为边的衰减量。假设从<span>server</span><span>出发一个强度为</span><span>4</span><span>个单位的信号，发到结点</span><span>a</span><span>后强度衰减为</span><span>4</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3=1<span>个单位。结点</span><span>a</span><span>再将其转发给结点</span><span>b</span><span>。由于信号强度为</span><span>1</span><span>，衰减量为</span><span>2</span><span>，因此信号无法发送到</span><span>b</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个解决这一问题的方法是，安装信号放大器。信号放大器的作用是将强度大于零的信号还原成初始强度（从服务器出发时的强度）。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">上图中，若在结点<span>a</span><span>处安装一个信号放大器，则强度为</span><span>4</span><span>的信号发到</span><span>a</span><span>处，即被放大至</span><span>4</span><span>。这样，信号就可以被发送的网络中的任意一个节点了。为了简化问题，我们假定每个结点只处理一次信号，当它第二次收到某个信号时，就忽略此信号。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">你的任务是根据给出的树型网络，计算出最少需要安装的信号放大器数量。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行一个整数<span>n</span><span>，表示网络中结点的数量。（</span><span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">=100000<span>）</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第<span>2~n+1</span><span>行，每行描述一个节点的连接关系。其中第</span><span>i+1</span><span>行，描述的是结点</span><span>i</span><span>的连接关系：首先一个整数</span><span>k</span><span>，表示与结点</span><span>i</span><span>相连的结点的数量。此后</span><span>2k</span><span>个数，每两个描述一个与结点</span><span>i</span><span>相连的结点，分别表示结点的编号（编号在</span><span>1~n</span><span>之间）和该结点与结点</span><span>i</span><span>之间的边的信号衰减量。结点</span><span>1</span><span>表示服务器。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">最后一行，一个整数，表示从服务器上出发信号的强度。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个整数，表示要使信号能够传遍整个网络，需要安装的最少的信号放大器数量。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如果不论如何安装信号放大器，都无法使信号传遍整个网络，则输出“<span>No solution.</span><span>”</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">booster.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">              </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">booster.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                       </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 2 3 3 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 1 3 4 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 1 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 2 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<br/>
</p>
<p>
	<br/>
</p>
