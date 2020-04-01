
# Description

<div class="content"><p><font face="Times New Roman" size="3">每一个由字母a和b组成的序列（或是空序列），称为ab-word。如果X=[x1,..,xn]是一个ab-word并且有i,j是整数（1&lt;=i&lt;=j&lt;=n），那么X[i..j]表示由字母xi,..,xj组成的X的字符串。如果一个ab-word X=[x1,..xn] 中，字母a的个数等于字母b的个数，并且对于任何i=1,...,n，字符串X[1,i]中，字母a 与b至少都个数相等，那么，我们称这个ab-word X=[x1,..xn] 为好的。 <br/>
现在，我们给出两个好的ab-words之间类似的归纳定义。 <br/>
每两个空的ab-words（字符串内无字母）是相似的 <br/>
两个非空的好ab-words， X=[x1,...,xn] 和Y=[y1,..,ym] 是相似的，如果他们的长度相等(n=m)，并且以下的条件有一个满足： <br/>
1、 x1=y1, xn=yn 和X[2..n-1] 和Y[2..n-1] 是相似的 ab-words并且他们都是好的 <br/>
2、 存在i（1&lt;=i&lt;=n），使X[1..i]和 X[i+1..n]是好的ab-words，并且 <br/>
a、Y[1..i], Y[i+1..n]是好的ab-words，X[1..i]与Y[1..i]相似，X[i+1..n] 与 Y[i+1..n]相似，或者 <br/>
b、Y[1..n-i], Y[n-i+1..n]是好的ab-words ，X[1..i] 与 Y[n-i+1..n] 相似X[i+1..n] 与Y[1..n-i]相似. <br/>
一个好的ab-words 的非空集合s的多样性的水平是ab-words的最大个数，他满足：s中任意一对w1和w2，w1不相似于w2 <br/>
</font></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="3">写出以下一个程序： <br/>
读出元素s； <br/>
算出集合s的多样性的水平； <br/>
</font></p>
<p><font face="Times New Roman" size="3">在输入文件的首行有集合S（1&lt;=n&lt;=1000）的元素个数；在接下来的n行里是集合S的元素，诸如ab-words（一行一个单词）；每一个ab-word的首字母是每行的首记号。字符串中两个连续字母之间没有空隙；每一个ab-word的长度是[1..200]中的一个整数。</font></p></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">首单行应该记下一个整数-S多样性的等级。 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
<br/>
3<br/>
aabaabbbab<br/>
abababaabb<br/>
abaaabbabb<br/>
<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

