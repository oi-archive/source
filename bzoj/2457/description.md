
# Description

<div class="content"><div style="margin: 13pt 0cm" align="center"></div>
<div><span style="font-size: 12pt">       Sherry</span><span style="font-size: 12pt">现在碰到了一个棘手的问题，有Ｎ个整数需要排序。</span></div>
<div><span style="font-size: 12pt">       Sherry</span><span style="font-size: 12pt">手头能用的工具就是若干个双端队列。</span></div>
<div><span style="font-size: 12pt">       </span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">她需要依次处理这</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个数，对于每个数，</span><span style="font-size: 12pt">Sherry</span><span style="font-size: 12pt">能做以下两件事：</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: 12pt">1．</span><span style="font-size: 12pt">新建一个双端队列，并将当前数作为这个队列中的唯一的数；</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: 12pt">2．</span><span style="font-size: 12pt">将当前数放入已有的队列的头之前或者尾之后。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt"> </div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">对所有的数处理完成之后，</span><span style="font-size: 12pt">Sherry</span><span style="font-size: 12pt">将这些队列排序后就可以得到一个非降的序列。</span></div></div>

# Input

<div class="content"><div><span style="font-size: 12pt">第一行包含一个整数</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">，表示整数的个数。接下来的</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">行每行包含一个整数</span><i><span style="font-size: 12pt">D<sub>i</sub></span></i><span style="font-size: 12pt">，其中</span><i><span style="font-size: 12pt">D<sub>i</sub></span></i><span style="font-size: 12pt">表示所需处理的整数。</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">其中只包含一行，为</span><span style="font-size: 12pt">Sherry</span><span style="font-size: 12pt">最少需要的双端队列数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
6<br/>
3<br/>
6<br/>
0<br/>
9<br/>
6<br/>
3<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
2</span></div>

# Hint

<div class="content"><p></p><p>100%的数据中N≤200000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

