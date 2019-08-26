
# Description

<div class="content"> 本题中，我们考察的是一类特殊的序列，这类序列只有+、-（正号，负号）两种符号构成，比如：-+++---++

 我们将其中连续的+的长度按从左到右的顺序写出，即其派生序列，如-+++---++的派生序列为（3，2）。

 现在的问题是，我们已知一个序列A的派生序列B，但是A的部分符号已经模糊到不能辨认的地步了。我们需要确定尽量多的符号。

 

</div>

# Input

<div class="content"> 输入文件有两行。

第一行一个由+、-、？构成的序列，描述A，其中？表示已经无法辨认的符号。

第二行有若干整数描述A的生成序列B。

</div>

# Output

<div class="content"> 输出一行，一个序列描述你恢复后的序列A（不能多余的空格），如果无解则输出一行No Solution。

</div>

# Sample Input

<div class="content"><span class="sampledata">+????-+??+<br/>
2 1 4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">++-??-++++<br/>
</span></div>

# Hint

<div class="content"><p>对于100%的数据满足|A| &lt; 20001<br/>
<br/>
B的元素属于[1 … |A|]<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=第一届“NOIer”全国竞赛">第一届“NOIer”全国竞赛</a></p></div>

