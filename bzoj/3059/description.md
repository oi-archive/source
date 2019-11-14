
# Description

<div class="content"><p><span style="font-size: medium">给出一个长度为N的由小写字母’a’~’z’和’*’组成的字符串A，一个长度为M的仅由小写字母’a’~’z’组成的字符串B。一个’*’可以匹配任意多个字符（包括0个）。求在B的所有循环同构串中，有多少个能够与A匹配。<br/>
循环同构串：就是把B的前k个字母(0&lt;=k&lt;M)移到结尾所得到的M个字符串。例如abc的循环同构串有abc、bca和cab。<br/>
A与B匹配：若除了A中的’*’号可以匹配B中的任意多个字符外，其余字符一一对应，则称A与B匹配。例如a*b*c与aadbc是匹配的，其中第一个*对应ad，第二个*对应空串。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行为字符串A。<br/>
第二行为字符串B。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
输出在B的所有循环同构串中，有多少个能够与A匹配。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
aaaa<br/>
aaaa<br/>
<br/>
样例输入2<br/>
a*a<br/>
aaaaaa<br/>
<br/>
样例输入3<br/>
*a*b*c*<br/>
abacabadabacaba<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1<br/>
4<br/>
<br/>
样例输出2<br/>
6<br/>
<br/>
样例输出3<br/>
15<br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p><br/><br/>
对于100% 的测试点，1&lt;=N&lt;=100，1≤M≤100000。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize12">Poetize12</a></p></div>

