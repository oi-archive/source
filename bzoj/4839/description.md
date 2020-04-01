
# Description

<div class="content"><div>一个大写的单词的定义是一个单词的首字母为大写字母，之后的字母均为小写字母且至少要包含1个小写字母，例</div>
<div>如：Ab,Abc,Abd,Abcde均为大写的单词，而ab,A,ABc,AcB,AB均不是大写的单词。一个可缩略序列的定义为一个字</div>
<div>符串由至少两个大写的单词组成，且由恰好一个空格隔开（不能是两个或多个空格，也不能有标点符号。一个可缩</div>
<div>略序列的缩略操作的定义为首先取这个可缩略序列的所有的大写的单词的首字母首先组成一个字符串（中间不含空</div>
<div>格），然后是一个空格，接着是一个左括号，再接着是这个可缩略序列，最后紧接着是一个右括号。（细节详见输</div>
<div>入输出样例）</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入不超过1000行，每行至多120个字符，每行的字符仅由大小写字母，空格，逗号或点（英文中的句号）</div>
<div>没有前置或后置空格，无空行且输入至少有一行。</div>
<div></div></div>

# Output

<div class="content"><div>对于输入的每一行，输出对该行中所有的可缩略序列执行缩略操作后的字符串。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1：<br/>
This is ACM North Eastern European Regional Contest,<br/>
sponsored by International Business Machines.<br/>
The. Best. Contest. Ever.<br/>
A Great Opportunity for all contestants.<br/>
样例输入2：<br/>
ab Ab A Abc AB Abcd ABc Abcde AbC<br/>
样例输入3：<br/>
Oh  No  Extra Spaces.And,Punctuation Ruin Everything</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1：<br/>
This is ACM NEERC (North Eastern European Regional Contest),<br/>
sponsored by IBM (International Business Machines).<br/>
The. Best. Contest. Ever.<br/>
A GO (Great Opportunity) for all contestants.<br/>
样例输出2：<br/>
ab Ab A Abc AB Abcd ABc Abcde AbC<br/>
样例输出3：<br/>
Oh  No  ES (Extra Spaces).And,PRE (Punctuation Ruin Everything)</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

