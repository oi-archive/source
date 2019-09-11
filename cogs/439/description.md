# 题目描述


<div>
<h3>
【问题描述】
</h3>
</div>
<div style="text-indent:24pt;">
对于一个软件公司来说，在发行一个新软件之后，可以说已经完成了工作。但是实际上，许多软件公司在发行一个新产品之后，还经常发送补丁程序，修改原产品中的错误(当然，有些补丁是要收费的)。
</div>
<div style="text-indent:24pt;">
如某微硬公司就是这样的一个软件公司。今年夏天，在发行了一个新的字处理软件之后，到现在他们已经编写了许多补丁程序。仅仅在这个周末，他们就用新编写的补丁程序解决了软件中的一个大问题。而在每一个补丁程序修改软件中的某些错误时，有可能引起软件中原来存在的某些错误重新发作。发生这种情况是因为当修改一个错误时，补丁程序利用了程序中约定的特别行为，从而导致错误的重新产生。
</div>
<div style="text-indent:24pt;">
微硬公司在他们的软件中一共发现了n个错误B={<span>b<sub>l</sub></span>，b<sub>2</sub>，…，<span>b<sub>n</sub></span>)，现在他们一共发送了m 个补丁程序p<sub>1</sub>,p<sub>2</sub>，…,p<sub>m</sub>。如果想要在软件中应用第p<sub>i</sub>号补丁程序，则软件中必须存在错误<span>B<sup>+</sup><sub>i</sub></span> ≤B，并且错误B<sup>-</sup><span><sub>i</sub></span>≤B必须不存在(显然，<span>B<sup>+</sup><sub>i</sub></span>∩B<sup>-</sup><span><sub>i</sub></span>为空集)。然后，这个补丁程序将改正错误 F<sup>-</sup><span><sub>i</sub></span>≤B(如果错误存在的话)，并且产生新错误<span>F<sup>+</sup><sub>i</sub></span>≤B(同样，<span>F<sup>+</sup><sub>i</sub></span>∩F<sup>-</sup><span><sub>i</sub></span>也为空集)。
</div>
<div style="text-indent:24pt;">
现在，微硬公司的问题只有一个。他们给出一个原始版本的软件，软件包含了B中的所有错误，然后按照某一顺序在软件中应用补丁程序(应用某个补丁程序时，软件必须符合该补丁程序的应用条件，且运行该程序需要一定的时间)。问怎样才能最快地改正软件中的所有错误(即为修正所有错误而运行的补丁程序的总时间最短)?
</div>
<div style="text-indent:24pt;">
 
</div>
<div>
<h3>
【输入格式】
</h3>
</div>
<div style="text-indent:24pt;">
数据存放在当前目录下的文本文件“<span>bugs.in</span>&#34;中。
</div>
<div style="text-indent:24pt;">
文件的第一行包含两个整数n和m，分别表示软件中的错误个数和发送的补丁个数。其中，n和m满足条件：1≤n≤20，1≤m≤100。
</div>
<div style="text-indent:24pt;">
接下来的m行(即第2行至第m+1行)按顺序描述了m个补丁程序的情况，第<span>i</span>行描述第i-1号补丁程序。每一行包含一个整数(表示在软件中应用该补丁程序所需的时间，单位为秒)和两个n个字符的字符串(中间均用一个空格分开)。、
</div>
<div style="text-indent:24pt;">
第一个字符串描述了应用该补丁程序(第i-1号)的条件，即说明在软件中某错误应该存在还是不应该存在。字符串的第<span>i</span>个字符，如果是“+”，表示在软件中必须存在b<sub>i</sub>号错误；如果是“-”，表示软件中错误b<sub>i</sub>不能存在；如果是“0&#34;，则表示错误bi存在或不存在均可(即对应用该补丁程序没有影响)。
</div>
<div style="text-indent:24pt;">
第二个字符串描述了应用该补丁程序(第i-1号)后的效果，即应用补丁程序后，哪些错误被修改好了，而又产生了哪些新错误。字符串的第<span>i</span>个字符，如果是“+”，表示产生了一个新错误b<sub>i</sub>；如果是“-”，表示错误b<sub>i</sub>被修改好了；如果是“0”，则表示错误b<sub>i</sub>不变(即原来存在，则仍然存在；原来不存在，则也不存在)。
</div>
<div style="text-indent:24pt;">
 
</div>
<div>
<h3>
【输出格式】
</h3>
</div>
<div style="text-indent:24pt;">
答案输出在当前目录下的文本文件“<span>bugs.out</span>&#34;中。
</div>
<div style="text-indent:24pt;">
请你找到一个应用补丁程序的最优顺序，修改软件中的所有错误，并且所用的时间最少。
</div>
<div style="text-indent:24pt;">
注意，每个补丁程序是可以应用多次的。
</div>
<div style="text-indent:24pt;">
如果存在这样一个序列，请在输出文件的第一行输出应用补丁程序的总时间(单位为秒)；如果找不到这样一个序列，请在输出文件的第一行输出-1。
</div>
<div style="text-indent:24pt;">
 
</div>
<div>
<h3>
【输入输出样例】
</h3>
</div>
<div style="text-indent:24pt;">
样例输入（<span>bugs.in</span>）:
</div>
<div style="text-indent:24pt;">
3 <span>3</span> 
</div>
<div style="text-indent:24pt;">
1 000 00-
</div>
<div style="text-indent:24pt;">
1 00- 0-+
</div>
<div style="text-indent:24pt;">
2 0-- -++
</div>
<div style="text-indent:24pt;">
样例输出（<span>bugs.out</span>）：
</div>
<div style="text-indent:24pt;">
8
</div>
