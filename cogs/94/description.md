# 题目描述


<p>
<br/>
</p>
<p>
Description
</p>
<p>
给出一个长度不超过200的由小写英文字母组成的字母串(约定;该字串以每行20个字母的方式输入，且保证每行一定为20个)。要求将此字母串分成k份(1＜k≤40)，且每份中包含的单词个数加起来总数最大(每份中包含的单词可以部分重叠。当选用一个单词之后，其第一个字母不能再用。例如字符串this中可包含this和is，选用this之后就不能包含th)。 单词在给出的一个不超过6个单词的字典中。要求输出最大的个数。
</p>
<p>
Input
</p>
<p>
（在正式输入前有一行一个1，代表数据组数）
</p>
<p>
第一行有2个正整数p，k。p表示字串的行数；k表示分为k个部分。
</p>
<p>
接下来的p行，每行均有20个字符。
</p>
<p>
再接下来有一个正整数s，表示字典中单词个数。(1≤s≤6)
</p>
<p>
接下来的s行，每行均有一个单词。
</p>
<p>
Output
</p>
<p>
仅一行，一个整数，表示划分出来的最多单词个数。
</p>
<p>
Sample Input
</p>
<p>
1
</p>
<p>
1 3
</p>
<p>
thisisabookyouareaoh
</p>
<p>
4
</p>
<p>
is
</p>
<p>
a
</p>
<p>
ok
</p>
<p>
sab
</p>
<p>
Sample Output
</p>
<p>
7
</p>
<p>
Hint
</p>
<p>
按如下方式划分字符串：
</p>
<p>
this/isabookyoua/reaoh
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>