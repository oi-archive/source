
# Description

<div class="content"><p><font face="Times New Roman" size="3">考虑一个只包含小写拉丁字母的字符串s。我们定义s的一个子串t的“出 <br/>
现值”为t在s中的出现次数乘以t的长度。请你求出s的所有回文子串中的最 <br/>
大出现值。 <br/>
</font></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="3">输入只有一行，为一个只包含小写字母(a -z)的非空字符串s。 <br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font face="Times New Roman" size="3">输出一个整数，为逝查回文子串的最大出现值。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入l】 <br/>
abacaba <br/>
<br/>
【样例输入2] <br/>
www <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出l】 <br/>
7 <br/>
<br/>
【样例输出2] <br/>
4 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
一个串是回文的，当且仅当它从左到右读和从右到左读完全一样。 <br/><br/>
在第一个样例中，回文子串有7个：a，b，c，aba，aca，bacab，abacaba，其中： <br/><br/>
● a出现4次，其出现值为4：1：1=4 <br/><br/>
● b出现2次，其出现值为2：1：1=2 <br/><br/>
● c出现1次，其出现值为l：1：l=l <br/><br/>
● aba出现2次，其出现值为2：1：3=6 <br/><br/>
● aca出现1次，其出现值为1=1：3=3 <br/><br/>
●bacab出现1次，其出现值为1：1：5=5 <br/><br/>
● abacaba出现1次，其出现值为1：1：7=7 <br/><br/>
故最大回文子串出现值为7。 <br/><br/>
【数据规模与评分】 <br/><br/>
数据满足1≤字符串长度≤300000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

