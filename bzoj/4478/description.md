
# Description

<div class="content"><p>JSOI 的世界里一共有 N 个不同的事件（ 依次由 1 到 N 编号），以及 M 条线索。<br/>
每一条线索对应一个二元组(x,y)，表示事件 x 发生会导致事件 y 发生——注<br/>
意： 线索是单向的，也就是如果 y 发生了，并不代表 x 一定会发生。<br/>
线索是有传递性的， 即如果存在线索(x,y)以及(y,z)， 那么 x 发生则会导致 z<br/>
发生。<br/>
同时由于世界是合理的，任意一个事件 x 一定不会通过某些线索导致事件 x<br/>
本身发生。<br/>
另外，整个世界仅包含这 M 条线索， 我们不认为一些事件会凭空发生（就<br/>
像福尔摩斯永远不会认为诡异的凶杀案是源于神的谴责）。具体而言： 对于某<br/>
个事件 x， 如果 x 发生了，并且存在某个事件可能导致 x 发生，那么一定至少有<br/>
一个可能导致 x 发生的事件发生了。<br/>
现在已知世界上的 M 条线索，以及 D 个已经发生的事件，那么由此推断，<br/>
哪些事件一定已经发生了呢？</p></div>

# Input

<div class="content"><p>第一行包含用空格隔开的三个整数，分别为 N， M 和 D。<br/>
接下来 M 行，每行两个整数 x， y 表示线索(x,y)， 满足 1 &lt; = x, y &lt; = N。<br/>
接下来 D 行为 D 个 1 到 N 之间不同的整数， 表示已知的已经发生的事件。<br/>
1 &lt; = D &lt; = N &lt; = 1000， 1 &lt; = M &lt; = 100000</p></div>

# Output

<div class="content"><p>包含一行至少 D 个由空格隔开的严格递增的正整数， 表示根据 M条线索以及 D 个已知事件<br/>
JYY 所能推断出的一定发生了的事件。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 1<br/>
1 3<br/>
2 3<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
在第一个样例中，由于事件 1 和事件 2 这两个事件中的任何一个发生都会导<br/>
致事件 3 发生，所以我们并不能确定到底哪个事件发生了。<br/>
在第二个样例中，由于事件 4 发生了，所以事件 2 和事件 3 中至少有一个发<br/>
生了。而不论哪一个发生了，都可以推出事件 1 发生了。最终由于事件 1 发生了，<br/>
使得我们可以推断出，所有 4 个事件都必然发生了。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

