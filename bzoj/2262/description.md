
# Description

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">量子力学指出，宇宙并非只有一种形态。 <br/>
根据量子理论，一件事件发生之后可以产生不同的后果，而所有可能的后果都会形成自己的宇宙。 <br/>
我们可以把一个宇宙看成一个时间轴，虫洞可以看成不同宇宙的不同时间之间的跳跃。虫洞非常的不稳定，存在时间只有一瞬间。 <br/>
如果存在虫洞事件(U1,t1,U2,t2)那么在宇宙U1的t1时间和宇宙U2的t2时间会被连接，此时就会发生时空跳跃现象。 <br/>
你可以认为：同一个宇宙同一个时刻最多只存在一个虫洞事件。 <br/>
为了研究虫洞的性质，科学家向宇宙深处发射了虫洞探测器。 <br/>
该探测器会检测到自己存在的宇宙中的虫洞事件，并且一旦检测到虫洞事件就一定会进行跳跃。 <br/>
由于科学家并不确定虫洞事件的具体位置时间，所以暂时用电脑模拟很多平行宇宙以及虫洞事件。 <br/>
你将被告之探测器被放出时所在的宇宙名称和时间。 <br/>
你需要处理以下信息： <br/>
1. “ADD U1 t1 U2 t2” 表示在模拟中加入一个虫洞事件(U1,t1,U2,t2),其中U1和U2是字符串，t1和t2是32位非负整数 <br/>
2. “DEL U1 t1 U2 t2” 表示删除之前加入过的一个虫洞事件，保证该事件之前被ADD过。 <br/>
3. “QUERY” 表示询问探测器经过足够久的时间后会落入哪个宇宙，输出宇宙名称。如果答案不确定，请输出“*” </font><br/>
<br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">第一行: U0 t0 表示探测器发射的地点和时间。保证该时刻不存在虫洞事件。 <br/>
第二行： 正整数 Q 表示操作数 <br/>
接下来 Q 行: 2种操作，如描述，ADD或ASK。无多余字符。 </font><br/>
<br/>
</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">按照输入顺序，回答每一个ASK操作，直接输出宇宙名称或者“*”，每个回答占一行。</font></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">a 0                                           <br/>
9                                            <br/>
QUERY                                        <br/>
ADD a 2 b 2                                 <br/>
QUERY                                        <br/>
ADD a 4 b 4                                  <br/>
QUERY                                       <br/>
ADD a 3 a 5                                  <br/>
QUERY                                        <br/>
DEL a 4 b 4                                  <br/>
QUERY   </span></div>

# Sample Output

<div class="content"><span class="sampledata">a<br/>
b<br/>
a<br/>
b<br/>
b<br/>
</span></div>

# Hint

<div class="content"><p></p><p><font face="Times New Roman"> 1≤Q≤200000 时刻均为非负且小于2147483648。宇宙名称为长度不超过20的小写字母串，不同的宇宙数目≤1000</font></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

