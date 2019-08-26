
# Description

<div class="content"><div align="center"></div>
<div style="text-indent: 20.65pt"><span style="font-size: medium"><b>基因串</b>是由一串有限长度的基因所组成的，其中每一个基因都可以用26个英文大写字母中的一个来表示，不同的字母表示不同的基因类型。一个单独的基因可以生长成为一对新的基因，而可能成长的规则是通过一个有限的成长规则集所决定的。每一个成长的规则可以用三个大写英文字母A<sub>1</sub>A<sub>2</sub>A<sub>3</sub>来描述，这个规则的意思是基因A<sub>1</sub>可以成长为一对基因A<sub>2</sub>A<sub>3</sub>。</span></div>
<div><span style="font-size: medium">我们用大写字母S来表示一类被称作<b>超级基因</b>的基因。因为每一个基因串都是由一串超级基因根据给出的规则所成长出来的。</span></div>
<div><span style="font-size: medium">任务：</span></div>
<div><span style="font-size: medium">请写一个程序：</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>读入有限条成长的规则和一些我们想要得到的基因串；</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>对于每个基因串，试判断它是否可以由一个有限长度的超级基因串成长得出。如果可以，那么请给出可成长为该基因串的最短超级基因串的长度；</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>把结果输出</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行包括一个整数<i>n</i>，<i>1 </i><i>£ n </i><i>£ 10000</i>。以下的<i>n</i>行中每行都包括一个成长的规则，每个规则由三个大写英文字母组成。</span></div>
<div><span style="font-size: medium">在该文件的第<i>n+1</i>行包括一个整数<i>k</i>，<i>1 </i><i>£ k </i><i>£ 10000</i>。以下的<i>k</i>行中每行都有一个基因串。每个基因串都是一个长度不超过100的大写字符串。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">你应该输出入下内容：</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>一个正整数，表示成长为改基因串所需的最短的超级基因串的长度；</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>或一个单词NIE（波兰语的“否”），如果说无法由超级基因串成长成为该基因串。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
SAB<br/>
SBC<br/>
SAA<br/>
ACA<br/>
BCC<br/>
CBC<br/>
3<br/>
ABBCAAABCA<br/>
CCC<br/>
BA<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
NIE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

