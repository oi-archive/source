
# Description

<div class="content"><div>Diffie-Hellman密钥交换协议是一种简单有效的密钥交换方法。它可以让通讯双方在没有事先约定密钥（密码）的情况下</div>
<div>通过不安全的信道（可能被窃听）建立一个安全的密钥K，用于加密之后的通讯内容。</div>
<div>假定通讯双方名为Alice和Bob，协议的工作过程描述如下（其中mod表示取模运算）：</div>
<div>1．协议规定一个固定的质数P，以及模P的一个原根g。P和g的数值都是公开的，无需保密。</div>
<div>2．Alice生成一个随机数a，并计算A=g^a mod P，将A通过不安全信道发送给Bob。</div>
<div>3．Bob生成一个随机数b，并计算B=g^b mod P，将B通过不安全信道发送给Alice。</div>
<div>4．Bob根据收到的A计算出K=A^b mod P，而Alice根据收到的B计算出K=B^a mod P。</div>
<div>5．双方得到了相同的K，即g^(a*b) mod P。K可以用于之后通讯的加密密钥。</div>
<div>可见，这个过程中可能被窃听的只有A、B，而a、b、K是保密的。并且根据A、B、P、g这4个数，不能轻易计算出</div>
<div>K，因此K可以作为一个安全的密钥。</div>
<div>当然安全是相对的，该协议的安全性取决于数值的大小，通常a、b、P都选取数百位以上的大整数以避免被破解。然而如</div>
<div>果Alice和Bob编程时偷懒，为了避免实现大数运算，选择的数值都小于2^31，那么破解他们的密钥就比较容易了。</div></div>

# Input

<div class="content"><div>输入文件第一行包含两个空格分开的正整数g和P。</div>
<div>第二行为一个正整数n，表示Alice和Bob共进行了n次连接（即运行了n次协议）。</div>
<div>接下来n行，每行包含两个空格分开的正整数A和B，表示某次连接中，被窃听的A、B数值。</div>
<div>2≤A，B&lt;P&lt;231，2≤g&lt;20， n&lt;=20 </div></div>

# Output

<div class="content"><div>输出包含n行，每行1个正整数K，为每次连接你破解得到的密钥。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 31<br/>
3<br/>
27 16<br/>
21 3<br/>
9 26</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
21<br/>
25</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Amphetamine整理题面">鸣谢Amphetamine整理题面</a></p></div>

