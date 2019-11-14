
# Description

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">curimit知道陶陶很喜欢吃苹果。于是curimit准备在陶陶生日的时候送给他一棵苹果树。 <br/>
<br/>
curimit准备了一棵这样的苹果树作为生日礼物：这棵苹果树有n个节点，每个节点上有c[i]个苹果，这棵树高度为h。 <br/>
<br/>
可是，当curimit把这棵树给陶陶看的时候，陶陶却说：“今年生日不收礼，收礼只收节点数减高度不超过k的苹果树。”这下curimit犯难了，curimit送来的树枝繁叶茂，不满足节点数-高度≤k。于是curimit决定剪掉一些枝条，使得修剪过后的树满足节点数-高度≤k，但是curimit又想保留尽量多的苹果数目。curimit想请你帮他算算经过修剪后的树最多能保留多少个苹果。 <br/>
<br/>
注： <br/>
一， 节点1为树根，不能把它剪掉。 <br/>
二， 1个节点的树高度为1。 <br/>
</font></span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">输入文件的第一行为两个整数n，k分别表示这棵树有n个节点，修剪后的树节点数-高度≤k。 <br/>
<br/>
第二行开始到第n+1行，每行有两个数，第i+1行的两个数father[i]和c[i]分别表示节点i的父亲是father[i]和节点i处有c[i]个苹果。 <br/>
<br/>
规定：节点1的父亲为0。 <br/>
</font></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">输出文件仅包含一行，ans，表示在满足修建后的树节点数-高度≤k的条件下，最多能保留多少个苹果。 <br/>
<br/>
<br/>
</font></span></p>
<p align="left"></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 3<br/>
0 89928<br/>
1 38219<br/>
1 91615<br/>
2 5517<br/>
3 15244<br/>
3 78458<br/>
1 76512<br/>
4 99582<br/>
7 64607<br/>
1 91175<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">494494<br/>
</span></div>

# Hint

<div class="content"><p></p><p align="left"><font face="Times New Roman" size="3">对于10%的数据， n≤10 <br/><br/>
对于30%的数据， n≤100　　0≤k≤20 <br/><br/>
对于100%的数据，n≤4000 0≤k≤=500 </font><span id="1332744975363E" style="display: none"> </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

