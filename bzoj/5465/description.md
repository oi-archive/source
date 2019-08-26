
# Description

<div class="content"><div>在平面上，有 n 个圆，记为 c_1, c_2, \ldots, c_n 。我们尝试对这些圆运行这个算法：  </div>
<div>1. 找到这些圆中半径最大的。如果有多个半径最大的圆，选择编号最小的。记为 c_i 。  </div>
<div>2. 删除 ci 及与其有交集的所有圆。两个圆有交集当且仅当平面上存在一个点，这个点同时在这两个圆的圆周上或圆内。</div>
<div>（如果平面上存在一个点被这两个圆所包含，我们称这两个圆有交集。一个点被一个圆包含当且仅当它位于圆内或圆周上。）  </div>
<div>3. 重复上面两个步骤直到所有的圆都被删除。</div>
<div> <img src="source/bzoj/5465/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgxMS92djEuanBn.jpg" width="391" height="392" alt=""/></div>
<div>当 ci 被删除时，若循环中第1步选择的圆是 cj ，我们说 ci 被 cj 删除。对于每个圆，求出它是被哪一个圆删除的。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数n，表示开始时平面上圆的数量，</div>
<div>接下来n行，每行包含三个整数xi,yi,ri，描述圆ci圆心的xy坐标和它的半径。</div>
<div>-1e9&lt;=xi,yi&lt;=1e9, 1&lt;=ri&lt;=1e9</div>
<div>1&lt;=n&lt;=3e5</div>
<p></p></div>

# Output

<div class="content"><div>输出一行，包含n个整数a1,a2,…,an，其中a_i表示圆c_i是被圆c_ai删除的。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">11<br/>
9 9 2<br/>
13 2 1<br/>
11 8 2<br/>
3 3 2<br/>
3 12 1<br/>
12 14 1<br/>
9 8 5<br/>
2 8 2<br/>
5 2 1<br/>
14 4 2<br/>
14 14 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">7 2 7 4 5 6 7 7 4 7 6<br/>
//题目描述中的图片对应了样例中的情形。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Qingyu上传">鸣谢Qingyu上传</a></p></div>

