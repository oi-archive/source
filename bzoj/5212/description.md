
# Description

<div class="content"><div>九条可怜是一个热爱阅读的女孩子。</div>
<div></div>
<div>这段时间，她看了一本非常有趣的小说，这本小说的架空世界引起了她的兴趣。</div>
<div></div>
<div>这个世界有n个城市，这n个城市被恰好n?1条双向道路联通，即任意两个城市都可以互相到达。同时城市1坐落在世</div>
<div>界的中心，占领了这个城市就称霸了这个世界。</div>
<div></div>
<div>在最开始，这n个城市都不在任何国家的控制之下，但是随着社会的发展，一些城市会崛起形成国家并夺取世界的</div>
<div>霸权。为了方便，我们标记第i个城市崛起产生的国家为第i个国家。在第i个城市崛起的过程中，第i个国家会取得</div>
<div>城市i到城市1路径上所有城市的控制权。</div>
<div></div>
<div>新的城市的崛起往往意味着战争与死亡，若第i个国家在崛起中，需要取得一个原本被国家j(j!=i)控制的城市的控</div>
<div>制权，那么国家i就必须向国家j宣战并进行战争。</div>
<div></div>
<div>现在，可怜知道了，在历史上，第i个城市一共崛起了ai次。但是这些事件发生的相对顺序已经无从考究了，唯一</div>
<div>的信息是，在一个城市崛起称霸世界之前，新的城市是不会崛起的。战争对人民来说是灾难性的。可怜定义一次崛</div>
<div>起的灾难度为崛起的过程中会和多少不同的国家进行战争（和同一个国家进行多次战争只会被计入一次）。可怜想</div>
<div>要知道，在所有可能的崛起顺序中，灾难度之和最大是多少。</div>
<div></div>
<div>同时，在考古学家的努力下，越来越多的历史资料被发掘了出来，根据这些新的资料，可怜会对ai进行一些修正。</div>
<div>具体来说，可怜会对ai进行一些操作，每次会将ax加上w。她希望在每次修改之后，都能计算得到最大的灾难度。</div>
<div></div>
<div>然而可怜对复杂的计算并不感兴趣，因此她想让你来帮她计算一下这些数值。</div>
<div>对题面的一些补充：</div>
<div>1:同一个城市多次崛起形成的国家是同一个国家，这意味着同一个城市连续崛起两次是不会和任何国家开战的：因</div>
<div>为这些城市原来就在它的控制之下。</div>
<div>2:在历史的演变过程中，第i个国家可能会有一段时间没有任何城市的控制权。但是这并不意味着第i个国家灭亡了</div>
<div>，在城市i崛起的时候，第i个国家仍然会取得1到i路径上的城市的控制权</div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行输入两个整数n,m表示城市个数和操作个数。</div>
<div>第二行输入n个整数表示ai的初始值。</div>
<div>接下来n-1行，每行输入两个整数ui,vi(1&lt;=ui,vi&lt;=n)描述了一条道路。</div>
<div>接下来m行每行输入两个整数xi,wi表示将axi加上wi</div>
<div>N,M&lt;=4*10^5</div>
<div>1 &lt;= ai, wi &lt;= 10^7, 1 &lt;= xi &lt;= n</div>
<div></div></div>

# Output

<div class="content"><div>输出共m+1行，第一行表示初始的ai的答案，接下来m行每行表示这次修正后的答案</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 1 1 1 1<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
2 1<br/>
3 1<br/>
4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
7<br/>
9<br/>
10<br/>
在修正开始之前，如果按照所在城市4,1,5,3,2的顺序崛起，那么依次会和0,1,2,1,2个<br/>
国家进行战争。这时一共会产生6对敌对关系。可以证明这是所有崛起顺序中的最大值。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

