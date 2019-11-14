
# Description

<div class="content"><div>奶牛们最近的旅游计划，是到苏必利尔湖畔，享受那里的湖光山色，以及明媚的阳光。作为整个旅游的策划者和负</div>
<div>责人，贝茜选择在湖边的一家著名的旅馆住宿。这个巨大的旅馆一共有N (1 &lt;= N &lt;= 50,000)间客房，它们在同一</div>
<div>层楼中顺次一字排开，在任何一个房间里，只需要拉开窗帘，就能见到波光粼粼的湖面。 贝茜一行，以及其他慕</div>
<div>名而来的旅游者，都是一批批地来到旅馆的服务台，希望能订到D_i (1 &lt;= D_i &lt;= N)间连续的房间。服务台的接</div>
<div>待工作也很简单：如果存在r满足编号为r..r+D_i-1的房间均空着，他就将这一批顾客安排到这些房间入住；如果</div>
<div>没有满足条件的r，他会道歉说没有足够的空房间，请顾客们另找一家宾馆。如果有多个满足条件的r，服务员会选</div>
<div>择其中最小的一个。 旅馆中的退房服务也是批量进行的。每一个退房请求由2个数字X_i、D_i 描述，表示编号为X</div>
<div>_i..X_i+D_i-1 (1 &lt;= X_i &lt;= N-D_i+1)房间中的客人全部离开。退房前，请求退掉的房间中的一些，甚至是所有</div>
<div>，可能本来就无人入住。 而你的工作，就是写一个程序，帮服务员为旅客安排房间。你的程序一共需要处理M (1 </div>
<div>&lt;= M &lt; 50,000)个按输入次序到来的住店或退房的请求。第一个请求到来前，旅店中所有房间都是空闲的。</div></div>

# Input

<div class="content"><div>* 第1行: 2个用空格隔开的整数：N、M</div>
<div>* 第2..M+1行: 第i+1描述了第i个请求，</div>
<div>如果它是一个订房请求，则用2个数字 1、D_i描述，数字间用空格隔开；</div>
<div>如果它是一个退房请求，用3 个以空格隔开的数字2、X_i、D_i描述</div></div>

# Output

<div class="content"><div>* 第1..??行: 对于每个订房请求，输出1个独占1行的数字：</div>
<div>如果请求能被满足 ，输出满足条件的最小的r；如果请求无法被满足，输出0</div></div>

# Sample Input

<div class="content"><span class="sampledata">10 6<br/>
1 3<br/>
1 3<br/>
1 3<br/>
1 3<br/>
2 5 5<br/>
1 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
4<br/>
7<br/>
0<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

