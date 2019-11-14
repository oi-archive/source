
# Description

<div class="content"><p>　　D博士对物理有着深入的研究，经典物理、天体物理、量子物理都有着以他的名字命名的定理。最近D博士着迷<br/>
于研究粒子运动的无规则性。对圣经深信不疑的他相信，上帝创造的任何事物必然是有序的、有理可循的，而不是<br/>
无规则的、混沌的。 经过长时间的研究，D博士找到了很多出现相当频繁的轨迹片断，他把这些轨迹片断储存在一<br/>
个很大的数据库内。他需要你帮助他写一个程序，对于一个给出的粒子运动轨迹，统计数据库中每个轨迹片断的出<br/>
现的次数。 为清楚起见，我们定义一个粒子的轨迹为二维平面上的一个点列（P1, P2, … PN）。点列P的一个子<br/>
列[i, j]定义为P中一段连续的子序列（Pi, Pi+1, … Pj）。点列P的一个子列[u, v]被称为点列Q = (Q1, Q2 … <br/>
Qv-u+1)在P中的一次出现，当且仅当Q经过有限次的平移、旋转、翻转、放缩之后得到Q’满足Q’k = Pu+k-1（k =<br/>
 1 … u – v + 1）。 对平面X-Y进行四种操作的解释平移 设平移向量为(dx, dy)，则任意点(x,y)平移后的结果<br/>
为(x+dx, y+dy) 旋转 设旋转角为t，则任意点(x,y)旋转后的结果为 (x cos t – y sin t, x sin t + y cos t)<br/>
 翻转 任意点(x,y) 翻转后的结果为(x, -y) 放缩 设放缩比例为p (p ≠ 0)，则任意点(x,y)放缩后的结果为(px,<br/>
 py)</p></div>

# Input

<div class="content"><p>　　第一行两个整数N、M，分别描述待处理的粒子运动轨迹的点列大小与数据库内的轨迹片断个数。接下来M行依<br/>
次给出每个轨迹片断。每行先是一个正整数K，表示该轨迹片断点列的长度。然后2K个整数，依次描述点列中的K个<br/>
点的横坐标与纵坐标。接下来一行2N个整数，依次描述待处理的粒子运动轨迹的点列中N个点的横坐标与纵坐标。<br/>
注：输入中的每条轨迹中任意相邻两点不会相同。</p></div>

# Output

<div class="content"><p>　　应包含M行，依次给出每个片段在待处理运动轨迹中的出现次数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
2 17 0 10 1<br/>
3 0 0 1 0 1 -1<br/>
0 0 1 0 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1</span></div>

# Hint

<div class="content"><p></p><p>N, K ≤ 200 000，<span style="color: rgb(255, 0, 0);">片段总长度 ≤ 1600000</span>，输入中给出所有点坐标绝对值均不大于10 000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢tangjz重新制作数据">鸣谢tangjz重新制作数据</a></p></div>

