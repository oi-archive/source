
# Description

<div class="content"><div>FUS公司是一家大型网络公司，总共拥有n台服务器。每一台服务器都有一个limit值，表示这台服务器的最大连接限制。在这n台服务器中，只有n-1条光纤线路连接，保证任意两台服务器可以互相通信。随着公司的发展、用户的增加，服务器的负担越来越重，一些服务器无法胜任任务，一些光纤也趋于老化。因此FUS常常对服务器进行一些调整：</div>
<div>更新操作：选中两个服务器x、y，用一条新的光纤连接它们，形成一个环。这时环上“加入时间”最早的光纤会被断开废弃。</div>
<div>修改操作：修改一个服务器的limit值，可以增大或减小，以胜任业务。</div>
<div>在用户访问时，FUS会智能选择服务器的处理。如果用户访问的内容在x到y服务器的路径上，FUS会自动分配一个k值，令x到y路径上limit值第k小的服务器服务用户。</div>
<div>FUS希望你能帮他实现这些功能。</div>
<div>（简化版：动态维护关于加入时间的最大生成树，带点权修改，多次询问树上给定两点间路径k小值）</div>
<p></p></div>

# Input

<div class="content"><div>第1行2个整数，n、m，表示服务器的数量和边的数量。</div>
<div>第2行n个整数，limit[1]到limit[n]，0&lt;=limit[i]&lt;=10^6，表示n个服务器的初始连接限制。</div>
<div>接下来n-1行，表示初始的n-1条光纤。这些光纤的输入顺序就是它们的加入时间顺序。</div>
<div>接下来m行，每行3个整数k、x、y，表示一个操作，总共有3种：</div>
<div>（1）k=-1，1&lt;=x,y&lt;=n，x不等于y，表示更新操作，连接x、y光纤，并断开环上最早加入的光纤；</div>
<div>（2）k=0，1&lt;=x&lt;=n，0&lt;=y&lt;=10^6，表示修改操作，将x服务器的limit值修改为y；</div>
<div>（3）1&lt;=k&lt;=n，1&lt;=x,y&lt;=n，x不等于y，表示一个用户访问的内容在x到y服务器的路径上，要求取limit值第k小的服务器服务用户。</div>
<div>对于第3种操作，保证k不超过x到y路径上的服务器数，也就是保证存在limit值第k小的服务器。</div>
<p></p></div>

# Output

<div class="content"><div>对于每一个第3种操作，输出一个数，表示x到y路径上limit值第k小的服务器的limit值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 4<br/>
1 2 3 4 5 6 7 8 9 10<br/>
1 2<br/>
2 3<br/>
2 4<br/>
2 5<br/>
3 6<br/>
3 7<br/>
1 8<br/>
8 9<br/>
9 10<br/>
-1 1 10<br/>
0 2 100002<br/>
2 2 8<br/>
3 6 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
6</span></div>

# Hint

<div class="content"><p></p><div>样例解释：</div><br/>
<div>第1个操作，更新操作，用光纤连接了1、10服务器，断开了1、8服务器之间的光纤。</div><br/>
<div>第2个操作，修改操作，将2的limit值从2修改成了100002。</div><br/>
<div>第3个操作，2到8之间的路径为2-1-10-9-8，limit值分别为100002、1、10、9、8，因此第2小的limit值为8。</div><br/>
<div>第4个操作，6到5之间的路径为6-3-2-5，limit值分别为6、3、100002、5，因此第3小的limit值为6。</div><br/>
<div>数据范围：</div><br/>
<div>本题有4种类型的数据。</div><br/>
<div>类型一（10%）：n=m=1000</div><br/>
<div>类型二（20%）：n=m=50000，0&lt;=k&lt;=n（即不存在更新操作）</div><br/>
<div>类型三（30%）：n=m=50000，保证询问的路径长度之和小于10^8。</div><br/>
<div>类型四（40%）：n=m=100000</div><br/>
<div>对于100%的数据，满足2&lt;=n,m&lt;=100000、每时每刻的limit值&lt;=10^6。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By immortalCO">By immortalCO</a></p></div>

