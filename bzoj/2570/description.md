
# Description

<div class="content"><div style="text-indent: 27pt"><span style="font-size: medium">考古学发现，几千年前古梅文明时期的数学非常的发达，他们懂得多位数的加法和乘法，其表达式和运算规则等都与现在<b><u>通常所用</u></b>的方式完全相同（如整数是十进制，左边是高位，最高位不能为零；表达式为中缀运算，先乘后加等），唯一的区别是其符号的写法与现在不同。有充分的证据表明，古梅文明的数学文字一共有13个符号，与 0,1,2,3,4,5,6,7,8,9,+,*,= 这13个数字和符号（称为现代算符）一一对应。为了便于标记，我们用13个小写英文字母a,b,…m代替这些符号（称为古梅算符）。但是，还没有人知道这些古梅算符和现代算符之间的具体对应关系。</span></div>
<div style="text-indent: 27pt"><span style="font-size: medium">在一个石壁上，考古学家发现了一组用古梅算符表示的等式，根据推断，每行有且仅有一个等号，等号左右两边为运算表达式（只含有数字和符号），并且等号两边的计算结果相等。</span></div>
<div style="text-indent: 27pt"><span style="font-size: medium">假设这组等式是成立的，请编程序破译古梅算符和现代算符之间的对应关系。</span></div>
<div style="text-indent: 27pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>输入文件的第一行为等式的个数N（1&lt;=N&lt;=1000），以下N行每行为一个等式。</span></p>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>每个等式的长度为5个字符到11个字符。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>如果不存在对应关系能够满足这组等式，输出“noway”和一个换行/回车符。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>如果有对应关系能够满足这组等式，输出所有能够确定的古梅算符和现代算符的对应关系。每一行有两个字符，其中第一个字符是古梅算符，第二个字符是对应的现代算符。输出按照字典顺序排序。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
abcdec<br/>
cdefe<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">a6<br/>
b*<br/>
d=<br/>
f+<br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium">[样例说明]</span></div><br/>
<div style="text-indent: 24pt"><span style="font-size: medium">在上例中，可能对应的现代表达式为{6*2=12，2=1+1}，{6*4=24，4=2+2}，{6*8=48，8=4+4}。可见，能够确定的对应关系只有a对应6，b对应*，d对应=，f对应+，应该输出；而{c,e}虽然能够找到对应的现代算符使得等式成立，但没有唯一的对应关系，不能输出。其他古梅算符{g,h…m}完全不能确定，也不能输出。</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

