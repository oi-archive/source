
# Description

<div class="content"><div>Freda发明了传呼机之后，rainbow进一步改进了传呼机发送信息所使用的信号。由于现在是数字、信息时代，rain</div>
<div>bow发明的信号用N个自然数表示。为了避免两个人的对话被大坏蛋VariantF偷听T_T，rainbow把对话分成A、B、C</div>
<div>三部分，分别用a、b、c三个密码加密。现在Freda接到了rainbow的信息，她的首要工作就是解密。Freda了解到，</div>
<div>这三部分的密码计算方式如下：</div>
<div>在1~N这N个数中，等概率地选取两个数l、r，如果l&gt;r，则交换l、r。把信号中的第l个数到第r个数取出来，构成一个数列P。</div>
<div>A部分对话的密码是数列P的xor和的数学期望值。</div>
<div>xor和就是数列P中各个数异或之后得到的数； </div>
<div>xor和的期望就是对于所有可能选取的l、r，所得到的数列的xor和的平均数。</div>
<div>B部分对话的密码是数列P的and和的期望，定义类似于xor和。</div>
<div>C部分对话的密码是数列P的or和的期望，定义类似于xor和。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数N。</div>
<div>第二行N个自然数，表示Freda接到的信号。</div>
<div>对于20%的数据，1&lt;=N&lt;=100。</div>
<div>对于40%的数据，1&lt;=N&lt;=1000。</div>
<div>对于另外30%的数据，N个数为0或1。</div>
<div>对于100%的数据，1&lt;=N&lt;=100000，N个自然数均不超过10^9。</div>
<div></div></div>

# Output

<div class="content"><div>一行三个实数，分别表示xor和、and和、or和的期望，</div>
<div>四舍五入保留3位小数，相邻两个实数之间用一个空格隔开。</div></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
2<br/>
4 5<br/>
<br/>
样例输入2<br/>
3<br/>
1 0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1<br/>
2.750 4.250 4.750<br/>
<br/>
样例输出2<br/>
0.667 0.222 0.889</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize9">Poetize9</a></p></div>

