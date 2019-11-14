<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　笨小猴的词汇量很小，所以每次做英语选择题的时候都很头疼。但是他找到了一种方法，经试验证明，用这种方法去选择选项的时候选对的几率非常大！<br/>
　　这种方法的具体描述如下：假设maxn是单词中出现次数最多的字母的出现次数，minn是单词中出现次数最少的字母的出现次数，如果maxn-minn是一个质数，那么笨小猴就认为这是个Lucky Word，这样的单词很可能就是正确的答案。</div>
# 输入格式

<div class="pdcont">　　输入只有一行，是一个单词，其中只可能出现小写字母，并且长度小于100。</div>
# 输出格式

<div class="pdcont">　　输出共两行，第一行是一个字符串，假设输入的的单词是Lucky Word，那么输出“Lucky Word”，否则输出“No Answer”；<br/>
　　第二行是一个整数，如果输入单词是Lucky Word，输出maxn-minn的值，否则输出0。</div>
# 样例输入

<div class="pddata">error</div>
# 样例输出

<div class="pddata">Lucky Word<br/>
2</div>
# 输入输出样例1解释

<div class="pdcont">　　单词error中出现最多的字母r出现了3次，出现次数最少的字母出现了1次，3-1=2，2是质数。</div>
# 样例输入

<div class="pddata">olympic</div>
# 样例输出

<div class="pddata">No Answer<br/>
<br/>
0</div>
# 输入输出样例2解释

<div class="pdcont">　　单词olympic中出现最多的字母i出现了2次，出现次数最少的字母出现了1次，2-1=1，1不是质数。</div>

</div>