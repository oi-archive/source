
# Description

<div class="content"><div style="text-align: left;"><span style="font-size: medium">给定一个长度为N的颜色序列C，对于该序列中的任意一个元素Ci，都有1&lt;=Ci&lt;=M。对于一种颜色ColorK来说，区间[L,R]内的权值定义为这种颜色在该区间中出现的次数的平方，即区间[L,R]内中满足Ci=ColorK的元素个数的平方。接下来给出Q个询问，询问区间[L,R]内颜色[a,b]的权值总和。</span></div>
<div style="text-align: left;"><span style="font-size: medium"> </span></div>
<div></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第1行三个整数N,M,Q。分别代表序列长度，颜色总数和询问总数。</span></div>
<div><span style="font-size: medium">第2行N个整数，代表序列Ci。</span></div>
<div><span style="font-size: medium">第3行到第Q+2行，每行4个整数l,r,a,b。记上一次计算出的答案为Lans。那么实际的l,r,a,b为给出的l,r,a,b xor上Lans。第一个询问的时候Lans=0。</span></div>
<div><span style="font-size: medium"> </span></div>
<div></div></div>

# Output

<div class="content"><div><span style="font-size: medium">总共Q行，对于每一个询问，输出权值总和</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 3<br/>
1 1 2 2 <br/>
1 4 1 2<br/>
10 11 9 10<br/>
3 0 0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
2<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p><p><font size="3">1&lt;=N,Q&lt;=50000,M&lt;=20000</font></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

