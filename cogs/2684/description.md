# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
Transmitting and memorizing information is a task that requires different coding systems for the best use of the available space. A well known system is that one where a number is associated to a character sequence. It is considered that the words are made only of small characters of the English alphabet a,b,c, ..., z (26 characters). From all these words we consider only those whose letters are in lexigraphical order (each character is smaller than the next character).
</p>
<p>
<br/>
</p>
<p>
The coding system works like this:
</p>
<p>
•	The words are arranged in the increasing order of their length.
</p>
<p>
•	The words with the same length are arranged in lexicographical order (the order from the dictionary).
</p>
<p>
•	We codify these words by their numbering, starting with a, as follows:
</p>
<p>
a - 1
</p>
<p>
b - 2
</p>
<p>
...
</p>
<p>
z - 26
</p>
<p>
ab - 27
</p>
<p>
...
</p>
<p>
az - 51
</p>
<p>
bc - 52
</p>
<p>
...
</p>
<p>
vwxyz - 83681
</p>
<p>
...
</p>
<p>
<br/>
</p>
<p>
Specify for a given word if it can be codified according to this coding system. For the affirmative case specify its code.
</p>
<p>
题目大意：求出给定的字符在字典中的编码，字典中的单词由小写字母组成且,s满足对于任意字符s[i]&lt;s[i+1]。
</p>
<p>
字典从&#34;a&#34;开始。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
要处理的字母
</p>
<h3>
【输出格式】
</h3>
<p>
编号，若不在字典中输出0
</p>
<h3>
【样例输入】
</h3>
<pre>bf</pre>
<h3>
【样例输出】
</h3>
<pre>55</pre>
<h3>
【来源】
</h3>
<p>
POJ1850
</p>
