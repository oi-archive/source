
# Description

<div class="content"><div>Mr ZHU 在一个通讯公司工作，他承担了公司的网络协议设计任务。目前他致力于通过一条电缆从一台电脑发送数据到另一台电脑。在电缆中有<i>k</i> 种不同的电平，而每秒电平有1/<i>n</i> 种变化 (1/<i>n</i> 秒这个常数，我们称之为一个<b>脉冲</b>).数据打包发送时，包含了<i>m</i>个连续的脉冲。(即每 <i>m</i>/<i>n</i> 秒发送一个包).</div>
<div>由于技术原因, 在每个包里的电平并稳定为一个常数, 而是不得不一次次改变. 严格地讲,包含连续<i>l</i>个脉冲电平相同的数据包将不能发送.</div>
<div>如果某种协议允许发送<i>x</i> 个不同的包，那么能对一个包进行log<sub>2</sub><i>x</i>二进制位的编码. Mr ZHU 想知道在1秒内最多能发送多少位信息.</div>
<div style="margin: auto 0cm"><b><font size="4">例如</font></b></div>
<div>假设电缆允许我门发送2种不同的电平的信息(<i>k</i>=2), 我们用0 和 1表示. 如果电平每秒有20次变化 (<i>n</i>=20), 包含有4 个脉冲(<i>m</i>=4), 在每个包内有3 个连续的脉冲具有同一种电平(<i>l</i>=3), 这时我们不能发送这些包: 0000, 0001, 1000, 1111, 1110, 0111. 但是可以发送这些包: 0010, 0011, 0100, 0110, 0101, 1101, 1100, 1011, 1001 and 1010. 当一个要发送10个不同种类的包，我们对每个包进行log<sub>2</sub>10 位信息编码. 在一秒内可以发送20/4 = 5 个包, 也就是5*log<sub>2</sub>10 ~ 16.6096 位信息.</div></div>

# Input

<div class="content"><div style="text-indent: 18pt"> 有四个整数：</div>
<ul type="disc">
    <li>电平种类 <i>k</i> (2 &lt;= k &lt;= 10),</li>
    <li>脉冲的频率 <i>n</i> (1 &lt;= <i>n</i> &lt;= 1000),</li>
    <li>数据包的大小 <i>m</i> (1 &lt;= <i>m</i> &lt;= 100),</li>
    <li>在一个包中连续脉冲的数目<i>l</i>, 也就是说在这个范围内必须改变电平 (2 &lt;= <i>l</i> &lt;= <i>m</i>),</li>
</ul>
<div style="text-indent: 18pt">我们假设 <i>n</i>/<i>m</i> 是一个不超过10的整数.</div>
<div style="text-indent: 21pt"></div></div>

# Output

<div class="content"><div style="text-indent: 21pt">写入一个整数，为一秒内最大能发送数据包的位数，答案四舍五入取整</div>
<p><divre></divre>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 20 4 3<br/>
<br/>
<br/>
<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">16<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

