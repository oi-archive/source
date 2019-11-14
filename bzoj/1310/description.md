
# Description

<div class="content"><p>给定某个字符串,长度为N,它只由&#34;I&#34;和&#34;X&#34;组成.并且有不超过K对&#34;I&#34;与&#34;X&#34;是相邻的. 例如对于字符串&#34;IXXIIXXX&#34;,它就是XI-8-3,即长度为8,&#34;I&#34;与&#34;X&#34;相邻的对数不超过3. 当然你要说它是XI-8-4也行,甚至于XI-8-K(K&gt;=3).值得注意的是:由于字符串的首尾不 固定,&#34;IXXIIXXX&#34;也可以看成&#34;XXXIIXXI&#34;,但由于每个字符串只有一个序号,因而我们对 这种由于颠倒首尾所产生的字符串,取两者之中字典序较小的那个为基准,当然如果一个 字符串它是回文串的话,那就无所谓了. 现在给定N,K的值,我们可以找到许多满足条件的字符串,现在希望能找出排在第i个的是 哪个字符串,例如N=3,K=2,i=5时,我们可以按字典序找出如下的字符串:&#34;III&#34;, &#34;IIX&#34;, &#34;IXI&#34;, &#34;IXX&#34;, &#34;XIX&#34;,&#34;XXX&#34;.那么排在第5个位置的为&#34;XIX&#34;</p></div>

# Input

<div class="content"><p>每行给定N,K,i,含义如上所述 规定:0&lt;=K</p></div>

# Output

<div class="content"><p>希望你能找出相应的字符串,如果找不出来就输出&#34;NO SUCH STONE&#34;  input data1: 3 2 5  input data2: 3 2 7</p></div>

# Sample Input

<div class="content"><span class="sampledata">output data1:<br/>
XIX<br/>
<br/>
output data2:<br/>
NO SUCH STONE</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>0 &lt;= k &lt; n&lt;= 60  0 &lt; i &lt; 10^18</p><br/>
<p>题解:<a href="/JudgeOnline/upload/201603/dsyoj1310《Magical stones》解题报告.rar">JudgeOnline/upload/201603/dsyoj1310《Magical stones》解题报告.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

