
# Description

<div class="content"><div>给定一个r行c列的在屏幕上的“虚拟键盘”，我们需要通过“上，下，左，右，选择”5个控制键来移动屏幕上的光标来打印文本。一开始，光标在键盘的左上角，每次按方向键，光标总是跳到下一个在该方向上与当前位置不同的字符，若不存在则不移动。每次按选择键，则将光标所在位置的字符打印出来。</div>
<div>现在求打印给定文本（要在结尾打印换行符）的最少按键次数。</div>
<div></div></div>

# Input

<div class="content"><p>第一行输入r,c(1≤r,c≤50)</p>
<div>接下来给出一个r*c的键盘，包括大写字母，数字，横线以及星号（星号代表Enter换行）</div>
<div>最后一行是要打印的文本串s，s的长度不超过10000.</div></div>

# Output

<div class="content"><p>输出打印文本（包括结尾换行符）的最少按键次数。保证一定有解。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 19<br/>
ABCDEFGHIJKLMNOPQZY<br/>
X*****************Y<br/>
AZAZ<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">19</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><br/>
<p></p><br/>
<p></p><br/>
<p>附其余三个样例</p><br/>
<p>Sample Input 1</p><br/>
<p>4 7</p><br/>
<p>ABCDEFG</p><br/>
<p>HIJKLMN</p><br/>
<p>OPQRSTU</p><br/>
<p>VWXYZ**</p><br/>
<p>CONTEST</p><br/>
<p>Sample Output 1</p><br/>
<p>30</p><br/>
<p></p><br/>
<p>Sample Input 2</p><br/>
<p>5 20</p><br/>
<p>12233445566778899000</p><br/>
<p>QQWWEERRTTYYUUIIOOPP</p><br/>
<p>-AASSDDFFGGHHJJKKLL*</p><br/>
<p>--ZZXXCCVVBBNNMM--**</p><br/>
<p>--------------------</p><br/>
<p>ACM-ICPC-WORLD-FINALS-2015</p><br/>
<p>Sample Output 2</p><br/>
<p>160</p><br/>
<p></p><br/>
<p>Sample Input 3</p><br/>
<p>6 4</p><br/>
<p>AXYB</p><br/>
<p>BBBB</p><br/>
<p>KLMB</p><br/>
<p>OPQB</p><br/>
<p>DEFB</p><br/>
<p>GHI*</p><br/>
<p>AB</p><br/>
<p>Sample Output 3</p><br/>
<p>7</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢phile提供译文">鸣谢phile提供译文</a></p></div>

