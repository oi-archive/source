
# Description

<div class="content"><div>【故事背景】</div>
<div>JYY在JSOI有很多很多的好朋友，比如PUPPY，KFC还有PUPPUP。因为</div>
<div>有了这么多的好朋友，所以JYY每天都很快乐。某天，JYY发现好朋友之间关</div>
<div>系的好坏和名字有很大的关系，比如PUPPY和PUPPUP的关系就特别好，但是</div>
<div>和KFC的关系就很一般。JYY苦思冥想终于发现了其中的规律，现在JYY想知</div>
<div>道两个朋友之间关系的好坏，你能帮助JYY么？</div>
<div>【问题描述】</div>
<div>给定两个字符串A和B，表示JYY的两个朋友的名字。我们用A(i,j)表示A</div>
<div>字符串中从第i个字母到第j个字母所组成的子串。同样的，我们也可以定义B(x,y)。</div>
<div>JYY发现两个朋友关系的紧密程度，等于同时满足如下条件的四元组(i,j,x,y)</div>
<div>的个数：</div>
<div>1:1&lt;=i&lt;=j&lt;=|A|</div>
<div>2:1&lt;=x&lt;=y&lt;=|B|</div>
<div>3:A(i,j)=B(x,y)</div>
<div>4:A(i,j)是回文串</div>
<div>这里表示字符串A的长度。</div>
<div>JYY希望你帮助他计算出这两个朋友之间关系的紧密程度。</div></div>

# Input

<div class="content"><p>数据包行两行由大写字母组成的字符串A和B<br/>
1≤|A|,|B|≤50000。</p></div>

# Output

<div class="content"><p>包含一行一个整数，表示紧密程度，也就是满足要求的4元组个数</p></div>

# Sample Input

<div class="content"><span class="sampledata">PUPPY<br/>
PUPPUP</span></div>

# Sample Output

<div class="content"><span class="sampledata">17</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

