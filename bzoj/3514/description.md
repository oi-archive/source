
# Description

<div class="content"><p><span style="font-size: medium">N个点M条边的无向图，询问保留图中编号在[l,r]的边的时候图中的联通块个数。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行四个整数N、M、K、type，代表点数、边数、询问数以及询问是否加密。<br/>
接下来M行，代表图中的每条边。<br/>
接下来K行，每行两个整数L、R代表一组询问。对于type=0的测试点，读入的L和R即为询问的L、R；对于type=1的测试点，每组询问的L、R应为L xor lastans和R xor lastans。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4"> K行每行一个整数代表该组询问的联通块个数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 4 0<br/>
1 3<br/>
1 2<br/>
2 1<br/>
3 2<br/>
2 2<br/>
2 3<br/>
1 5<br/>
5 5<br/>
1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
3<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1≤N、M、K≤200,000。</p><br/>
<p>2016.2.26提高时限至60s</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By  zhonghaoxi">By  zhonghaoxi</a></p></div>

