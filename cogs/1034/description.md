# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">柠檬当上了警察局长！</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目背景】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">『Citric杯』NOIP模拟赛 I 第三题</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon因为偶然的原因，当上了警察局长。而一上任，他就碰到了个大麻烦：追捕周克华。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">周克华是人尽皆知的抢劫杀人犯，而就在几天前，他在Lemon辖区内的银行门口，枪杀了一名储户后逃之夭夭。Lemon知道，如果他抓不住周克华，他的警察局长恐怕就当不下去了。为了能继续当他的警察局长，Lemon决定倾警察局之物力全力追捕。Lemon的辖区可以表示为一张边上带权的无向图。银行位于结点1。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon仔细研究周克华的案底后得出以下结论：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">首先，周克华拥有极强的反侦查能力，因此，他深知不走回头路的重要性。他永远不会访问任何一个结点两次。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">其次，周克华深知多走一分钟路就多一分钟暴露的危险，而且他之前已经完全摸清了辖区的地形，因此他总是走最短路，也就是，他访问任何一个结点时，走的路线都是从银行到这里的最短路。为了简化题目，我们保证从银行（结点1）到任何一个结点的最短路都是唯一的。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">再次，周克华知道，为了尽可能远离案发现场，他必须不停的运动。也就是说，只要有相邻的结点能满足“不走回头路、只走最短路”的前提，他一定会移动。如果有多个相邻结点可供选择，他会随机等概率选择一个作为他的移动目标。如果没有结点满足这一要求，那么周克华就会选择遁入深山之中，而可以想象在距离案发现场十万八千里的山区里抓捕周克华的难度，所以一旦周克华遁入山中，也就意味着Lemon的抓捕行动失败了。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon分析出了以上结论后决定，只能在结点上布置警察，实施埋伏抓捕。但是，周克华的身体素质、反侦查能力和使用武器技术都十分优秀，因此，即使周克华遇到了埋伏，也有一定几率杀害所有参与埋伏的警察后逃脱。当然，随着埋伏的警察的数目的增多，逃脱几率会减小。如果逃脱成功，周克华会像什么都没发生一样，继续按上文所述的方式行动。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">注意，周克华一旦到达一个结点，埋伏在那里的警察会立即实施抓捕，只有周克华逃脱了在当前结点的抓捕后才能进行下一步行动（遁入群山或继续移动），包括结点1，也就是周克华需要先逃脱结点1的埋伏才能走出他的第一步。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon知道，他的设置警力方式决定了追捕成功的概率。他现在已经知道了他的辖区地图以及在不同地点设置不同数量的警力能成功抓捕周克华的概率，Lemon现在想要找到一个尽量优的方式设置警力，因此求助于你。你能告诉Lemon在最优的设置下，抓捕成功概率是多少吗？ Lemon到时或许会把高额的悬赏分给你一部分的哦～</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件第一行包含两个数N，M，分别表示辖区里的结点数目和边的数目。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来M行，每行3个数a,b,c，表示结点a和b之间有一条权值为c的无向边。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来一个数S，表示可以参与埋伏的警察个数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来N行，每行S个数，第i行第j个数Pij表示在结点i埋伏j个警察抓捕成功的概率。注意，如果不埋伏任何警察，那么显然绝不可能成功抓住周克华。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件仅包含一个实数，保留到4位小数，表示在最优警力设置下，抓捕成功的概率。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 2 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 4 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 4 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0.01 0.1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0.5 0.8</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0.5 0.8</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0.7 0.9</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0.6000</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">地图如下。（用字符画出来的，请使用等宽字体浏览以获得最佳效果）</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 1 ---(1)--- 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> |           |</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> |           |</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(2)         (3)</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> |           |</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> |           |</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 3 ---(1)--- 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">括号内的数为权值。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">周克华在结点1会等概率选择2或3逃跑。如果选择了2，那么下一步他会选择遁入群山，因为1已经访问过了，而继续往4走就不是最短路了（1=&gt;3=&gt;4比1=&gt;2=&gt;4短）；</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果选择了3，那么下一步他会继续往4跑，然后选择遁入群山（到达4后继续往2跑也不是最短路）。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">最优警力设置是，在2、4处各设置一名警察。这样如果周克华在第一步选择了2（50%概率），那么在2处有50%概率被抓，如没有被成功抓住则遁入群山。如果第一步选择了3（50%概率），在3处被抓概率为0（因为没有警察埋伏），但接下来周克华会往4走（100%概率），在4处被抓的概率是70% 所以总成功率是50%*50%+50%*70%=0.6</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据规模约定】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">时间限制为1s</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于20%数据，满足N,S&lt;=6.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于50%数据，满足N,S&lt;=30,每个结点度数不超过3.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%数据，满足N,S&lt;=200,M&lt;=20000,1&lt;=a,b&lt;=N,1&lt;=c&lt;=10000,0&lt;Pij&lt;=1.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据保证图中没有自环或重边,从结点1到任何一个结点的最短路唯一。</span><br/>
<br/>
<br/>
