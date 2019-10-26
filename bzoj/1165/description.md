
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">厌倦了你的工作, 你从IT行业跳槽到了一家水产养殖公司.</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">你的第一项任务是把两个水槽分隔开. 尝试了操作手册的内容并仔细观察之后, 你了解了水槽的工作机制.</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">两个水槽由n条通道相连, 每个通道上有两个水闸. 只有两个水闸都打开时通道才开启, 其余情况下通道都是封闭的.</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">这2n个水闸的状态由开关控制. 每个水闸的状态恰好由一个开关控制, 当然某个开关可能控制多个水闸或者不控制任何水闸. 一条通道上的两个水闸也有可能由同一个开关控制.</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">开关一共有m个, 编号为1; 2;……;m, 每个开关有两种状态: 开和关. 而水闸受开关控制的方式有两种:</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>开关开时水闸打开, 开关关时水闸关闭.</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>开关关时水闸打开, 开关开时水闸关闭.</span></div>
<p><span style="font-size: medium"><img height="454" alt="" width="301" src="/source/bzoj/1165/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwOC8xMSgzKS5qcGc=.jpg"/></span></p></div>

# Input

<div class="content"><p>输入的第一行包含两个整数n和m.<br/>
接下来n行每行包含了一条通道的信息, 由四个整数a; S a; b; S b表示. a和b表示控制两个水闸的开关编号,而S a和S b为0或1, 表示水闸受开关控制的方式. S i = 0表示开关i关时水闸关, 以此类推.</p></div>

# Output

<div class="content"><p>如果存在一种开关的状态使得所有通道都封闭, 则输出m行, 每行一个整数0或1. 第i行为0表示编号为i的开关应当关, 为1则表示开关应当开.<br/>
如果不存在这样的状态, 输出一行“IMPOSSIBLE”.</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
1 0 2 1<br/>
1 0 2 0<br/>
1 1 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体"><font size="3">对所有数据<span lang="EN-US">, n &lt;= 250000;m &lt;= 500000.</span></font></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

