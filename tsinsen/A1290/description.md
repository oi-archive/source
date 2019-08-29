<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Huffman coding is an entropy encoding algorithm. For a set of positive weights <i>W</i>={<i>w</i><sub>1</sub>, <i>w</i><sub>2</sub>, …, <i>w<sub>n</sub></i>}, the algorithm finds out a prefix-free binary code <i>C</i>={<i>c</i><sub>1</sub>, <i>c</i><sub>2</sub>,…,<i>c<sub>n</sub></i>}, where <i>c<sub>i</sub></i>  (1 ≤ <i>i</i> ≤ <i>n</i>) is a binary codeword, with minimum expected codeword length, or explicitly, the minimum length <i>L </i>= <i>w</i><sub>1</sub>*length(<i>c</i><sub>1</sub>)+<i>w</i><sub>2</sub>*length(<i>c</i><sub>2</sub>)+…+<i>w<sub>n</sub></i>*length(<i>c<sub>n</sub></i>).<br/>
　　Now given a set of binary codewords, please find out the minimum number of binary codewords to be added to the set, so that the set can be a legal Huffman code. Note that if the set given is already a legal Huffman code, the answer should be 0.</div>
# 输入格式

<div class="pdcont">　　The first line of the input contains an integer <i>N</i>, indicating the size of the set <i>C</i>.<br/>
　　Each of the following <i>N</i> lines contains a binary codeword.</div>
# 输出格式

<div class="pdcont">　　The output should contain exactly one line with one integer, which is the minimum number of binary codewords needed. If it is not possible to add codewords to make the set <i>C</i> a legal Huffman code, the output should be one integer -1.</div>
# Sample Input One

<div class="pdcont">　　3<br/>
　　10<br/>
　　01<br/>
　　1</div>
# Sample Output One

<div class="pdcont">　　-1</div>
# Sample Input Two

<div class="pdcont">　　4<br/>
　　00<br/>
　　01<br/>
　　10<br/>
　　11</div>
# Sample Output Two

<div class="pdcont">　　0</div>
# Sample Input Three

<div class="pdcont">　　4<br/>
　　000<br/>
　　01<br/>
　　0011<br/>
　　10</div>
# Sample Output Three

<div class="pdcont">　　2</div>
# Explanations

<div class="pdcont">　　In the third sample, the two missing code words could be 0010 and 11.</div>
# Constraints

<div class="pdcont">　　For all test cases, 1 ≤ <i>n</i> ≤ 1000, and the length of each binary codeword is no larger than 20.</div>

</div>