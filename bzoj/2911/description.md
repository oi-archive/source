
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">给定两个单词序列：(x<sub>1</sub>,...,x<sub>n</sub>) and (y<sub>1</sub>,...,y<sub>n</sub>), 1 &lt;= n &lt;= 30。我们每次从两个序列中选取xi 或 yi中的一个，将被选择的单词将从左到右进行合并。共做n选择。每一步我们都可以从两个序列中的任意一个拿走一个单词。也就是说：最终的选择都是由1和2组成的一个长度为n的序列。当然不同选择方式，最终可能组成同一个单词。 如果一个选择的结果是可逆的，则我们说这种选择是对称的选择。例如：一个单词从左到右和从右到左读都相同。</span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>任务</b></span></div>
<div><span style="font-size: medium">写一个程序：</span></div>
<ul type="disc">
    <li><span style="font-size: medium">中读入数n和两个单词序列(x<sub>1</sub>,...,x<sub>n</sub>) 和 (y<sub>1</sub>,...,y<sub>n</sub>), </span></li>
    <li><span style="font-size: medium">从被给的序列中选择单词，计算对称选择的数目</span><span style="font-size: medium"> </span></li>
</ul></div>

# Input

<div class="content"><div> <span style="font-size: medium">第一行是一个正整数n， n &lt;= 30. 下面N行是连续的第一个序列，其中每一行为一个单词 (xi)，接下来是第二个序列，每一行为一个单词 (yi).单词 全部由小写的英文字母组成 (从a到 z)，单词的长度为[1..400]. </span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium"> 输出非负整数，为对称选择的数目。 </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
ab<br/>
a<br/>
a<br/>
ab<br/>
a<br/>
a<br/>
baaaa<br/>
a<br/>
a<br/>
ba<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

