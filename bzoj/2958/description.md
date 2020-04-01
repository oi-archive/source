
# Description

<div class="content"><p><span style="font-size: medium">　　给出一个长度为N由B、W、X三种字符组成的字符串S，你需要把每一个X染成B或W中的一个。<br/>
　　对于给出的K，问有多少种染色方式使得存在整数a,b,c,d使得:<br/>
　　1&lt;=a&lt;=b&lt;c&lt;=d&lt;=N<br/>
　　Sa,Sa+1,...,Sb均为B<br/>
　　Sc,Sc+1,...,Sd均为W<br/>
　　其中b=a+K-1,d=c+K-1<br/>
　　由于方法可能很多，因此只需要输出最后的答案对109+7取模的结果。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　第一行两个正整数N,K<br/>
　　第二行一个长度为N的字符串S<br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">　　一行一个整数表示答案%(109+7)。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
5 2<br/>
XXXXX<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
4<br/>
数据约定<br/>
　　对于20%的数据，N&lt;=20<br/>
　　对于50%的数据，N&lt;=2000<br/>
　　对于100%的数据，1&lt;=N&lt;=10^6，1&lt;=K&lt;=10^6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=　中国国家队清华集训 2012-2013 第一天
">　中国国家队清华集训 2012-2013 第一天<br/>
</a></p></div>

