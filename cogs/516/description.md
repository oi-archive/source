# 题目描述


<p>
【问题描述】<br/>
<br/>
给出一个数列A1，A2…．，An和K，P。<br/>
设<span style="font-size:24px;">S</span>ij=<span style="font-size:24px;">A</span>i<span style="font-size:24px;">+</span><span style="font-size:24px;">A</span>i+1<span style="font-size:24px;">+</span>…<span style="font-size:24px;">+A</span>j<br/>
Anaswer=min{S<sub>i,j</sub> mod P | s<sub>i,j</sub> mod P≥K)，其中i≤j，(s<sub>i,j</sub> mod P | s<sub>i,j</sub> mod P≥K}非空。
</p>
<p>
【输入格式】<br/>
第一行一个正整数n，K，P。<br/>
第二行n个整数，表示一个数列A1，A2，…，An
</p>
<p>
【输出格式】<br/>
在第一行输出Answer。
</p>
<p>
【输入样例】<br/>
7 2 17<br/>
12<br/>
13<br/>
15<br/>
11<br/>
16<br/>
26<br/>
11
</p>
<p>
【输出样例】
</p>
<p>
2
</p>
<p>
【数据范围】<br/>
在100％的数据中，1&lt;n&lt;100000，1&lt;K，P，ai&lt;108，i=1，2…n<br/>
 
</p>
