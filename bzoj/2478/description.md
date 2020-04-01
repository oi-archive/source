
# Description

<div class="content"><div>Tuple博士正在为<span>ACM（Advanced Commercial Merchandise）公司开发一个数据挖掘的软件。其中一个子程序是用来处理两个数组的，设两个数组分别为P和Q，均含N个元素，编号为0到N-1。数组P是一个带关键字的hash表，用来存放需要处理的元素，这些元素对应的数据可以通过数组Q找到。</span></div>
<div style="text-indent: 21pt">数组<span>P中每个元素的大小为Sp字节，数组Q中每个元素的大小为Sq字节。Tuple博士希望这个子程序的效率越高越好，因为它是整个软件的关键。但是Sp和Sq只有等到程序运行的时候才能知道，因此是不可能在编译时优化的。</span></div>
<div style="text-indent: 21pt">我们都知道最直接的寻址方式：</div>
<div style="text-indent: 21pt">·数组<span>P的第i个元素的地址Pofs(i)=Sp×i——(1)；</span></div>
<div style="text-indent: 21pt">·数组<span>Q的第i个元素的地址Qofs(i)=Sq×i——(2)。</span></div>
<div style="text-indent: 21pt">但是，乘法运算要比加减法慢得多。可喜的是，<span>Tuple博士成功地避免了使用乘法运算。在整个软件中，他总是用每个元素的地址Pofs(i)代替该元素的序号i。在计算与第i个元素相邻的元素地址时，只要用下面这两个简单的公式即可：</span></div>
<div style="text-indent: 21pt">Pofs(i+1)=Pofs(i)+Sp；</div>
<div style="text-indent: 21pt">Pofs(i-1)=Pofs(i)-Sp。</div>
<div style="text-indent: 21pt">因为<span>P和Q是一个整体，每当数组P中的元素被修改时，Q中元素也要作相应的变动。Qofs(i)可以用Pofs(i)直接求得：Qofs(i)=Pofs(i)/Sp×Sq——(3)。</span></div>
<div style="text-indent: 21pt">然而这个公式不仅要用到乘法，而且要用到除法。虽然仅仅是整数除法，但是速度还是很慢。经过研究，<span>Tuple博士发现可以用一个更快的公式代替上述公式：Qofs&#39;(i)=(Pofs(i)+Pofs(i)&lt;&lt;A)&gt;&gt;B——(4)。</span></div>
<div style="text-indent: 21pt">其中：<span>A和B是非负整数，“&lt;&lt;A”表示左移A位（相当于乘以2^A），“&gt;&gt;B”表示右移B位（相当于除以2^B）。</span></div>
<div style="text-indent: 21pt">这个公式的效率显然比公式<span>(3)高多了，不过不是总能找到A和B使之能和公式(3)产生一样的结果的。而且，这个公式可能会牺牲更多的内存。</span></div>
<div style="text-indent: 21pt">如果使用公式<span>(2)的话，存放数组Q只需要N×Sq就够了。Tuple博士发现，如果使用公式(4)的话，总能够找到一个K（K&gt;=N×Sq），用K字节存放数组Q并恰当地选择A和B，使得所有的元素都不重叠。</span></div>
<div style="text-indent: 21pt"><span style="color: blue">任务</span>：请你编写一个程序，找到所有可行的解当中<span>K最小的。如果有多组解的话，输出A最小的；如果还有多组解，输出B最小的。公式的运算过程中可能出现非常大的整数，请你<span style="color: red">注意</span>不要溢出，不过你不用担心Tuple博士的电脑会溢出。</span></div>
<div> </div></div>

# Input

<div class="content"><div style="text-indent: 21pt">输入文件中仅一行为三个整数<span>N，Sp，Sq（1&lt;=N&lt;=2^20，1&lt;=Sp&lt;=2^10，1&lt;=Sq&lt;=2^10）。</span></div>
<div> </div></div>

# Output

<div class="content"><div style="text-indent: 21pt">输出文件中仅一行为三个整数<span>K，A，B，相邻两个整数之间用一个空格隔开。</span></div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
20 3 5<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">119 0 0<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

