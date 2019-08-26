
# Description

<div class="content"><div>IOI2015将要在哈萨克斯坦举行。哈萨克斯坦的“哈萨克”是用字母的“QAZAQ”拼写的。这个“QAZQA”是回文—</div>
<div>—知晓这一点的JOI君出于对回文的喜爱，准备用眼前的字符串制作一个回文。JOI君找到了一个长为N的字符串S=(</div>
<div>S1,S2,...,SN)，每个字符可以用1...C之间的一个整数来表示。从这个字符串第i个位置到第j个位置的字符串(Si,</div>
<div>Si+1,...,Sj)称作子串(i,j)。如果子串(i,j)翻转后和原来相等，即(Si,Si+1,...,Sj)=(Sj,Sj-1,...,Si)，则称</div>
<div>子串(i,j)是回文的。JOI君进行如下操作来制造回文：</div>
<div>1.        首先，选择S的一个子串。不妨设选择的子串为T。</div>
<div>2.        将子串T按照升序排序，得到T’</div>
<div>3.        在S中，用T’替换T，得到S’。我们可以这样描述这三项操作：JOI君选择一个子串(i,j)，将Si,Si+1,</div>
<div>...,Sj按升序排序得到T’i,T’i+1,...,T’j，最终得到S’=(S1,S2,...,Si-1,T’i,T’i+1,...,T’j,Sj+1,...,SN)</div>
<div>4.        在这之后，寻找S’中的回文子串</div>
<div>JOI进行如上操作后，想要得到最长的回文子串</div>
<div>现在JOI君将字符串S交给了你，请你输出JOI君进行如上操作后能得到的最长回文子串的长度。</div></div>

# Input

<div class="content"><div>第一行两个空格分隔的正整数N和C，分别表示字符串的长度和字符集大小</div>
<div>接下来N行，第i行一个正整数Si，表示字符串S中第i个位置的字符</div>
<div>
<div>1&lt;=N&lt;=3000</div>
<div>1&lt;=C&lt;=3000</div>
<div>1&lt;=Si&lt;=C</div>
</div>
<div></div></div>

# Output

<div class="content"><p>输出一行一个正整数，表示JOI君进行操作后能得到的最长回文子串的长度。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">12 26<br/>
26<br/>
17<br/>
17<br/>
17<br/>
1<br/>
26<br/>
1<br/>
17<br/>
19<br/>
20<br/>
1<br/>
14<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
样例输入中，N=12,C=26,S=(26,17,17,17,1,26,1,17,19,20,1,14)。JOI君可以选择子串(4,8)，将其按照升序排列<br/>
，得到S’=(26,17,17,1,1,17,17,26,19,20,1,14)，这样子串(1,8)就是回文了。这个回文长度为8，是最长可能得<br/>
到的回文子串。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2014~2015 春季training合宿 竞技3 By PoPoQQQ">JOI 2014~2015 春季training合宿 竞技3 By PoPoQQQ</a></p></div>

