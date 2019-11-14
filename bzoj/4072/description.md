
# Description

<div class="content"><p> 给定一排长度为4n的格子，编号从-2n+1到2n</p>
<div>每个编号为正的格子中有一个物品，其中每个编号为奇数的格子中有一个B类物品，编号为偶数的格子中有一个A类物品</div>
<div>例如：当n=4时初始状态如下图所示：</div>
<div><img src="/source/bzoj/4072/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS_pmYTlm74ucG5n.png" width="960" height="100" alt=""/></div>
<div>你只能进行一种操作：选择某两个相邻的格子，要求这两个格子中都有物品，然后移动到另外两个相邻的空格子中，不能改变两个格子的相对位置</div>
<div>要求进行最少的操作使得所有物品以AAA...ABBB...B(n个A和n个B)的形式排列在一起</div>
<div></div></div>

# Input

<div class="content"><p>输入数据包含一行一个正整数n，含义如题面中所示</p>
<div></div></div>

# Output

<div class="content"><p>输出一个最短的满足要求的移动序列</p>
<div>
<div>每个操作的格式如下：</div>
<div>x to y</div>
<div>含义为将x和x+1两个格子中的物品移动到y和y+1两个位置</div>
<div>如果有多组方案可以达到要求，你可以输出任意一组。</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 to -1<br/>
3 to 8<br/>
6 to 3<br/>
0 to 6<br/>
9 to 0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢wangtianyi1998提供SPJ及题面">鸣谢wangtianyi1998提供SPJ及题面</a></p></div>

