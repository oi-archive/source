
# Description

<div class="content"><p><span style="font-size: medium">The king of Byteotia, Byteasar, is returning to his country after a victorious battle. In Byteotia, there are n towns connected with only n-1 roads. It is known that every town can be reached from every other town by a unique route, consisting of one or more (direct) roads. (In other words, the road network forms a tree).<br/>
The king has just entered the capital. Therein a triumphal arch, i.e., a gate a victorious king rides through, has been erected. Byteasar, delighted by a warm welcome by his subjects, has planned a triumphal procession to visit all the towns of Byteotia, starting with the capital he is currently in.<br/>
The other towns are not ready to greet their king just yet - the constructions of the triumphal arches in those towns did not even begin! But Byteasar&#39;s trusted advisor is seeing to the issue. He desires to hire a number of construction crews. Every crew can construct a single arch each day, in any town. Unfortunately, no one knows the order in which the king will visit the towns. The only thing that is clear is that every day the king will travel from the city he is currently in to a neighboring one. The king may visit any town an arbitrary number of times (but as he is not vain, one arch in each town will suffice).<br/>
Byteasar&#39;s advisor has to pay each crew the same flat fee, regardless of how many arches this crew builds. Thus, while he needs to ensure that every town has an arch when it is visited by the king, he wants to hire as few crews as possible. Help him out by writing a program that will determine the minimum number of crews that allow a timely delivery of the arches.<br/>
</span></p>
<p><span style="font-size: medium"><span>Foreseeable和拿破仑的御用建筑师让·夏格伦在玩游戏</span></span></p>
<pre><span style="font-size: medium">		<br/>让·夏格伦会玩一个叫“凯旋门”的游戏：
 现在有一棵n个节点的树，表示一个国家 
1号点代表这个国家的首都 这个游戏由两个人
一起玩 一个玩家扮演视察国家的国王，
另一个扮演建立凯旋门的建筑师 一开始只有首都
有凯旋门 国王每次会从当前所在城市移动到一个相
邻的城市 在国王每次移动前，建筑师可以选择国家
内任意不超过k个城市建造出凯旋门 如果在任意一个
时刻，国王所在的城市没有凯旋门 那么国王会很生气，
扮演建筑师的玩家就输了 如果所有的城市都建立起了凯旋
门而国王一直没有走到有凯旋门的城市，那么建筑师就胜利了
 Foreseeable不会建筑，所以他扮演国王 而让·夏格伦则
“扮演”建筑师（他本来就是建筑师不需要扮演）  容易发现k
的大小非常影响游戏有趣度…… 如果k太大，那么建筑师可以在
国王行动前就在所有城市建出凯旋门，那么国王就没有胜利的希望了
，这样Foreseeable会掀桌不玩 如果k太小，那么Foreseeable
很有可能会发挥自己所剩无几的智商走到一个没有凯旋门的地方  
让·夏格伦想享受虐Foreseeable的快感 所以你要帮他确
定最小的k，使得在这个游戏中，如果建筑师足够聪明的
话，建筑师必胜  
Input 第一行一个整数n 接下来n-1行，每行两个整数u,v，表示u,v相邻 Output 一行一个整数表示最小的k 
Sample Input 
7 1 2 1 3 2 5 2 6 7 2 4 1
 Sample Output
 3 
Hint 1&lt;=n&lt;=300000 
样例解释：在foreseeable第一次行动前，让在2,3,4城市建好
凯旋门，然后接下来无论foreseeable走到哪个城市，
在5,6,7建好凯旋门就能保证让的胜利了  </span></pre>
<p></p></div>

# Input

<div class="content"><p><font size="4">The first line of the standard input contains a single integer n (1&lt;=N&lt;=300000) , the number of towns in Byteotia. The towns are numbered from 1 to n, where the number 1 corresponds to the capital.<br/>
The road network is described in n-1 lines that then follow. Each of those lines contains two integers,a,b(1&lt;=a,b&lt;=N) , separated by a single space, indicating that towns a and b are directly connected with a two way road.<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">The first and only line of the standard output is to hold a single integer, the minimum number of crews that Byteasar&#39;s advisor needs to hire.<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 2<br/>
1 3<br/>
2 5<br/>
2 6<br/>
7 2<br/>
4 1<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
Explanation of the example: On the first day, triumphal arches need to be erected in towns 2, 3, 4. On the second day, they should be erected in towns 5, 6, 7.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Wcmg提供译文">鸣谢Wcmg提供译文</a></p></div>

