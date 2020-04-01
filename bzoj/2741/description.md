
# Description

<div class="content"><div><span style="font-size: medium">FOTILE得到了一个长为N的序列A，为了拯救地球，他希望知道某些区间内的最大的连续XOR和。</span></div>
<div><span style="font-size: medium">即对于一个询问，你需要求出max(Ai xor Ai+1 xor Ai+2 ... xor Aj)，其中l&lt;=i&lt;=j&lt;=r。</span></div>
<div><span style="font-size: medium">为了体现在线操作，对于一个询问(x,y)：</span></div>
<div><span style="font-size: medium"><span style="color: rgb(0,0,32); line-height: normal; font-family: monospace; background-color: rgb(246,249,224); text-align: justify">l = min ( </span><span style="color: rgb(0,0,32); line-height: normal; font-family: monospace; background-color: rgb(246,249,224); text-align: justify">((x+lastans) mod N)+1 , ((y+lastans) mod N)+1 </span><span style="color: rgb(0,0,32); line-height: normal; font-family: monospace; background-color: rgb(246,249,224); text-align: justify">).<br/>
r = max ( ((x+lastans) mod N)+1 , ((y+lastans) mod N)+1 ).</span></span></div>
<div style="text-align: justify"><span style="font-size: medium"><font face="monospace" color="#000020"><span style="line-height: normal">其中lastans是上次询问的答案，一开始为0。</span></font></span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行两个整数N和M。</span></div>
<div><span style="font-size: medium">第二行有N个正整数，其中第i个数为Ai，有多余空格。</span></div>
<div><span style="font-size: medium">后M行每行两个数x,y表示一对询问。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div></div></div>

# Output

<div class="content"><div>
<h2 style="color: blue; line-height: normal; font-family: arial, verdana, helvetica, sans-serif"> </h2>
</div>
<div><span style="font-size: medium">共M行，第i行一个正整数表示第i个询问的结果。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 4 3<br/>
0 1<br/>
0 1<br/>
4 3<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
7<br/>
7</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
HINT<br/><br/>
N=12000，M=6000，x,y,Ai在signed longint范围内。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By seter">By seter</a></p></div>

