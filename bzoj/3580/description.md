
# Description

<div class="content"><p><span style="font-size: medium">　　下面是一段实现冒泡排序算法的C++代码：</span></p>
<p><span style="font-size: medium">　　for (int i=1;i&lt;n;i++)<br/>
　　for (int j=1;j&lt;=n-i;j++)<br/>
　　if (a[j]&gt;a[j+1])<br/>
　　swap(a[j],a[j+1]);</span></p>
<p></p>
<p><span style="font-size: medium">　　其中待排序的a数组是一个1~n的排列，swap函数将交换数组中对应位置的值。<br/>
　　对于给定的数组a以及给定的非负整数k，使用这段代码执行了正好k次swap操作之后数组a中元素的值会是什么样的呢？<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　输入文件共2行。<br/>
　　第1行包含空格隔开的一个正整数n和一个非负整数k；<br/>
　　第2行包含n个空格隔开的互不相同的正整数，表示初始时a数组中的排列。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">　　输出文件共1行。<br/>
　　若在执行完整个代码之后执行swap的次数仍不够k，那么输出一个字符串”Impossible!”(不含引号)，否则按顺序输出执行swap操作k次之后数组a的每一个元素，用空格隔开。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 1<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Impossible!<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">n&lt;=10^6<br/><br/>
k&lt;=10^12<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

