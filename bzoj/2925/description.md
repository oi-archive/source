
# Description

<div class="content"><div><span style="font-size: medium">假设K是一个不为0的十进制阿拉伯数字。如果有这样一个表达式：它的值为X同时它仅仅包含了由阿拉伯数字K所组成的数字，那么我们称这样的算术表达式为整数X的K-表示法（所有这些数字当然也是十进制的）。在这个表达式中，下面的算术操作是允许的：包括加、减、乘、除,而圆括号也是允许使用的。除法只有当被除数是除数的若干倍时才能使用。</span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>例如</b></span></div>
<div><span style="font-size: medium">下面每一个表达式是数字12的5-表示法： </span></div>
<ul type="disc">
    <li><span style="font-size: medium">5+5+(5:5)+(5:5) </span></li>
    <li><span style="font-size: medium">(5+(5))+5:5+5:5 </span></li>
    <li><span style="font-size: medium">55:5+5:5 </span></li>
    <li><span style="font-size: medium">(55+5):5 </span></li>
</ul>
<div><span style="font-size: medium">K-表示法的长度是这个表达式中阿拉伯K出现的次数。上面例子中的头两个表示法长度是6，第三个是5，第四个是4。 </span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>任务</b></span></div>
<div><span style="font-size: medium">写一个程序：</span></div>
<div style="margin-left: 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>阿拉伯数字K和数字的级数，</span></div>
<div style="margin-left: 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>从这个级数检验每一个数字，看它是否有长度最多为8的K-表示法，如果存在则程序找出这个表示法的最小长度。</span></div>
<div style="margin-left: 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>把结果输出 </span></div></div>

# Input

<div class="content"><div style="margin: auto 0cm"> </div>
<div><span style="font-size: medium">输入文件MON.IN的首行包括阿拉伯数字K，K是{1,…,9}中的元素。第二行包括数字n（<i>1&lt;=n&lt;=10</i>）。在接下来的n 行中有自然数序列<i>a<sub>1</sub>,...,a<sub>n</sub></i>,<i> 1&lt;=a<sub>i</sub>&lt;=32000</i> (for <i>i=1,..,n</i>)，每一行一个数字。</span></div>
<div style="margin: auto 0cm">
<div style="margin: auto 0cm"></div>
</div></div>

# Output

<div class="content"><div style="margin: auto 0cm">
<div style="margin: auto 0cm"></div>
<span style="font-size: medium">由n行组成。第I行应该包括：</span></div>
<div style="margin: 0cm 0cm 0pt 18pt; text-indent: -18pt"><span style="font-size: medium">1． 1．假设一个长度不大于8的表示法存在，确定一个数字，它是a<i><sub>i</sub></i>的K-表示法的最小长度。</span></div>
<div style="margin: 0cm 0cm 0pt 18pt; text-indent: -18pt"><span style="font-size: medium">2． 2．如果数字a<i><sub>i</sub></i>的K-表达法的最小长度是大于8则为单词NIE（波兰语为“没有”）</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2<br/>
12<br/>
31168<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
4<br/>
NIE<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

