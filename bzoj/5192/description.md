
# Description

<div class="content"><div>FarmerJohn注意到他的奶牛们如果被关得太紧就容易吵架，所以他想开放一些新的牛棚来分散她们。每当FJ建造一</div>
<div>个新牛棚的时候，他会将这个牛棚用至多一条双向道路与一个现有的牛棚连接起来。为了确保他的奶牛们足够分散</div>
<div>，他有时想要确定从某个特定的牛棚出发，到它能够到达的最远的牛棚的距离（两个牛棚之间的距离等于从一个牛</div>
<div>棚出发到另一个之间必须经过的道路条数）。FJ总共会给出Q（1≤Q≤10^5）次请求，每个请求都是“建造”和“</div>
<div>距离”之一。对于一个建造请求，FJ建造一个牛棚，并将其与至多一个现有的牛棚连接起来。对于一个距离请求，</div>
<div>FJ向你询问从某个特定的牛棚通过一些道路到离它最远的牛棚的距离。保证询问的牛棚已经被建造。请帮助FJ响应</div>
<div>所有的请求。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个整数Q</div>
<div>以下Q行，每行包含一个请求。每个请求的格式都是“B p”或是“Q k”</div>
<div>分别告诉你建造一个牛棚并与牛棚p连接，或是根据定义求从牛棚k出发最远的距离。</div>
<div>如果p=-1，则新的牛棚不会与其他牛棚连接。</div>
<div>否则，p是一个已经建造的牛棚的编号。</div>
<div>牛棚编号从1开始，所以第一个被建造的谷仓是1号谷仓，第二个是2号谷仓，以此类推。</div>
<div></div></div>

# Output

<div class="content"><p>对于每个距离请求输出一行。注意一个没有连接到其他牛棚的牛棚的最远距离为0</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
B -1<br/>
Q 1<br/>
B 1<br/>
B 2<br/>
Q 3<br/>
B 2<br/>
Q 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
2<br/>
1<br/>
输入样例对应下面的牛棚网：<br/>
  (1) <br/>
    \   <br/>
     (2)---(4)<br/>
    /<br/>
  (3)<br/>
对于请求1，我们建造牛棚1。对于请求2，我们询问从1出发到最远连接的牛棚的距离。由于牛棚1没有与其他牛棚<br/>
连接，所以回答是0。对于请求3，我们建造牛棚2并将其与牛棚1连接。对于请求4，我们建造牛棚3并将其与牛棚2<br/>
连接。对于请求5，我们询问从3出发到最远连接的牛棚的距离。在这时，最远的是牛棚1，距离为2单位。对于请求<br/>
6，我们建造牛棚4并将其与牛棚2连接。对于请求7，我们询问从2出发到最远连接的牛棚的距离。所有其他三个牛<br/>
棚1，3，4都与2相距相同的距离1，所以这就是我们的回答。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

