<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Huffman树在编码中有着广泛的应用。在这里，我们只关心Huffman树的构造过程。<br/>
　　给出一列数{<i>p<sub>i</sub></i>}={<i>p</i><sub>0</sub>, <i>p</i><sub>1</sub>, …, <i>p<sub>n</sub></i><sub>-1</sub>}，用这列数构造Huffman树的过程如下：<br/>
　　1.      找到{<i>p<sub>i</sub></i>}中最小的两个数，设为<i>p<sub>a</sub></i>和<i>p<sub>b</sub></i>，将<i>p<sub>a</sub></i>和<i>p<sub>b</sub></i>从{<i>p<sub>i</sub></i>}中删除掉，然后将它们的和加入到{<i>p<sub>i</sub></i>}中。这个过程的费用记为<i>p<sub>a</sub></i> + <i>p<sub>b</sub></i>。<br/>
　　2.      重复步骤1，直到{<i>p<sub>i</sub></i>}中只剩下一个数。<br/>
　　在上面的操作过程中，把所有的费用相加，就得到了构造Huffman树的总费用。<br/>
　　本题任务：对于给定的一个数列，现在请你求出用该数列构造Huffman树的总费用。<br/>
<br/>
　　例如，对于数列{<i>p<sub>i</sub></i>}={5, 3, 8, 2, 9}，Huffman树的构造过程如下：<br/>
　　1.      找到{5, 3, 8, 2, 9}中最小的两个数，分别是2和3，从{<i>p<sub>i</sub></i>}中删除它们并将和5加入，得到{5, 8, 9, 5}，费用为5。<br/>
　　2.      找到{5, 8, 9, 5}中最小的两个数，分别是5和5，从{<i>p<sub>i</sub></i>}中删除它们并将和10加入，得到{8, 9, 10}，费用为10。<br/>
　　3.      找到{8, 9, 10}中最小的两个数，分别是8和9，从{<i>p<sub>i</sub></i>}中删除它们并将和17加入，得到{10, 17}，费用为17。<br/>
　　4.      找到{10, 17}中最小的两个数，分别是10和17，从{<i>p<sub>i</sub></i>}中删除它们并将和27加入，得到{27}，费用为27。<br/>
　　5.      现在，数列中只剩下一个数27，构造过程结束，总费用为5+10+17+27=59。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个正整数<i>n</i>（<i>n</i>&lt;=100）。<br/>
　　接下来是<i>n</i>个正整数，表示<i>p</i><sub>0</sub>, <i>p</i><sub>1</sub>, …, <i>p<sub>n</sub></i><sub>-1</sub>，每个数不超过1000。</div>
# 输出格式

<div class="pdcont">　　输出用这些数构造Huffman树的总费用。</div>
# 样例输入

<div class="pddata">5<br/>
5 3 8 2 9</div>
# 样例输出

<div class="pddata">59</div>

</div>