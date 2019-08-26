
# Description

<div class="content"><div>在一个迷宫中有一个蛋糕。作为一个吃货，Luna非常想吃到这块蛋糕。现</div>
<div>在Luna手里有这个迷宫的地图，该地图是一个r行c列的网格图，每个格子包</div>
<div>含了下述4种字符中的一种：</div>
<div>“#”表示这里是墙砖，不能通过；</div>
<div>“.”表示这里是空地，可以通过；</div>
<div>“S”表示Luna的初始位置；</div>
<div>“C”表示蛋糕的位置。</div>
<div>Luna只能在空地上行走，并且只能从一个格子走到与这个格子有公共边的</div>
<div>相邻格子上。另外，整个地图的四周都是被墙砖所环绕的。</div>
<div>为了能更快吃到蛋糕，Luna不知从哪里获得了一把次元枪，这把枪可以用</div>
<div>来制造传送门。该枪的使用说明如下：</div>
<div>1.在任何时候，Luna可以选择上下左右四个方向中的一个开一枪。当她向</div>
<div>一个方向开枪之后，子弹会撞到这个方向上第一个遇到的墙砖，并在这个墙砖面</div>
<div>向她的面上开启一个传送门。</div>
<div>2.由于能量限制，在同一时刻最多存在两个传送门。如果已经存在两个传</div>
<div>送门，那么当Luna再开枪时，其中一个传送门会被回收用于补充能量，回收哪</div>
<div>一个由Luna自己决定。当Luna向某个传送门开枪时，会有一个新的传送门取代</div>
<div>它，即在一块墙砖的一个面上同时只能存在一个传送门。</div>
<div>3.当存在两个传送门时，Luna可以进入其中任意一个传送门，然后会从另</div>
<div>外一个传送门走出。</div>
<div>由于Luna枪法一流，所以开枪是不耗时的。Luna从一个格子走到任意一个</div>
<div>相邻格子的耗时为1，穿越传送门的耗时也为1。</div>
<div>现在Luna把地图给了你，她想知道她吃到蛋糕的最少耗时是多少，你不忍</div>
<div>心拒绝这样一位少女的请求，所以你绞尽脑汁也要把这个问题解决。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数r,c。</div>
<div>接下来r行每行c个字符，表示地图。“S”和“C”均只会出现一次。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行一个整数，表示最少耗时。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
.#.C<br/>
.#.#<br/>
....<br/>
S...</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1 ≤ r, c ≤ 1000，Luna 一定能吃到蛋糕</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

