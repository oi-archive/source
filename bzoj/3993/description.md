
# Description

<div class="content"><p> 3333年，在银河系的某星球上，X军团和Y军团正在激烈地作战。在战斗的某一阶段，Y军团一共派遣了N个巨型机器人进攻X军团的阵地，其中第i个巨型机器人的装甲值为Ai。当一个巨型机器人的装甲值减少到0或者以下时，这个巨型机器人就被摧毁了。X军团有M个激光武器，其中第i个激光武器每秒可以削减一个巨型机器人Bi的装甲值。激光武器的攻击是连续的。这种激光武器非常奇怪，一个激光武器只能攻击一些特定的敌人。Y军团看到自己的巨型机器人被X军团一个一个消灭，他们急需下达更多的指令。为了这个目标，Y军团需要知道X军团最少需要用多长时间才能将Y军团的所有巨型机器人摧毁。但是他们不会计算这个问题，因此向你求助。</p></div>

# Input

<div class="content"><p>第一行，两个整数，N、M。</p>
<div>
<div>第二行，N个整数，A1、A2…AN。</div>
<div>第三行，M个整数，B1、B2…BM。</div>
<div>接下来的M行，每行N个整数，这些整数均为0或者1。这部分中的第i行的第j个整数为0表示第i个激光武器不可以攻击第j个巨型机器人，为1表示第i个激光武器可以攻击第j个巨型机器人。</div>
</div></div>

# Output

<div class="content"><p> 一行，一个实数，表示X军团要摧毁Y军团的所有巨型机器人最少需要的时间。输出结果与标准答案的绝对误差不超过10-3即视为正确。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
3 10<br/>
4 6<br/>
0 1<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.300000</span></div>

# Hint

<div class="content"><p></p><p> 【样例说明1】</p><br/>
<div>战斗开始后的前0.5秒，激光武器1攻击2号巨型机器人，激光武器2攻击1号巨型机器人。1号巨型机器人被完全摧毁，2号巨型机器人还剩余8的装甲值；</div><br/>
<div>接下来的0.8秒，激光武器1、2同时攻击2号巨型机器人。2号巨型机器人被完全摧毁。</div><br/>
<div>对于全部的数据，1&lt;=N, M&lt;=50，1&lt;=Ai&lt;=105，1&lt;=Bi&lt;=1000，输入数据保证X军团一定能摧毁Y军团的所有巨型机器人</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 感谢yts1999上传">Round 1 感谢yts1999上传</a></p></div>

