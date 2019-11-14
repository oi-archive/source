
# Description

<div class="content"><p><span style="font-size: medium"> 给出n个正整数X1,X2,...Xn，可以进行不超过m次操作，每次操作选择一个非零的Xi，并将它减一。</span></p>
<div><span style="font-size: medium">最终要求存在某个k满足Xk=0，并且z=max{|Xi - Xi+1|}最小。</span></div>
<div><span style="font-size: medium">输出最小的z和此时最小的k。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div><font size="3"><br/>
</font></div>
<div></div></div>

# Input

<div class="content"><p> </p>
<div>
<div><span style="font-size: medium">第一行两个正整数n, m (1&lt;=n&lt;=1,000,000, 1&lt;=m&lt;=10^18)。第二行n个正整数X1,X2,...Xn (Xi&lt;=10^9)。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div><font size="3"><br/>
</font></div>
<div></div>
</div></div>

# Output

<div class="content"><p> </p>
<div>
<div><span style="font-size: medium">输出k和z。数据保证方案一定存在。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div><font size="3"><br/>
</font></div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">16 15<br/>
8 7 6 5 5 5 5 5 6 6 7 8 9 7 5 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 将X序列变为</p><br/>
<div>0 2 4 5 5 5 5 5 6 6 7 8 9 7 5 5</div><br/>
<div></div><br/>
<div>此时k=1，z=2，共操作了8+5+2=15次。</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 oimaster">鸣谢 oimaster</a></p></div>

