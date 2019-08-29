<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出一个长度不超过200的由小写英文字母组成的字母串(约定;该字串以每行20个字母的方式输入，且保证每行一定为20个)。要求将此字母串分成k份 (1&lt;k&lt;=40)，且每份中包含的单词个数加起来总数最大(每份中包含的单词可以部分重叠。当选用一个单词之后，其第一个字母不能再用。例 如字符串this中可包含this和is，选用this之后就不能包含th)。<br/>
　　单词在给出的一个不超过6个单词的字典中。<br/>
　　要求输出最大的个数。</div>
# 输入格式

<div class="pdcont">　　第一行有二个正整数(p，k)<br/>
　　p表示字串的行数;<br/>
　　k表示分为k个部分。<br/>
　　接下来的p行，每行均有20个字符。<br/>
　　再接下来有一个正整数s，表示字典中单词个数。(1&lt;=s&lt;=6)<br/>
　　接下来的s行，每行均有一个单词。</div>
# 输出格式

<div class="pdcont">　　每行一个整数，分别对应每组测试数据的相应结果。</div>
# 样例输入

<div class="pddata">1        3<br/>
thisisabookyouareaoh<br/>
4<br/>
is<br/>
a<br/>
ok<br/>
sab</div>
# 样例输出

<div class="pddata">7</div>
# 数据规模和约定

<div class="pdcont">　　长度不超过200，1&lt;k&lt;=40，字典中的单词数不超过6。</div>

</div>