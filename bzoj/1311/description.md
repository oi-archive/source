
# Description

<div class="content"><img border="0" src="/source/bzoj/1311/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEzMTEuanBn.jpg"/>

其中:
Auv是与Aij相邻的像素(为了简化,认为(i-1,j),(i+1,j,(i,j-1),(i,j+1)为相邻元素);
Wij取值0或者1,表示Aij修改后取V0或者V1.
E的定义直观上的理解是,当修改了A之后,各像素上的值与原来的值相差了多少,以及相邻的像素对比程度的变化.为了图像的保真度,我们希望E的值越小越好.

</div>

# Input

<div class="content">第一行二个整数N,M(1&lt;=N,M&lt;=35)
第二行二个整数V0,V1
接下来N行M列,对应矩阵元素Aij

</div>

# Output

<div class="content">一个数E,表示最小可能的估价值
</div>

# Sample Input

<div class="content"><span class="sampledata">1 2<br/>
0 255<br/>
10 20<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">30</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

