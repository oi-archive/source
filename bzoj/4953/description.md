
# Description

<div class="content"><div>数字图像的像素可以用三个在0到255之间的整数表示,它们分别表示红色、绿色和蓝色的强度。为了压缩图片或是</div>
<div>为了产生艺术效果,许多图像编辑工具收录了如下所述的&#34;色调分离&#34;操作。每个颜色通道会分别考虑,本题只考虑红</div>
<div>色通道的情况。不同于在红色通道使用0到255之间全部的整数,一张色调分离后的图片只会使用这些数字里至多 k </div>
<div>种整数。每个像素原来的红色强度会被替换成最相近的可用强度。图像编辑工具会选择k个整数来最小化替换过程</div>
<div>引起的平方误差之和。假设原图有n个像素,它们的红色取值是r1,···,rn,而 k 种可用整数为v1,···,vk ,那</div>
<div>么平方误差之和被定义为</div>
<div><img src="/source/bzoj/4953/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOC80NC5wbmc=.png" width="267" height="120" alt=""/></div>
<div>你的任务是计算可以实现的最小平方误差之和,参数k和图片的红色强度会给出。</div></div>

# Input

<div class="content"><div>第一行包含两个整数d(1≤d≤256)和k(1≤k≤d)</div>
<div>分别表示原图中不同的红色强度有多少种,色调分离后可以使用的红色强度有多少种。</div>
<div>接下来d行描述了每种红色强度在原图中占据的像素点数量。</div>
<div>每行包含两个整数r(0≤r≤255)和p(1≤p≤226)</div>
<div>这里r是一种红色强度的取值,而p是这种取值对应的像素点数量。这d行信息按照红色强度取值升序给出。</div></div>

# Output

<div class="content"><div>输出最优的 k 种可选取值对应的平方误差之和。</div></div>

# Sample Input

<div class="content"><span class="sampledata">样例1<br/>
2 1<br/>
50 20000<br/>
150 10000<br/>
样例2<br/>
2 2<br/>
50 20000<br/>
150 10000<br/>
样例3<br/>
4 2<br/>
0 30000<br/>
25 30000<br/>
50 30000<br/>
255 30000</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例1<br/>
66670000<br/>
样例2<br/>
0<br/>
样例3<br/>
37500000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供翻译">鸣谢Tangjz提供翻译</a></p></div>

