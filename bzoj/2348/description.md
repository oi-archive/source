
# Description

<div class="content"><div align="center"></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">世界编程大赛的选手们提交</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">份程序文件</span><i><span style="font-size: 12pt">f</span></i><sub><span style="font-size: 12pt">1</span></sub><span style="font-size: 12pt">, …, <i>f</i><sub>N</sub></span><span style="font-size: 12pt">给评测系统。在将评测结果正式公布之前，评委会想要排除一切可能的剽窃现象。他们已有一个对比程序，用来比较两份程序文件，并判断它们是否太过相似了。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">然而程序文件的数目相当大，把每两份（一对，</span><span style="font-size: 12pt">pair</span><span style="font-size: 12pt">）文件都进行比较的话将花太多的时间。另一方面，许多对</span><span style="font-size: 12pt">(pair)</span><span style="font-size: 12pt">可以直接被排除，如果文件的大小相差太大的话。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">更准确地说，评委会决定，如果每两份文件（一对，</span><span style="font-size: 12pt">pair</span><span style="font-size: 12pt">）中，较小文件的体积小于较大文件的体积的</span><span style="font-size: 12pt">90%</span><span style="font-size: 12pt">，那将直接不比较这样的一对</span><span style="font-size: 12pt">(pair)</span><span style="font-size: 12pt">。所以，对比程序只比较这样的一对</span><span style="font-size: 12pt">(<i>f</i><sub>i</sub>, <i>f</i><sub>j</sub>)</span><span style="font-size: 12pt">：</span><span style="font-size: 12pt"> i≠j, size(<i>f</i><sub>i </sub>)≤ size(<i>f</i><sub>j </sub>)</span><span style="font-size: 12pt">且</span><span style="font-size: 12pt">size(<i>f</i><sub>i </sub>)≥0.9∙size(<i>f</i><sub>j </sub>)</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">编写程序计算有多少对</span><span style="font-size: 12pt">(pair)</span><span style="font-size: 12pt">文件需要被比较。</span></div>
<div></div></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">第</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">行包含一个整数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，即提交的程序文件总数。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">第</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">行包含</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个整数</span><span style="font-size: 12pt">size(<i>f</i><sub>1</sub>), …, size(<i>f</i><sub>N</sub>)</span><span style="font-size: 12pt">，每个整数代表文件的体积大小。</span></div>
<div style="text-indent: 24pt"></div></div>

# Output

<div class="content"><div style="text-indent: 24pt"><span style="font-size: 12pt">第</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">行，也是唯一的一行，给出一个整数，即需要被比较的文件的对</span><span style="font-size: 12pt">(pair)</span><span style="font-size: 12pt">的数目。</span></div>
<div><b><span style="font-size: 14pt">数据范围</span></b></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">1≤ N ≤100 000</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">1≤ size(<i>f</i><sub>i</sub> ) ≤100 000 000</span></div>
<p><span style="font-size: 12pt">有</span><span style="font-size: 12pt">50</span><span style="font-size: 12pt">分的测试点中，</span><span style="font-size: 12pt">1≤ N ≤2 000</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1 1 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p><div style="text-indent: 24pt"><span style="font-size: 12pt">第</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">个样例中，每两个文件之间都要互相比较（当然，每对只比较一次，不是两次）。</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

