
# Description

<div class="content"><p> 方伯伯为了吃到最传统最纯净的美食，决定亲自开垦一片菜园。</p>
<div>现有一片空地，方伯伯已经规划n个地点准备种上蔬菜。最新鲜的蔬菜需有最甘甜井水的灌溉，因此方伯伯</div>
<div>将要打出两口井，分别记为井A、井B。</div>
<div>现在问题来了，在何处打井？每颗蔬菜分别由哪口井来灌溉？</div>
<div>方伯伯不善于计算，于是提出以下几个原则，再根据这些原则找方案。</div>
<div>原则如下：</div>
<div>1.井必须打在它负责灌溉的蔬菜的正中心，即设它的坐标为(X,Y)，X(Y)为它负责灌溉的所有蔬菜的</div>
<div>横(纵)坐标之和的平均值。</div>
<div>2.所有蔬菜都需要被灌溉。</div>
<div>3.两口井都必须要灌溉至少一颗蔬菜。</div>
<div>4.到A井更近的蔬菜，必须由A井灌溉，到B井更近的蔬菜，必须由B井灌溉。距离相等相等时则可任意一口井灌溉。</div>
<div>当然两口井不能打到同一个位置，多株蔬菜当然也不会种在同一个位置。</div>
<div>方伯伯把他的开垦原则告诉了你，请你告诉他有多少种满足这些原则方案。</div>
<div>我们把灌溉1号蔬菜的井记为A号井，那么，只要A灌溉的蔬菜的集合不同，就是一种不同的方案。</div></div>

# Input

<div class="content"><p>输入1行包含1个整数n，代表方师傅的蔬菜的数目</p>
<div>接下来n行，每行包含2个整数，xi，yi，代表第i棵蔬菜的坐标。</div>
<div></div></div>

# Output

<div class="content"><div>输出包含1个整数，代表方师傅可行的方案数</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3 4<br/>
1 1<br/>
5 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p> 1&lt;=n&lt;=60，0&lt;=xi,yi&lt;=60</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

