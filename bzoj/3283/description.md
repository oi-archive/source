
# Description

<div class="content"><div>操作有<span>3种：</span></div>
<div><span style="font-size: 12pt"> </span></div>
<p><img height="112" alt="" width="629" src="source/bzoj/3283/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwOC8xMTEuanBn.jpg"/></p></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行一个正整数N，描述数据组数。</span></div>
<div><span style="font-size: medium">接下来的N行，每行4个正整数Sum，y，z，p。</span></div>
<div><span style="font-size: medium">Sum表述询问类型，如上题所述。对于第2种要求，若X不存在，则输出“Math Error”</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">要求有N行输出，每行一个整数，为询问的答案。</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 10 1000<br/>
2 3 1 1000<br/>
2 2 3 4 <br/>
3 2 7 9<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
0<br/>
Math Error <br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">操作1个数小于501。保证Y,Z,P小于10^9<br/><br/>
操作2个数小于51 保证Y,Z,P小于10^9 P不一定为质数<br/><br/>
操作3个数小于51 保证Y，Z小于10^9，P小于10^9<br/><br/>
P不一定为质数</span></p><br/>
<p><span style="color: #ff0000"><span style="font-size: medium">P&lt;=10^9<br/><br/>
假设分解质因数后,P=p1^s1*p2^s2*……保证pi^ki&lt;=10^5<br/><br/>
</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

