
# Description

<div class="content"><p>考虑到如下的两段代码，很容易发现他们其实是一样的。<br/>
代码1 <br/>
int i, j; <br/>
i = 3; <br/>
j = i + 1; <br/>
代码2<br/>
int a, i; <br/>
a = 3; <br/>
i = a + 1; <br/>
这是因为这两段代码之间唯一的差异，只是他们更换了一下变量名，比如第<br/>
一段代码中的i变成了第二段的a，第一段的j变成了第二段的i。而其他的常量，<br/>
例如3，1或者其他的关键字和运算符，比如 int，+和；。都是没有发生变化的。  <br/>
不过注意到如下的代码片段，我们并不能简单认为这是一样的，因为这不是<br/>
一个简单的替换，而是可以导致不同运算结果的。<br/>
代码3<br/>
a = 3; <br/>
b = 3; <br/>
代码4<br/>
c = 3; <br/>
c = 3;  <br/>
为了简化问题，我们用大写字母来表示所有的关键字、常量等非变量符合。<br/>
假如我们采用如下的替换表 <br/>
<img width="612" height="92" alt="" src="/source/bzoj/4462/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC8zMy5wbmc=.png"/><br/>
那么最开始给出的两段雷同代码就可以分别写成 AiBjCiDECjDiFGC 以及<br/>
AaBiCaDECiDaFGC。或者简单的说，我们认为这两段代码是一样的。 <br/>
现在请写一个程序，处理若干这样的代码雷同检测问题：给一个完整代码以<br/>
及一个较短的代码片段，请求出，这个代码片段在完整代码中一共出现了多少次<br/>
（代码片段出现的位置可以重叠）。 <br/>
为了简单起见，我们认为程序中只会至多出现 a~z 这 26 个变量，同时也至<br/>
多只有A~Z这26个非变量符号。</p></div>

# Input

<div class="content"><p>第一行包含一个整数 Q表示此数据中一共包含 Q个询问。 <br/>
接下来 2Q行，每两行为一个询问。 <br/>
每个询问中的第一行包含一个字符串 S，表示完整代码，第二行包含一个字符串<br/>
T，表示需要检测出现次数的代码片段。</p></div>

# Output

<div class="content"><p>一共输出 Q行，每行一个整数，表示对应代码片段的出现次数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
AiBjCiDECjDiFGC<br/>
AaBiCaDECiDaFGC<br/>
cDEcDEbDE<br/>
aDEbDE<br/>
ccddef<br/>
aab</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
2<br/>
【样例说明】<br/>
前两个样例均为题目中所举例的代码段。第三个样例中，在完整代码 S中与<br/>
代码片段T 一样的片段为：ccd和dde</span></div>

# Hint

<div class="content"><p></p><p>Q&lt;=3,|T|&lt;=100000,|S|&lt;=1000000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

