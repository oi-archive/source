
# Description

<div class="content"><div>“哈佛结构”是指一台拥有多个分散内存用于记录指令与数据的计算机。这个术语起源于“哈佛马克1号”计算机。它由IBM于1944年制造，用纸带记录指令，用继电器来储存数据。</div>
<div>一些最新的单片机使用了“哈佛结构”（当然没有用纸带和继电器）。数据是由“内存库”来组织，每个“内存库”拥有相同数量的数据。每一个访问数据的指令都由2个数控制。一个数a（非0即1）。如果a为0，那么访问的是0号“内存库”。如果a为1则访问BSR（bank select register “内存库”选择寄存器）中选择的“内存库”。另一个数f表示访问该“内存库”的第f个变量。我们假设每一个指令花费相同的时间运行。另外还有一个可以设定BSR值的命令。</div>
<div>举例来说，假设有4个“内存库”，每个“内存库”有8个字节。为了访问位置5（0号“内存库”第5个变量），我们有两种方法。第一种，使用指令a=0，f=5。第二种，先将BSR的值设为0，然后使用指令a=1，f=5。第一种方法更快，因为它不需要花费时间设置BSR。</div>
<div>现在假设（还是刚才的“内存库”）我们要访问位置20（2号“内存库”第4个变量）。现在只有1种方法能够访问。将BSR的值设为2（除非BSR原来就是2），然后用指令a=1，f=4。</div>
<div>一个程序是一个操作的序列，每个操作是：</div>
<div>●一个变量访问操作，写作Vi，i是一个正整数。</div>
<div>●一个循环操作，写作 Rn &lt;program&gt; E，n是一个正整数，&lt;program&gt;是一个任意的程序。这个操作等价于依次执行n遍&lt;program&gt;。</div>
<div>你的工作是决定一个程序最小的运行时间。更确切的说，给出“内存库”的个数和大小，需要执行的程序，输出为了执行这个程序最小的指令数（包括数据访问指令和设定BSR的指令）。为了完成这个，你必须设定一个变量到“内存库”的映射，使得这个程序运行时间最短，并且输出这个时间（也就是程序运行的指令数）。开始的时候BSR的值为undefined，直到一条命令显式的设定了它的值。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>每组输入包含一个case，两行。第一行两个整数b和s，1≤b≤13代表“内存库”的个数，1≤s≤13代表每个“内存库”的大小（即能储存的变量数）。第二行是一个非空程序，最多有1000个元素（每个Rn，Vi，E都算1个元素）。</div>
<div>保证：</div>
<div>在循环Rn中，循环次数1≤n≤10^6。</div>
<div>在循环Rn &lt;program&gt; E中, &lt;program&gt;非空。</div>
<div>在数据访问Vi中，1≤i≤min(b*s,13)。</div>
<div>程序访问变量的次数不超过10^12次。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出运行该程序最少需要的指令数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2<br/>
V1 V2 V1 V1 V2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

