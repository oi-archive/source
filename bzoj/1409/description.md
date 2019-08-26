
# Description

<div class="content"><pre class="line mt-10 q-content" style="white-space: pre-wrap; word-wrap: break-word; font-size: 14px; line-height: 23px;">Rivest是密码学专家。近日他正在研究一种数列E = {E[1],E[2],……,E[n]}，<br/>且E[1] = E[2] = p（p为一个质数），E[i] = E[i-2]*E[i-1] （若2&lt;i&lt;=n）。<br/></pre>
<div style="font-family: Arial; font-size: 14px; line-height: 23px;">例如{2,2,4,8,32,256,8192,……}就是p = 2的数列。在此基础上他又设计了一种加密算法，该算法可以通过一个密钥q (q &lt; p)将一个正整数n加密成另外一个正整数d，计算公式为：d = E[n] mod q。现在Rivest想对一组数据进行加密，但他对程序设计不太感兴趣，请你帮助他设计一个数据加密程序。</div></div>

# Input

<div class="content"><p>第一行读入m，p。其中m表示数据个数，p用来生成数列E。 以下有m行，每行有2个整数n，q。n为待加密数据，q为密钥。 数据范围:  0 &lt; p n&lt; 2^31 0 &lt; q &lt; p 0 &lt; m &lt;= 5000。</p></div>

# Output

<div class="content"><p>将加密后的数据按顺序输出到文件 第i行输出第i个加密后的数据。  输入样例1 2 7 4 5 4 6  输入样例2 4 7 2 4 7 1 6 5 9 3</p></div>

# Sample Input

<div class="content"><span class="sampledata">输入样例1 <br/>
2 7 <br/>
4 5 <br/>
4 6 <br/>
输入样例2 <br/>
4 7 <br/>
2 4 <br/>
7 1 <br/>
6 5 <br/>
9 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">输出样例1<br/>
3<br/>
1<br/>
<br/>
输出样例2<br/>
3<br/>
0<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

