<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　一般的文本编辑器都有查找单词的功能，该功能可以快速定位特定单词在文章中的位置，有的还能统计出特定单词在文章中出现的次数。<br/>
　　现在，请你编程实现这一功能，具体要求是：给定一个单词，请你输出它在给定的文章中出现的次数和第一次出现的位置。注意：匹配单词时，不区分大小写，但要求完全匹配，即给定单词必须与文章中的某一独立单词在不区分大小写的情况下完全相同 （参见样例 1） ，如果给定单词仅是文章中某一单词的一部分则不算匹配（参见样例 2） 。</div>
# 输入格式

<div class="pdcont">　　输入2行。<br/>
　　第 1 行为一个字符串，其中只含字母，表示给定单词；<br/>
　　第 2 行为一个字符串，其中只可能包含字母和空格，表示给定的文章。</div>
# 输出格式

<div class="pdcont">　　输出一行， 如果在文章中找到给定单词则输出两个整数， 两个整数之间用一个空格隔开，分别是单词在文章中出现的次数和第一次出现的位置（即在文章中第一次出现时，单词首字母在文章中的位置，位置从 0 开始） ；如果单词在文章中没有出现，则直接输出一个整数-1。</div>
# 样例输入

<div class="pddata">To<br/>
to be or not to be is a question</div>
# 样例输出

<div class="pddata">2 0</div>
# 样例输入

<div class="pddata">to<br/>
Did the Ottoman Empire lose its power at that time</div>
# 样例输出

<div class="pddata">-1</div>
# 输入输出样例 1 说明

<div class="pdcont">　　输出结果表示给定的单词 To 在文章中出现两次，第一次出现的位置为 0。</div>
# 输入输出样例 2 说明

<div class="pdcont">　　表示给定的单词 to 在文章中没有出现，输出整数-1。</div>
# 数据规模和约定

<div class="pdcont">　　1 ≤单词长度≤10。<br/>
　　1 ≤文章长度≤1,000,000。</div>

</div>