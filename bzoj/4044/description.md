
# Description

<div class="content"><div>Viruses are usually bad for your health. How about fighting them with... other viruses? In </div>
<div>this problem, you need to find out how to synthesize such good viruses. </div>
<div>We have prepared for you a set of strings of the letters A, G, T and C. They correspond to the </div>
<div>DNA nucleotide sequences of viruses that we want to svnthesize, using the following operations: </div>
<div>* Adding a nucleotide either to the beginning or the end of the existing sequence </div>
<div>* Replicating the sequence, reversing the copied piece, and gluing it either to the beginmng or </div>
<div>to the end of the original (so that e.g., AGTC can become AGTCCTGA or CTGAAGTC). </div>
<div>We&#39;re concerned about efficiency, since we have very many such sequences, some of them verv </div>
<div>long. Find a wav to svnthesize them in a mmimum number of operations. </div>
<div>你要用ATGC四个字母用两种操作拼出给定的串： </div>
<div>1.将其中一个字符放在已有串开头或者结尾 </div>
<div>2.将已有串复制，然后reverse，再接在已有串的头部或者尾部 </div>
<div>一开始已有串为空。求最少操作次数。 </div>
<div>len&lt;=100000 </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains the number of test cases T. The descriptions of the test cases </div>
<div>follow: </div>
<div>Each test case consists of a single line containing a non-empty string. The string uses only </div>
<div>the capital letters A, C, G and T and is not longer than 100 000 characters. </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>For each test case, output a single line containing the minimum total number of operations </div>
<div>
<div>necessary to construct the given sequence.</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
AAAA<br/>
AGCTTGCA<br/>
AAGGGGAAGGGGAA<br/>
AAACAGTCCTGACAAAAAAAAAAAAC</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
8<br/>
6<br/>
18</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

