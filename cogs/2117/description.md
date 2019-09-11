# 题目描述


<div id="psrc" style="margin-top:20px;display:none;">
<div class="pdsec">
试题来源
</div>
<div class="pdcont">
CodeChef February Challenge 2014
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<p>
<br/>
</p>
<div class="pdsec">
问题描述
</div>
<p>
厨师Hawlader和厨师Heickal是好朋友。除了烹饪以为，他们还喜爱算法。Hawlader喜欢图论而Heickal喜欢数论。<br/>
<br/>
又一次，厨师Hawlader给厨师Heickal讲授图论。“嘿，Heical，你应该更专注于对图论的学习。数论中还剩下什么呢？图论是这个世界的全部，你甚至可以将数论问题规划到图论来解决，你懂吗？”Hawlader说。而对于Heickal来说，他并不厌恶图论，根据她的理论，生活应该是数论，图论，动态规划，数据结构，ad hoc等等等等的混合。要成为一命优秀的厨师，你必须知道所有这些东西而不仅仅只有图论。<br/>
<br/>
Hecikal：“哦，你是图论的大师？那你知道DFS？”<br/>
Hawlader：“当然，DFS，深度优先搜索，这是一个基本的图论算法。”<br/>
Hecikal：“因此，对于任意一幅图，你可以按照DFS进入的时间给他们编号？”<br/>
Hawlader：“太简单了。用下面的伪代码就行了”<br/>
<br/>
int C = 1;<br/>
void DFS(int u)  {<br/>
new_number[u] = C;<br/>
C++;<br/>
// initially all value of visited array is set to false<br/>
visited[u] = true;<br/>
// here v can be chosen in an arbitrary order<br/>
for each v such that there is a edge from u to v<br/>
if(visited[v] == false)<br/>
DFS(v);<br/>
}<br/>
<br/>
Hecikal：“好的，我可以给你一个难一点的问题了。”<br/>
Hawlader：“什么？放马过来吧！”<br/>
Hecikal：“我会给你一个有N个节点，M条边的有向图。每个节点编号按照是上面的伪代码生成的。并且，从1号点出发，所有的节点都可达。”<br/>
Hawlader：“好的，那问题呢？”<br/>
Hecikal：“等等，我给你一些定义，一个节点x被称为是另一个节点y的supreme vertex，如果存在一条有向路x = v_0, v_1, ..., v_k = y，满足x &lt; y &lt; w，对于所有0 &lt; i &lt; k。也就是说，一条从x出发到y有0个或更多个中间节点的有向路，满足所有中间节点的编号都大于x和y的编号，并且x的编号小于y。如果v是另一个节点w所有的supreme vertex中编号最小的，v被称为是w的superior vertex。你将得到Q个询问。每个询问，将会给定一个节点v，你需要找出有多少节点，将v视为其superior vertex。”<br/>
Hawlader：“噢！呃...”
</p>
<p>
厨师Hawlader无法解决这个问题，他正在向你求助。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<div class="pdsec">
输入格式
</div>
<p>
输入数据的第一行有一个整数T，表示数据的组数。每组测试数据的地养护，有三个整数N,M,Q。接下来的M行，每行有一对整数U_i和V_i表示一条从U_i出发，指向V_i的有向边。接下来的一行包含Q个用空格隔开的整数，P_1,P_2,...,P_q。每个整数表示一组询问。
</p>
<p>
<br/>
</p>
<div class="pdsec">
输出格式
</div>
<p>
对于每组询问，输出一行表示对应的结果。
</p>
<p>
<br/>
</p>
<div class="pdsec">
样例输入
</div>
<p>
2<br/>
3 3 3<br/>
1 2<br/>
1 3<br/>
3 2<br/>
1 2 3<br/>
8 9 8<br/>
1 2<br/>
1 7<br/>
2 3<br/>
2 5<br/>
3 4<br/>
5 6<br/>
7 8<br/>
6 4<br/>
8 4
</p>
<p>
1 2 3 4 5 6 7 8
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<div class="pdsec">
样例输出
</div>
<p>
2 0 0
</p>
<p>
3 2 0 0 1 0 1 0
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<div class="pdsec">
样例说明
</div>
<p>
样例一中，结点3有且仅有1作为其supreme vertex和superior vertex。因为有一条1到3的有向边。结点2有一个superme vertex 1（1 -&gt; 3 -&gt; 2）。因为结点2仅有这一个supreme vertex，所以这个结点也是其superior vertex。
</p>
<p>
样例二中，结点4有两个supreme vertex 1 （1 -&gt; 7 -&gt; 8 -&gt; 4） 和 2 （2 -&gt; 5 -&gt; 6 -&gt; 4），因此结点1是结点4的superior vertex。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<div class="pdsec">
数据规模和约定
</div>
<p>
1 &lt;= T &lt;= 10<br/>
2 &lt;= N &lt;= 100000<br/>
N-1 &lt;= M &lt;= 200000<br/>
1 &lt;= Q &lt;= 100000<br/>
1 &lt;= U_i, V_i &lt;= N,  且U_i不等于V_i
</p>
<p>
没有重边，所有结点从1号结点可达
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<div id="pcont2" style="margin-top:20px;display:none;">
<p>
【问题描述】<br/>
    厨师Hawlader和厨师Heickal是好朋友。除了烹饪以为，他们还喜爱算法。Hawlader喜欢图论而Heickal喜欢数论。
</p>
<p>
 
</p>
<p>
    又一次，厨师Hawlader给厨师Heickal讲授图论。“嘿，Heical，你应该更专注于对图论的学习。数论中还剩下什么呢？图论是这个世界的全部，你甚至可以将数论问题规划到图论来解决，你懂吗？”Hawlader说。而对于Heickal来说，他并不厌恶图论，根据她的理论，生活应该是数论，图论，动态规划，数据结构，ad hoc等等等等的混合。要成为一命优秀的厨师，你必须知道所有这些东西而不仅仅只有图论。
</p>
<p>
 
</p>
<p>
    Hecikal：“哦，你是图论的大师？那你知道DFS？”
</p>
<p>
    Hawlader：“当然，DFS，深度优先搜索，这是一个基本的图论算法。”
</p>
<p>
    Hecikal：“因此，对于任意一幅图，你可以按照DFS进入的时间给他们编号？”
</p>
<p>
    Hawlader：“太简单了。用下面的伪代码就行了”
</p>
<p>
 
</p>
<p>
int C = 1;
</p>
<p>
void DFS(int u)  {
</p>
<p>
    new_number[u] = C;
</p>
<p>
    C++;
</p>
<p>
    // initially all value of visited array is set to false
</p>
<p>
    visited[u] = true;
</p>
<p>
    // here v can be chosen in an arbitrary order
</p>
<p>
    for each v such that there is a edge from u to v
</p>
<p>
        if(visited[v] == false)
</p>
<p>
            DFS(v);
</p>
<p>
}
</p>
<p>
 
</p>
<p>
    Hecikal：“好的，我可以给你一个难一点的问题了。”
</p>
<p>
    Hawlader：“什么？放马过来吧！”
</p>
<p>
    Hecikal：“我会给你一个有N个节点，M条边的有向图。每个节点编号按照是上面的伪代码生成的。并且，从1号点出发，所有的节点都可达。”
</p>
<p>
    Hawlader：“好的，那问题呢？”
</p>
<p>
    Hecikal：“等等，我给你一些定义，一个节点x被称为是另一个节点y的supreme vertex，如果存在一条有向路x = v_0, v_1, ..., v_k = y，满足x &lt; y &lt; w，对于所有0 &lt; i &lt; k。也就是说，一条从x出发到y有0个或更多个中间节点的有向路，满足所有中间节点的编号都大于x和y的编号，并且x的编号小于y。如果v是另一个节点w所有的supreme vertex中编号最小的，v被称为是w的superior vertex。你将得到Q个询问。每个询问，将会给定一个节点v，你需要找出有多少节点，将v视为其superior vertex。”
</p>
<p>
    Hawlader：“噢！呃...”
</p>
<p>
    厨师Hawlader无法解决这个问题，他正在向你求助。<br/>
【输入格式】
</p>
<p>
    输入数据的第一行有一个整数T，表示数据的组数。每组测试数据的地养护，有三个整数N,M,Q。接下来的M行，每行有一对整数U_i和V_i表示一条从U_i出发，指向V_i的有向边。接下来的一行包含Q个用空格隔开的整数，P_1,P_2,...,P_q。每个整数表示一组询问。
</p>
<p>
【输出格式】
</p>
<p>
    对于每组询问，输出一行表示对应的结果。<br/>
【样例输入】
</p>
<p>
2
</p>
<p>
3 3 3
</p>
<p>
1 2
</p>
<p>
1 3
</p>
<p>
3 2
</p>
<p>
1 2 3
</p>
<p>
8 9 8
</p>
<p>
1 2
</p>
<p>
1 7
</p>
<p>
2 3
</p>
<p>
2 5
</p>
<p>
3 4
</p>
<p>
5 6
</p>
<p>
7 8
</p>
<p>
6 4
</p>
<p>
8 4
</p>
<p>
 1 2 3 4 5 6 7 8
</p>
<p>
【样例输出】
</p>
<p>
2 0 0
</p>
<p>
3 2 0 0 1 0 1 0
</p>
<p>
【样例解释】
</p>
<p>
    样例一中，结点3有且仅有1作为其supreme vertex和superior vertex。因为有一条1到3的有向边。结点2有一个superme vertex 1（1 -&gt; 3 -&gt; 2）。因为结点2仅有这一个supreme vertex，所以这个结点也是其superior vertex。
</p>
<p>
    样例二中，结点4有两个supreme vertex 1 （1 -&gt; 7 -&gt; 8 -&gt; 4） 和 2 （2 -&gt; 5 -&gt; 6 -&gt; 4），因此结点1是结点4的superior vertex。
</p>
<p>
【数据规模和约定】
</p>
<p>
1 &lt;= T &lt;= 10
</p>
<p>
2 &lt;= N &lt;= 100000
</p>
<p>
N-1 &lt;= M &lt;= 200000
</p>
<p>
1 &lt;= Q &lt;= 100000
</p>
<p>
1 &lt;= U_i, V_i &lt;= N,  且U_i不等于V_i
</p>
<p>
没有重边，所有结点从1号结点可达
</p>
</div>
<br/>
<div id="pcode" class="code">
<div id="pcodesu" style="display:none;">
<hr/>
<span class="notice">这是一道完善程序的试题，你只需要在下面程序标注的&#34;<span class="code"><span class="Y">@你的代码</span></span>&#34;的位置补充适当的语句或语句段使程序能正确运行即可，在提交的时候，你要提交的内容只包括补充的内容，不包括其他的代码。</span> 
</div>
</div>
