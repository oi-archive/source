
# Description

<div class="content"><div>给出一个长度为N由B、W、X三种字符组成的字符串S，你需要把每一个X染成B或W中的一个。</div>
<div>对于给出的K，问有多少种染色方式使得存在整数a,b,c,d使得:</div>
<div>1&lt;=a&lt;=b&lt;c&lt;=d&lt;=N</div>
<div>Sa,Sa+1,...,Sb均为B</div>
<div>Sc,Sc+1,...,Sd均为W</div>
<div>其中b=a+K-1,d=c+K-1</div>
<div>由于方法可能很多，因此只需要输出最后的答案对10^9+7取模的结果。</div></div>

# Input

<div class="content"><div>第一行两个正整数N,K</div>
<div>第二行一个长度为N的字符串S</div>
<div>1&lt;=N&lt;=10^6，1&lt;=K&lt;=10^6</div></div>

# Output

<div class="content"><p>一行一个整数表示答案%(10^9+7)。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
XXXXX</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

