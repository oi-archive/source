
# Description

<div class="content"><div>四年一度的幻想乡大选开始了，最近幻想乡最大的问题是很多来历不明的妖</div>
<div>怪涌入了幻想乡，扰乱了幻想乡昔日的秩序。但是幻想乡的建制派妖怪（人类）</div>
<div>博丽灵梦和八云紫等人整日高谈所有妖怪平等，幻想乡多元化等等，对于幻想乡</div>
<div>目前面临的种种大问题却给不出合适的解决方案。</div>
<div>风间幽香是幻想乡里少有的意识到了问题的严重性的大妖怪。她这次勇敢的</div>
<div>站了出来参加幻想乡大选。提出包括在幻想乡边境建墙（并让人类出钱），大力</div>
<div>开展基础设施建设挽回失业率等一系列方案，成为了大选年出人意料的黑马并顺</div>
<div>利的当上了幻想乡的大统领。</div>
<div>幽香上台以后，第一项措施就是要修建幻想乡的公路。幻想乡有 N 个城市，</div>
<div>之间原来没有任何路。幽香向选民承诺要减税，所以她打算只修 N- 1 条路将</div>
<div>这些城市连接起来。但是幻想乡有正好 N- 1 个建筑公司，每个建筑公司都想</div>
<div>在修路的过程中获得一些好处。</div>
<div>虽然这些建筑公司在选举前没有给幽香钱，幽香还是打算和他们搞好关系，</div>
<div>因为她还指望他们帮她建墙。所以她打算让每个建筑公司都负责一条路来修。</div>
<div>每个建筑公司都告诉了幽香自己有能力负责修建的路是哪些城市之间的。所</div>
<div>以幽香打算选择 N-1 条能够连接幻想乡所有城市的边，然后每条边都交给一</div>
<div>个能够负责该边的建筑公司修建，并且每个建筑公司都恰好修一条边。</div>
<div>幽香现在想要知道一共有多少种可能的方案呢？两个方案不同当且仅当它</div>
<div>们要么修的边的集合不同，要么边的分配方式不同。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数 N(N&lt;=17)， 表示城市个数。</div>
<div>接下来 N-1 行，其中第 i行表示第 i个建筑公司可以修建的路的列表：</div>
<div>以一个非负数mi 开头，表示其可以修建 mi 条路，接下来有mi 对数，</div>
<div>每对数表示一条边的两个端点。其中不会出现重复的边，也不会出现自环。</div>
<p></p></div>

# Output

<div class="content"><div>仅一行一个整数，表示所有可能的方案数对 10^9 + 7 取模的结果。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 3 2 4 2<br/>
5 2 1 3 1 3 2 4 1 4 3<br/>
4 2 1 3 2 4 1 4 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">17</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

