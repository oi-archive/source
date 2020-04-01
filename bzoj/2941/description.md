
# Description

<div class="content"><div style="text-indent: 121.5pt"><span style="font-size: medium">在Byteland的安全局（BSA）里有职员和指挥官俩种等级。任一员工的资料都可在档案库里找到。在属于每个员工的文件夹中，都有一份Signatures，Signatures是其他的员工（职员或者指挥官）为他的忠诚所做的保证。每一新雇的职员都必须至少得到一份保证，但随着时间推移，保证人也会增加。BSA最近发现，在他们的指挥官的圈子里已经有来自敌方Microsoftland的间谍的渗入。那么，BSA接下来就会雇佣其他的间谍作为他的职员由于这个间谍指挥官的保证或者其他雇佣间谍的保证。这些间谍有专门来自间谍员工的保证。</span></div>
<div style="text-indent: 27pt"><span style="font-size: medium">我们说一个职员的可信度值得怀疑，如果他没有获得任何一个不是间谍的指挥官的间接保证。即不存在这样的员工序列<i>p</i><sub>1</sub>, <i>p</i><sub>2</sub>,..., <i>p</i><sub>k</sub>，其中<i>p</i><sub>1</sub>为一不是间谍的指挥官，对于员工<i>p</i><sub>k </sub>(for <i>i</i>=1,..., <i>k</i>-1)，<i>p</i><sub>i</sub>为<i>p<sub>i</sub></i><sub>+1</sub>作保证。</span></div>
<div style="text-indent: 27pt"><span style="font-size: medium">如果我们假定一个指挥官是间谍，则使得他所担保的职员被怀疑是间谍。BSA司令部急须知到这些职员的名单。</span></div>
<div><span style="font-size: medium"><b>举例</b></span></div>
<div><span style="font-size: medium">     指挥官：   阿莉斯，Gregor</span></div>
<div style="text-indent: 31.5pt"><span style="font-size: medium">职员：</span></div>
<div style="margin: 0cm 0cm 0pt 84pt"><span style="font-size: medium">鲍勃（阿莉斯保证），查利（鲍勃保证），戴维（鲍勃，并且查利保证），伊夫（阿莉斯和Gregor保证），夫兰克（伊夫保证），亨利（Gregor和Isabelle保证），Isabelle（Gregor和亨利保证）。</span></div>
<div style="text-indent: 31.5pt"><span style="font-size: medium">怀疑对象：</span></div>
<div style="text-indent: 84pt"><span style="font-size: medium">鲍勃，查利，戴维，亨利，Isabelle。</span></div>
<div><span style="font-size: medium"><b>要求</b></span></div>
<div style="text-indent: 27pt"><span style="font-size: medium">写一程序：</span></div>
<div style="margin: 0cm 0cm 0pt 82.5pt; text-indent: -18pt"><span style="font-size: medium">1、 读入BSA的指挥官和职员人数以及作担保的信息；</span></div>
<div style="margin: 0cm 0cm 0pt 82.5pt; text-indent: -18pt"><span style="font-size: medium">2、 计算确定被怀疑为间谍的职员的名单表；</span></div>
<div style="margin: 0cm 0cm 0pt 82.5pt; text-indent: -18pt"><span style="font-size: medium">3、 结果输出</span></div></div>

# Input

<div class="content"><div> <span style="font-size: medium">第一行为一正整数n，1 &lt;= <i>n</i> &lt;= 500，表示BSA的员工个数，员工从1到n标号。下面的n行是职员担保的描述。第<i>i+1</i> 行的数字是给第<i>I</i>个员工作担保的员工编号，它是用单个空格隔开的数字序列。每行的第一个数字0 &lt; <i>m<sub>i </sub></i>，他表示为给第<i>I </i>个员工作担保的其他员工的个数。接下来的<i>m<sub>i </sub></i><sub> </sub>个数字分别是这些员工的编号。员工的指挥官不需要任何人为其做担保。</span></div></div>

# Output

<div class="content"><div style="text-indent: 27pt"><span style="font-size: medium">输出：</span></div>
<div style="margin: 0cm 0cm 0pt 77.25pt; text-indent: -18pt"><span style="font-size: medium">1、 被怀疑为间谍的职员的编号，如果存在的话。连续输出，每行输出一个，升序。</span></div>
<div style="margin: 0cm 0cm 0pt 77.25pt; text-indent: -18pt"><span style="font-size: medium">2、 仅输出一单词BRAK，如果这样的职员不存在的话。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
0<br/>
1 1<br/>
1 2<br/>
2 2 3<br/>
2 1 7<br/>
1 5<br/>
0<br/>
2 7 9<br/>
2 7 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
4<br/>
8<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

