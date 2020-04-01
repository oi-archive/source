
# Description

<div class="content"><div>
<div>每年万圣节，威斯康星的奶牛们都要打扮一番，出门在农场的N(1≤N≤100000)个牛棚里转悠，来采集糖果．她们</div>
<div>每走到一个未曾经过的牛棚，就会采集这个棚里的1颗糖果． 农场不大，所以约翰要想尽法子让奶牛们得到快乐．</div>
<div>他给每一个牛棚设置了一个“后继牛棚”．牛棚i的后继牛棚是Xi．他告诉奶牛们，她们到了一个牛棚之后，只要</div>
<div>再往后继牛棚走去，就可以搜集到很多糖果．事实上这是一种有点欺骗意味的手段，来节约他的糖果．  第i只奶</div>
<div>牛从牛棚i开始她的旅程．请你计算，每一只奶牛可以采集到多少糖果．</div>
</div></div>

# Input

<div class="content"><div>第1行输入N，之后一行一个整数表示牛棚i的后继牛棚Xi，共N行．</div></div>

# Output

<div class="content"><div>共N行，一行一个整数表示一只奶牛可以采集的糖果数量．</div></div>

# Sample Input

<div class="content"><span class="sampledata">4        //有四个点<br/>
1       //1有一条边指向1<br/>
3      //2有一条边指向3<br/>
2     //3有一条边指向2<br/>
3<br/>
INPUT DETAILS:<br/>
Four stalls.<br/>
* Stall 1 directs the cow back to stall 1.<br/>
* Stall 2 directs the cow to stall 3<br/>
* Stall 3 directs the cow to stall 2<br/>
* Stall 4 directs the cow to stall 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
2<br/>
3<br/>
//Cow 1: Start at 1, next is 1. Total stalls visited: 1. <br/>
Cow 2: Start at 2, next is 3, next is 2. Total stalls visited: 2. <br/>
Cow 3: Start at 3, next is 2, next is 3. Total stalls visited: 2. <br/>
Cow 4: Start at 4, next is 3, next is 2, next is 3. Total stalls visited: 3.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

