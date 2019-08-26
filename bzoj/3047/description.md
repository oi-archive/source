
# Description

<div class="content"><p><span style="font-size: medium">为了随时与rainbow快速交流，Freda制造了两部传呼机。Freda和rainbow所在的地方有N座房屋、M条双向光缆。每条光缆连接两座房屋，传呼机发出的信号只能沿着光缆传递，并且传呼机的信号从光缆的其中一端传递到另一端需要花费t单位时间。现在Freda要进行Q次试验，每次选取两座房屋，并想知道传呼机的信号在这两座房屋之间传递至少需要多长时间。Freda和rainbow简直弱爆了有木有T_T，请你帮帮他们吧……<br/>
N座房屋通过光缆一定是连通的，并且这M条光缆有以下三类连接情况：<br/>
A：光缆不形成环，也就是光缆仅有N-1条。<br/>
B：光缆只形成一个环，也就是光缆仅有N条。<br/>
C：每条光缆仅在一个环中。</span><span style="font-size: medium">。</span></p></div>

# Input

<div class="content"><p> </p>
<p><span style="font-size: medium">第一行包含三个用空格隔开的整数，N、M和Q。<br/>
接下来M行每行三个整数x、y、t，表示房屋x和y之间有一条传递时间为t的光缆。<br/>
最后Q行每行两个整数x、y，表示Freda想知道在x和y之间传呼最少需要多长时间。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出Q行，每行一个整数，表示Freda每次试验的结果。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
5 4 2<br/>
1 2 1<br/>
1 3 1<br/>
2 4 1<br/>
2 5 1<br/>
3 5<br/>
2 1<br/>
<br/>
样例输入2<br/>
5 5 2<br/>
1 2 1<br/>
2 1 1<br/>
1 3 1<br/>
2 4 1<br/>
2 5 1<br/>
3 5<br/>
2 1<br/>
<br/>
样例输入3<br/>
9 10 2<br/>
1 2 1<br/>
1 4 1<br/>
3 4 1<br/>
2 3 1<br/>
3 7 1<br/>
7 8 2<br/>
7 9 2<br/>
1 5 3<br/>
1 6 4<br/>
5 6 1<br/>
1 9<br/>
5 7</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
<br/>
样例输出1<br/>
3<br/>
1<br/>
<br/>
样例输出2<br/>
3<br/>
1<br/>
<br/>
样例输出3<br/>
5<br/>
6</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p>对于100%的数据，2&lt;=N&lt;=10000，N-1&lt;=M&lt;=12000，Q=10000，1&lt;=x,y&lt;=N，1&lt;=t&lt;32768<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize9">Poetize9</a></p></div>

