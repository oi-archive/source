
# Description

<div class="content"><div>农夫约翰创立了一家为客户提供云端计算服务的公司，但是他还没开始购买计算机。于是他去了电脑商店，看了商</div>
<div>店里所有的n台电脑的配置属性列表。每台电脑的属性有 CPU核心数量 ci，工作频率fi,价格vi，即这台电脑有ci</div>
<div>个可以独立工作，不会互相干扰的CPU核心，可以同时给每个CPU核心分配不同的任务。当一个客户在约翰的公司里</div>
<div>下订单的时候，订单里会指定特定的CPU核心数量Cj，最低工作频率Fj，并且会给出这个客户所能接受的定价Vj。</div>
<div>如果约翰接受了一个客户的订单，那就需要选出Cj个CPU核心专门为这个客户工作（这些CPU核心可能来自于不同的</div>
<div>计算机），而且这Cj个CPU核心的工作频率至少为Fj。这些CPU核心一旦被选定为这个订单工作，就无法被分配给其</div>
<div>他任何订单。约翰需要你告诉他：应该接受哪些订单同时买下哪些电脑来最大化他的利润。(利润=接受的所有订单</div>
<div>的定价之和-购买的计算机的价格之和)</div>
<div>原题面:www.lydsy.com/JudgeOnline/upload/5441.pdf</div>
<div></div></div>

# Input

<div class="content"><div>第一行输入包含一个整数n(1&lt;=n&lt;=2000)，表示商店里计算机的数量。</div>
<div>接下来的n行，每行包含3个用空格隔开的整数，ci,fi,vi(1&lt;=ci&lt;=50,1&lt;=fi&lt;=10^9,1&lt;=vi&lt;=10^9),</div>
<div>分别表示商店里第i台计算机的CPU核心数量，工作频率和价格</div>
<div>之后的一行包括一个整数m，(1&lt;=m&lt;=2000)，表示订单的数量。</div>
<div>接下来的m行，每行包括3个用空格隔开的整数Cj,Fj,Vj(1&lt;=Cj&lt;=50,1&lt;=Fj&lt;=10^9,1&lt;=Vj&lt;=10^9)，</div>
<div>表示这个订单所需的CPU核心数量，CPU核心的最低工作频率，以及这个顾客愿意给出的定价。</div>
<div>分组数据范围:</div>
<div>对于18%的数据点,n&lt;=15</div>
<div>对于另外18%的数据点,m&lt;=15</div>
<div>对于另外18%的数据点,n,m&lt;=250,ci=Cj=1</div>
<div>对于另外18%的数据点,fi=Fj=1</div>
<div>对于另外18%的数据点,vi=Vj=1</div>
<div>对于另外10%的数据点,没有任何限制</div>
<div></div></div>

# Output

<div class="content"><p> 输出只有一行，包含一个整数，表示能达到的最大利润</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4 2200 700<br/>
2 1800 10<br/>
20 2550 9999<br/>
4 2000 750<br/>
3<br/>
1 1500 300<br/>
6 1900 1500<br/>
3 2400 4550</span></div>

# Sample Output

<div class="content"><span class="sampledata">350<br/>
<br/>
样例解释<br/>
商店里有4台计算机和3份可以接受的订单。<br/>
用700和750的代价买两个有4个CPU核心的计算机，（即输入中的第1台和第4台计算机）<br/>
然后接受前2个订单获得300+1500=1800的总定价，<br/>
于是，约翰就有了4个工作频率为2200的CPU核心和4个工作频率为2000的CPU核心，<br/>
他只需要把这8个CPU核心中的任意1个分配给第一个订单，接着把剩余7个CPU核心中的任意6个分配给第二个订单，<br/>
就满足了这2个订单的要求。最后他获得利润就是1800-（700+750）=350</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

