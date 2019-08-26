
# Description

<div class="content"><div>给定两个只含大写字母A和B的字符串x和y，我们定义一个有序字符串对(a,b)是「优秀的」，当且仅当它满足以下条件：</div>
<div>a和b只包含字符0和1；</div>
<div>1&lt;=|a|,|b|&lt;=n，其中n是给定的常数；</div>
<div>如果我们将x与y中的字符A用a替换，字符B用b替换，则替换后的x和y相等。</div>
<div></div>
<div>定义f(x,y)为优秀的有序对(a,b)的个数。</div>
<div>现在你有两个字符串c和d，它们只包含字符A，B和问号。你需要求出Sigma(f(x,y))，</div>
<div>其中(x,y)是分别将c和d中的所有问号任意替换为A或B得到的所有不同的字符串对。</div>
<div>答案模10^9+7。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>三行，依次为字符串c，d和常数n，它们的意义如上所述。</div>
<div>1&lt;=|c|,|d|&lt;=3*10^5，1&lt;=n&lt;=10^10</div>
<div>
<div></div>
</div>
<div></div></div>

# Output

<div class="content"><div>输出仅一行，表示Sigma(f(x,y))在模10^9+7下的取值。</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">```<br/>
A?<br/>
?<br/>
3<br/>
```</span></div>

# Sample Output

<div class="content"><span class="sampledata">```<br/>
2<br/>
```<br/>
<br/>
对于样例数据，有4种可能的(x,y)：<br/>
若(x,y)=(AA,A)，则f(x,y)=0；<br/>
若(x,y)=(AB,A)，则f(x,y)=0；<br/>
若(x,y)=(AA,B)，则f(x,y)=2，对应的(a,b)分别为(1,11)和(0,00)；<br/>
若(x,y)=(AB,B)，则f(x,y)=0。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

