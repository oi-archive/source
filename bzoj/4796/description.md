
# Description

<div class="content"><div>Goran正在从他的膝盖手术中恢复，并正在试验用于存储的智能卡加密密钥。在这个问题中，一个密钥是指一个长</div>
<div>度为3n的二进制序列，其中n是正整数。序列的每一位从左往右依次被编号为1到3n。一个密钥的权值是指相邻位不</div>
<div>同的位置个数再加上1。比如：“000”的权值是1，“011010100”的权值是7。他发现他可以发送小型脉冲电流来</div>
<div>修改智能卡的电路，从而修改密钥。确切地说，他可以不断进行下面的操作：选择任意两个相邻的位，然后同时取</div>
<div>反它们。比如他可以通过一次操作把“000”修改为“110”。给定一个长度为3n的密钥，请操作不超过n次，将其</div>
<div>修改为一个权值不少于2n的密钥。你可以认为合法解必然存在。</div></div>

# Input

<div class="content"><div>包含一行一个01序列，表示初始密钥，保证长度一定为3n，且1&lt;=n&lt;=100000。</div></div>

# Output

<div class="content"><div>第一行包含一个整数m，表示操作的次数，你需要保证0&lt;=m&lt;=n。</div>
<div>第二行包含m个正整数a_1,a_2,...,a_m(1&lt;=a_i&lt;n)，依次表示每次翻转第a_i和第(a_i)+1位。</div>
<div>如果初始密钥的权值已经不小于2n，你可以仅输出一行一个整数0。</div></div>

# Sample Input

<div class="content"><span class="sampledata">111001000111</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3 9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

