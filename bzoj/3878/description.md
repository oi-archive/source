
# Description

<div class="content"><p> 【故事背景】</p>
<div>JYY有个奇怪的计算器，有一天这个计算器坏了，JYY希望你能帮助他写</div>
<div>一个程序来模拟这个计算器的运算。</div>
<div>【问题描述】</div>
<div>JYY的计算器可以执行N条预设好的指令。每次JYY向计算器输入一个正</div>
<div>整数X，计算器就会以X作为初始值，接着依次执行预设的N条指令，最后把</div>
<div>最终得出的结果返回给JYY。</div>
<div>每一条指令可以是以下四种指令之一：（这里a表示一个正整数。）</div>
<div>1、+a：表示将当前的结果加上a；</div>
<div>2、-a：表示将当前的结果减去a；</div>
<div>3、*a：表示将当前的结果乘以a；</div>
<div>4、@a：表示将当前的结果加上a*X（X是一开始JYY输入的数）。</div>
<div>计算器用于记录运算结果的变量的存储范围是有限的，所以每次运算结束之</div>
<div>后会有计算结果溢出的问题。</div>
<div>JYY的计算器中，存储每计算结果的变量只能存储L到R之间的正整数，</div>
<div>如果一次指令执行过后，计算结果超过了R，那么计算器就会自动把结果变成R，然后再以R作为当前结果继续进行之后的计算。同理，如果运算结果小于L，计算器也会把结果变成L，再接着计算。</div>
<div>比如，假设计算器可以存储1到6之间的值，如果当前的计算结果是2，那</div>
<div>么在执行+5操作之后，存储结果的变量中的值将会是6。虽然2+5的实际结</div>
<div>果是7，但是由于7超过了存储范围的上界，所以结果就被自动更正成了上界的大小，也就是6。</div>
<div>JYY一共想在计算器上输入Q个值，他想知道这Q个值输入计算器之后，</div>
<div>分别会得到什么结果呢？</div>
<div></div>
<div></div></div>

# Input

<div class="content"><p>输入文件的第一行包含三个正整数，N，L和R；</p>
<div>
<div>第接下来N行，每行一个指令，每个指令如题述，由一个字符和一个正整</div>
<div>数组成，字符和正整数中间有一个空格隔开；</div>
<div>第N+2行包含一个整数Q，表示JYY希望输入的数的数量；</div>
<div>第接下来Q行每行一个正整数，第k个正整数Xk表示JYY在第k次输入的</div>
<div>整数。</div>
<div></div>
</div></div>

# Output

<div class="content"><p>输出Q行每行一个正整数，第k行的整数表示输入Xk后，依次经过N个指</p>
<div>
<div>令进行计算所得到的结果。</div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 1 6<br/>
+ 5<br/>
- 3<br/>
* 2<br/>
- 7<br/>
@ 2<br/>
3<br/>
2<br/>
1<br/>
5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
3<br/>
6</span></div>

# Hint

<div class="content"><p></p><p> 【样例说明】</p><br/>
<div>当JYY输入2时，计算器会进行5次运算，每一次运算之后得到的结果分</div><br/>
<div>别是6（实际计算结果为7但是超过了上界），3，6，1（实际结果为-1但是低于了下界）和5（由于一开始输入的是2，所以这一次计算为1+2×2）。</div><br/>
<div></div><br/>
<div>1&lt;=N,Q&lt;=10^5,1&lt;=L&lt;=Xk&lt;=R&lt;=10^9,1&lt;=a&lt;=10^9</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round2 By 佚名上传">Round2 By 佚名上传</a></p></div>

