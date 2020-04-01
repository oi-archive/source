
# Description

<div class="content"><div>小q有n只机器人，一开始他把机器人放在了一条数轴上，第i只机器人在ai的位置上静止，而自己站在原点。在这</div>
<div>之后小q会执行一些操作，他想要命令一个机器人向左或者向右移动x格。但是机器人似乎听不清小q的命令，事实</div>
<div>上它们会以每秒x格的速度匀速移动。看着自己的机器人越走越远，小q很着急，他想知道当前离他（原点）最远的</div>
<div>机器人有多远。具体的操作以及询问见输入格式。注意，不同的机器人之间互不影响，即不用考虑两个机器人撞在</div>
<div>了一起的情况。</div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>共有m个事件，输入将会按事件的时间顺序给出。第一行两个正整数n,m。接下来一行n个整数，第i个数是ai，表示</div>
<div>第i个机器人初始的位置（初始移动速度为0）。接下来m行，每行行首是一个非负整数ti，表示该事件点发生的时</div>
<div>刻（以秒为单位）。第二个是一个字符串S，代表操作的种类。数字与字符串之间用一个空格隔开。接下来的输入</div>
<div>按S的种类分类。若S是“command”（不带引号），则接下来两个整数ki,xi，表示小q对第ki个机器人执行了操作</div>
<div>，该机器人的速度将会被重置，变为向数轴正方向每秒移动xi格（若xi为负数就相当于向数轴负方向每秒移动∣xi</div>
<div>∣格）。保证1≤ki≤n。若S是“query”（不带引号），则你需要输出当前离原点最远的机器人有多远。保证t1≤</div>
<div>t2≤t2≤...≤tm。（注：若同一时间发生多次操作，则按读入顺序依次执行）</div>
<div>
<div></div>
</div></div>

# Output

<div class="content"><div>对于每个query询问，输出一行，包含一个整数表示正确的答案。C/C++输入输出longlong时请用%lld。由于本题数</div>
<div>据量较大，建议不要使用cin/cout进行输入输出。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
-20 0 20 100<br/>
10 command 1 10<br/>
20 command 3 -10<br/>
30 query<br/>
40 command 1 -30<br/>
50 query</span></div>

# Sample Output

<div class="content"><span class="sampledata">180<br/>
280</span></div>

# Hint

<div class="content"><p></p><div>第一个命令执行时，各个机器人的位置为：−20,0,20,100。</div><br/>
<div>第二个命令执行时，各个机器人的位置为：80,0,20,100。</div><br/>
<div>第一个询问时，各个机器人的位置为：180,0,−80,100。</div><br/>
<div>第三个命令执行时，各个机器人的位置为：280,0,−180,100。</div><br/>
<div>第二个询问时，各个机器人的位置为：−20,0,−280,100。</div><br/>
<div>限制与约定</div><br/>
<div>设 command 的个数为 C，query 的个数为 Q。（所以 C+Q=m）</div><br/>
<div>对于所有的事件满足 0≤ti≤10^9，对于所有的 command 满足 ∣xi∣≤10^4。</div><br/>
<div>对于所有的机器人满足 ∣ai∣≤10^9。</div><br/>
<div>N,C&lt;=10^5</div><br/>
<div>Q&lt;=5*10^5</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年集训队互测 By  zhj">2015年集训队互测 By  zhj</a></p></div>

