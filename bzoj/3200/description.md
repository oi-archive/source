
# Description

<div class="content"><div align="left"><span style="font-size: medium">Tar的第一项家庭作业是一大堆中缀表达式。他要把这些表达式写成后缀形式之后交给老师。Tar不会做这个作业，所以他找同学要了一份答案来抄。Tar的老师是一个近视眼，分不清连续一串的相同字符和一个字符的区别。Tar今天感觉非常累，于是他决定偷懒，少抄几个字糊弄一下老师。请你帮他完成这个任务。</span></div>
<div align="left"><span style="font-size: medium">我们来做几个必要的定义。</span></div>
<div align="left"><span style="font-size: medium"><b>表达式</b>由a-z的小写字母和一些二元运算符构成，运算符可以是a-z以外的任意可见字符。</span></div>
<div align="left"><span style="font-size: medium"><b>中缀表达式</b>就是一般情况下使用的表达式，比如((a+h)/b)*(c+d)，将运算符置于两个运算数中间（注意运算数本身可以是变量或者一个表达式，因此这是一个递归定义）。一般可以利用括号指定运算顺序。</span></div>
<div align="left"><span style="font-size: medium"><b>后缀表达式</b>的特点是把运算符置于两个运算数之后，比如和上式等价的后缀表达式是ah+b/cd+*。后缀表达式不需要括号，严格从左到右进行计算。</span></div>
<div align="left"><span style="font-size: medium">另外我们假定这个表达式系统内，<b>相同的运算符号</b>满足结合律和交换律，具体来说：</span></div>
<div align="left"><span style="font-size: medium"><b>结合律</b>：A*(B*C) = (A*B)*C 写成后缀时，ABC** = AB*C*。</span></div>
<div align="left"><span style="font-size: medium"><b>交换律</b>：A*B = B*A 写成后缀时，AB* = BA*</span></div></div>

# Input

<div class="content"><div align="left"><span style="font-size: medium">一行字符，表示Tar同学的答案。以后缀表达式的形式给出。</span></div></div>

# Output

<div class="content"><div align="left"><span style="font-size: medium">输出一个数字，表示Tar能够蒙混过关至少要写几个字。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
af+b*cd**<br/>
<br/>
样例输入2<br/>
xy*x*y*x*y*</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1<br/>
7<br/>
<br/>
样例输出2<br/>
3</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">样例解释2<br/><br/>
xy*x*y*x*y* = xxxyyy***** = (xy*) 长度为3 <br/><br/>
100%的数据满足：输入长度&lt;=2500</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

