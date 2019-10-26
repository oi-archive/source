
# Description

<div class="content"><div>T公司是一家专门生产彩色珠子项链的公司，其生产的项链设计新颖、款式多样、价格适中，广受青年人的喜爱。</div>
<div>最近T公司打算推出一款项链自助生产系统，使用该系统顾客可以自行设计心目中的美丽项链。该项链自助生产系</div>
<div>统包括硬件系统与软件系统，软件系统与用户进行交互并控制硬件系统，硬件系统接受软件系统的命令生产指定的</div>
<div>项链。该系统的硬件系统已经完成，而软件系统尚未开发，T公司的人找到了正在参加全国信息学竞赛的你，你能</div>
<div>帮助T公司编写一个软件模拟系统吗？一条项链包含 N 个珠子，每个珠子的颜色是 1，2，…，c 中的一种。项链</div>
<div>被固定在一个平板上，平板的某个位置被标记位置 1 ，按顺时针方向其他位置被记为 2，3，…，N。</div>
<div><img src="/source/bzoj/1493/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9mZmYoMSkucG5n.png" width="211" height="239" alt=""/></div>
<div>你将要编写的软件系统应支持如下命令：</div>
<div><img src="/source/bzoj/1493/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9mYS5wbmc=.png" width="572" height="427" alt=""/></div></div>

# Input

<div class="content"><div>输入文件第一行包含两个整数 N，c ，分别表示项链包含的珠子数目以及颜色数目。</div>
<div>第二行包含 N 个整数，x1，x2，…，xn ，表示从位置 1 到位置 N 的珠子的颜色，1≤xi≤c 。</div>
<div>第三行包含一个整数 Q ，表示命令数目。接下来的 Q 行每行一条命令，如上文所述。N≤500000 ，Q≤500000，c≤1000 </div>
<div></div></div>

# Output

<div class="content"><p>对于每一个 C 和 CS 命令，应输出一个整数代表相应的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 2 3 2 1<br/>
4<br/>
C<br/>
R 2<br/>
P 5 5 2<br/>
CS 4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1</span></div>

# Hint

<div class="content"><p></p><div>注意旋转命令旋转“珠子”但不改变“位置”的编号，而反转命令始终以位置 1 为对称轴。例如当 N=10 时，项</div><br/>
<div>链上的位置编号如图1：</div><br/>
<div><img src="/source/bzoj/1493/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9jYy5wbmc=.png" width="366" height="214" alt=""/></div><br/>
<div><br/>
<div>但注意此时项链上的位置编号仍然如图1所示，于是翻转的对称轴不变。因而再执行一次“F”命令时，项链的颜色</div><br/>
<div>如图4所示。</div><br/>
<div>2. 关于CountSegment命令CS命令表示查询一个“线段”中有多少个“部分”。尤其注意当查询的长度</div><br/>
<div>等于 N 时，我们仍然将查询部分作为“线段”理解。例如在图4所示的情况中，执行“CS 1 10”命令，查询从位</div><br/>
<div>置 1 开始到位置 10 结束的这个长度为 10 的线段中有多少个“部分”，于是得到返回值 3 。与之形成对照的是</div><br/>
<div>，若执行“C”命令，返回值则为 2</div><br/>
</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

