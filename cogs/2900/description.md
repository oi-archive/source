# 题目描述


<h3>
【题目描述】
</h3>
<p>
Van最近很苦恼，因为他的平家boy们都太过强大了，Van深感力不从心。恰巧Van的朋友木吉刚从新日暮里回来，学会了一些膜法，当Van和木吉谈起自己的苦恼时，木吉表示愿意用自己的膜法帮Van解决问题。
</p>
<p>
<img alt="" src="/upload/image/20180211/20180211092425_82708.jpg"/> <img alt="" src="/upload/image/20180211/20180211121950_70824.jpg"/> 
</p>
<p>
Van的平家boy们都身经百战，有一腚的力量值，居住在与Van相邻的平坦的街道上。<strong>木吉的膜</strong><strong>法可以使boy们的力量值小于等于p，具体做法是通过摸</strong><strong></strong><strong>（%</strong><strong>），</strong>木吉在释放膜法的同时也会使用鬼步来让膜法的效率更高，<strong>即木吉会通过鬼步来完成瞬移，使他能够同时摸一段街道上的boy们</strong><strong>。</strong>但由于木吉的鬼步非常骚皮，所以他的膜法会受到影响，<strong>即p值具有极大的不稳定性，对于每一段街道，里面的boy们受到的抚</strong><strong>摸都会变化</strong>。
</p>
<p>
现在，木吉找到Van来汇报自己的鬼步，但是Van却忙着教训自己的平家boy们，于是Van就把这个任务交给了因为超速而被跤警Van拘留的你，<strong>但是Van为了调教你，同时想知道自己能否战胜那些平家boy们，就把自己的问题掺杂在木吉的鬼步中。</strong>作为王的我为了让你好好的接受Van的调教，就帮助你把Van的问题和木吉的鬼步分开，<strong>即0</strong><strong>代表Van的问</strong><strong>题，1</strong><strong>代表木吉的鬼</strong><strong>步</strong><strong>。</strong> 
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个整数n m，n代表平家boy们的数量，m代表木吉的鬼步和Van的问题的总数量。
</p>
<p>
接下来n行，每行一个整数代表一个平家boy的力量值；
</p>
<p>
接下来m行，每行一个操作，有如下两种情况：
</p>
<p>
0 a b   代表Van想让你告诉他当前从a到b（包含a b）的平家boy们的力量值的和；
</p>
<p>
1 a b p  代表木吉的鬼步是从a到b的瞬移，p的含义见题目描述。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每一个Van的询问，输出平家boy们的力量值的和。
</p>
<h3>
【样例输入】
</h3>
<pre>2 2</pre>
<pre> 5 </pre>
<pre> 7</pre>
<pre> 1 1 2 3</pre>
<pre> 0 1 2</pre>
<h3>
【样例输出】
</h3>
<pre>3</pre>
<h3>
【提示】
</h3>
<p>
 Van的平家boy们数量众多，但尻虑到木吉的感受，Van只要求他最多对100000只平家boy施展膜法。对于Van的每次询问和木吉的每次膜法，都有0&lt;a&lt;=b&lt;=100000。同时木吉受到鬼步的强大影响最多释放100000膜法（包含Van的询问）。
</p>
<h3>
【来源】
</h3>
<p>
 新日暮里唱片公司
</p>
<p>
<img alt="" src="/upload/image/20180211/20180211121538_24812.jpg"/> 
</p>
<p>
 
</p>
<p>
 
</p>
