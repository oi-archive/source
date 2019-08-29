<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Freda和Rainbow正在研究外星人的DNA。外星人的DNA是一个由&#39;A&#39;、&#39;C&#39;、&#39;G&#39;、&#39;T&#39;组成的序列，并且在发生着突变。每次突变的过程都是一样的：DNA序列中连续的一段被激活，这一段中的每个碱基自我复制，错位排序后紧接在这段被激活的序列后面。错位排序指的是：首先把这段被激活的序列的偶数位置上的碱基取出，按照原顺序接在序列后面；再把奇数位置上的碱基取出，按照原顺序接在序列后面。例如被激活的那段序列为s1s2s3……s11，那么这次突变后，s2s4s6s8s10s1s3s5s7s9s11会被接在这段序列后面。<br/>
　　例如，起初外星人的DNA序列为&#34;ACTGG&#34;，序列中[2,4]这段（&#34;CTG&#34;）发生突变，那么突变后DNA序列会变为&#34;ACTGTCGG&#34;。<br/>
　　Rainbow找到了一个外星人的DNA序列并把它记了下来，他问Freda经过n次突变后DNA序列的前k个碱基是什么，但是Freda觉得这个序列太长了有木有T_T！于是请你写个程序帮忙计算一下……</div>
# 输入格式

<div class="pdcont">　　第一行一个由&#39;A&#39;、&#39;C&#39;、&#39;G&#39;、&#39;T&#39;组成的字符串，表示外星人的初始DNA序列。<br/>
　　第二行一个整数k。<br/>
　　第三行一个整数n。<br/>
　　接下n行每行两个整数l、r，表示[l,r]这段发生一次突变。</div>
# 输出格式

<div class="pdcont">　　输出一行，表示n次突变过后DNA序列的前k个碱基。</div>
# 样例输入

<div class="pddata">ACGTACGT<br/>
16<br/>
2<br/>
1 2<br/>
2 8</div>
# 样例输出

<div class="pddata">ACCAGTACCGACATCG</div>
# 数据规模和约定

<div class="pdcont">　　0&lt;=n&lt;=5000，1&lt;=k&lt;=3000000，1&lt;=l&lt;=r&lt;=10^9，字符串长度不超过3000000。</div>

</div>