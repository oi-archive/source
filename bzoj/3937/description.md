
# Description

<div class="content"><p> “世界充满着各种if，我们存在着的这个世界也不过是为数众多的if的结果中的一个，而未来则更是由于无限的if而混沌流动着的世界。”</p>
<div>在某一条世界线中，你可能正在经营一个跨国公司，想想是不是有点激动呢。在那一个世界中，你正被营销网络的设计问题所困扰。</div>
<div>你的跨国公司在n个国家设立了销售网点，国家由1到n编号，这n个国家由m条双向航线连接。如果把国家看作结点把航线看作边，可以抽象成一个无向图。</div>
<div>你已经在其中的S个国家设立了分公司。你会买下一些航线的VIP以加速你的商品运输。</div>
<div>无论这条世界线出了什么偏差，你是OIer这个事实是不会改变的，所以你对VIP航线购买方案有着苛刻的要求：</div>
<div>以任意一个国家作为出发点，都无法只经过VIP航线且不经过重复的国家回到出发点。即购买的VIP航线形成原图的一个生成森林。</div>
<div>从任意一个分公司出发都可以只经过VIP航线到达另一个分公司。</div>
<div>每条航线都有一个权值，表示购买该航线的VIP的费用。敏锐的你一定一眼发现了完成目标的最小总花费。但是这样不够任性不够土豪，这势必会影响公司未来的发展。于是机智的你决定求出总费用前k小的VIP航线购买方案。</div>
<div>两个VIP航线购买方案被认为是不同的，当且仅当存在至少一条航线只在其中一个购买方案中被买为VIP。</div>
<div>“if只是单纯的if罢了。就算有这样一个存在着goodif的平行世界，人类也不是能简单地跨过世界线，去到那里的。”</div>
<div>但是小小地遐想一下还是很美好的，所以就请你解决这个问题吧。</div>
<div>简要题意：求出前k小的生成森林，要求给定的S个点在森林中两两可达。</div>
<div></div></div>

# Input

<div class="content"><p>第一行，四个正整数n,m,S,k。</p>
<div>第二行，S个正整数，表示分公司所在的国家，保证读入的国家编号互不相同。</div>
<div>接下来m行，每行三个正整数ui，vi，ci，表示国家ui与vi之间有一条费用为ci的航线。保证1≤ui,vi≤n，且ui≠vi。</div></div>

# Output

<div class="content"><p> 输出k行，每行一个正整数，第i行的正整数表示总费用第i小的VIP航线购买方案的总费用。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 9 3 6<br/>
3 1 5<br/>
1 2 1<br/>
1 3 2<br/>
3 2 2<br/>
2 4 5<br/>
3 4 5<br/>
3 5 2<br/>
3 6 2<br/>
6 4 4<br/>
5 6 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
5<br/>
5<br/>
5<br/>
5<br/>
6</span></div>

# Hint

<div class="content"><p></p><p> 除题面样例外的，航线和分公司所在国家均是在n,m,S固定的情况下均匀随机生成的。对于所有航线，ci是从1到100的整数中均匀随机选取的。</p><br/>
<div>保证一定存在至少k种不同的VIP航线购买方案。</div><br/>
<div>N&lt;=50,M&lt;=100,S&lt;=15,K&lt;=50</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年集训队互测 By Stilwell">2015年集训队互测 By Stilwell</a></p></div>

