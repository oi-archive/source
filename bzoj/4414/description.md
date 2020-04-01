
# Description

<div class="content"><div>神犇heheda最近得到了UOJ抱枕，蒟蒻yts1999想要玩。于是heheda给yts1999出了一道题：</div>
<div>一个长度为2n+2的整数数列 按照下式定义：</div>
<div>A0=0</div>
<div>A1=C</div>
<div>Ai+2=(Ai+1+Ai) Mod M (0&lt;=i&lt;=2*N)</div>
<div>现有n个平面向量v1…vn：</div>
<div>V1=(A2,A3),V2=(A4,A5)...Vn=(A2n,A2n+1)</div>
<div>集合S的定义如下：</div>
<div> <img width="380" height="48" alt="" src="/source/bzoj/4414/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8xMTEucG5n.png"/></div>
<div>其中&#34;vi•vj&#34;表示向量vi和vj的数量积。</div>
<div>求S集合中不同元素的个数是多少。答案对M取模。</div>
<div>heheda告诉yts1999，只要他做出了这道题，她就可以把抱枕借给他玩一会。然而yts1999实在是太弱了不会做，于是向你求助。</div>
<p></p></div>

# Input

<div class="content"><div>输入数据包含一行三个整数C,M和n，分别表示a1的值，模数和平面向量的个数，每两个数之间用一个空格隔开。</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数表示答案对M取模后的值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><div>数列为{0,4,4,3,2,0,2,2}，v1=(4,3),v2=(2,0),v3=(2,2)。</div><br/>
<div><span style="font-family: arial, verdana, helvetica, sans-serif; font-size: 18px; line-height: normal; background-color: rgb(228, 240, 248);">v1•v2 mod M=3</span>, v2•v3 mod M=4, v1•v3 mod M=4。</div><br/>
<div>对于100%的数据，1≤C≤10^9,1≤M≤10^9,1≤n≤3*10^5</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By yts1999">By yts1999</a></p></div>

