
# Description

<div class="content"><div></div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">一种非对称加密算法的密钥生成过程如下：</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">1. 任选两个不同的质数 p ，q</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">2. 计算 N=pq , r=(p-1)(q-1)</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">3. 选取小于r ，且与 r 互质的整数 e </span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">4. 计算整数 d ，使得 ed≡1 mod r</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">5. 二元组 (N,e) 称为公钥，二元组 (N,d) 称为私钥</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">当需要加密消息 n 时（假设 n 是一个小于 N 整数，因为任何格式的消息都可转为整数表示），使用公钥 (N,e)，按照</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">n^e≡c mod N</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">运算，可得到密文 c 。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">对密文 c 解密时，用私钥 (N,d) ，按照</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">c^d≡n mod N</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">运算，可得到原文 n 。算法正确性证明省略。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">由于用公钥加密的密文仅能用对应的私钥解密，而不能用公钥解密，因此称为非对称加密算法。通常情况下，公钥由消息的接收方公开，而私钥由消息的接收方自己持有。这样任何发送消息的人都可以用公钥对消息加密，而只有消息的接收方自己能够解密消息。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">现在，你的任务是寻找一种可行的方法来破解这种加密算法，即根据公钥破解出私钥，并据此解密密文。</span></div>
<div></div></div>

# Input

<div class="content"><p>输入文件内容只有一行，为空格分隔的j个正整数e,N,c。N&lt;=2^62,c&lt;N</p>
<div></div></div>

# Output

<div class="content"><p>输出文件内容只有一行，为空格分隔的k个整数d,n。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 187 45 </span></div>

# Sample Output

<div class="content"><span class="sampledata">107 12<br/>
//样例中 p = 11, q = 17</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

