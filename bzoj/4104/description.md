
# Description

<div class="content"><p> 对于一个长度为N的字符串，我们在字符串的末尾添加一个特殊的字符&#34;.&#34;。之后将字符串视为一个环，从位置1,2,3,...,N+1为起点读出N+1个字符，就能得到N+1个字符串。</p>
<div></div>
<div>比如对于字符串“ABCAAA”，我们可以得到这N+1个串：</div>
<div></div>
<div>ABCAAA.</div>
<div></div>
<div>BCAAA.A</div>
<div></div>
<div>CAAA.AB</div>
<div></div>
<div>AAA.ABC</div>
<div></div>
<div>AA.ABCA</div>
<div></div>
<div>A.ABCAA</div>
<div></div>
<div>.ABCAAA</div>
<div></div>
<div>接着我们对得到的这N+1个串按字典序从小到大进行排序（注意特殊字符“.”的字典序小于任何其他的字符）结果如下：</div>
<div></div>
<div>.ABCAAA</div>
<div></div>
<div>A.ABCAA</div>
<div></div>
<div>AA.ABCA</div>
<div></div>
<div>AAA.ABC</div>
<div></div>
<div>ABCAAA.</div>
<div></div>
<div>BCAAA.A</div>
<div></div>
<div>CAAA.AB</div>
<div></div>
<div>最后，将排序好的N+1个串的最后一个字符取出，按照顺序排成一个新的字符串，也就是上面这个表的最后一列，就是加密后的密文“AAAC.AB”。</div>
<div></div>
<div>请通过加密后的密文求出加密前的字符串。</div>
<div></div></div>

# Input

<div class="content"><div>第一行有两个整数N,M，分别表示加密前的字符串长度和字符集大小，其中字符用整数1,2,3,...,M编号，添加的特殊字符“.&#34;用0编号。</div>
<div></div>
<div>第二行为N+1个整数，表示加密后的字符串。</div>
<div></div></div>

# Output

<div class="content"><p>输出仅一行，包含N个整数，用空格隔开，依次表示加密前字符串中每个字符的编号。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 1 1 3 0 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2 3 1 1 1</span></div>

# Hint

<div class="content"><p></p><p> #i (i=1~4)    N=5*(i+1) M&lt;=3</p><br/>
<div></div><br/>
<div>#5~6    N,M&lt;=50 字符串中字符互不相同</div><br/>
<div></div><br/>
<div>#7~8    N,M&lt;=1000 字符串中字符互不相同</div><br/>
<div></div><br/>
<div>#9~12    N,M&lt;=1000</div><br/>
<div></div><br/>
<div>#13~#20    N,M&lt;=200000</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

