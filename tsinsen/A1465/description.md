<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　现在有n个单词组成的一句话s0，以及m个由若干单词组成的长句子si，若s0的某一个排列是长句子si的子序列，则称s0同si相似，定义两者的差异度p为满足相似条件的排列的倒置数量（即在s0的原排列与当前排列中相对位置发生改变的单词对数）的最小值，现在需要你求出在m个长句子中与s0差异度最小的句子，若存在多个，则取编号最小的句子。</div>
# 输入格式

<div class="pdcont">　　第一行一个整数n。<br/>
　　第二行n个单词表示s0，单词之间用一个空格隔开。<br/>
　　第三行一个整数m。<br/>
　　接下来m行描述长句子，第i行一个整数L为长句子si的单词数量，接下来L个单词，单词之间用一个空格隔开。<br/>
　　长句子以1开始，按读入顺序标号。</div>
# 输出格式

<div class="pdcont">　　如果不存在长句子同s0相似则输出“Brand new problem!”（不含引号）。<br/>
　　否则第一行一个整数表示答案句子的编号。<br/>
　　第二行一个字符串包含字符 [: ，n*(n-1)/2-p+1 个 | ，最后两个字符 :]。</div>
# 样例输入

<div class="pddata">4<br/>
these papers are formulas<br/>
3<br/>
6 what are these formulas and papers<br/>
5 papers are driving me crazy<br/>
4 crazy into the night</div>
# 样例输出

<div class="pddata">1<br/>
[:||||:]</div>
# 数据规模和约定

<div class="pdcont">　　1&lt;=n&lt;=15，m&lt;=10，L&lt;=500000，数据保证所有单词都由不超过10个小写字母组成，且总长不超过500000。</div>

</div>