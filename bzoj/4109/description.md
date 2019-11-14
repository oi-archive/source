
# Description

<div class="content"><div>给定一个100*100*100（单位：毫米）的奶酪方块，这个奶酪含有n个球形小孔。现在要求将这个奶酪切成s片使得每片质量相等。</div>
<div></div>
<p class="MsoNormal"></p></div>

# Input

<div class="content"><p>第一行包含两个整数n,s，表示奶酪有n个小空，要切成s片（0≤n≤10000，1≤s≤100）</p>
<div>接下来n行每行包含四个正整数r,x,y,z来描述每个小孔，r代表半径，(x,y,z)代表球心坐标。0≤r,x,y,z≤100,000（单位：微米）</div>
<div>我们假定切割必须垂直于z轴。对于小孔，孔与孔之间不会重叠（但可能相切），且每个孔都完全被奶酪包含（可能与奶酪边界相切）。</div>
<div></div></div>

# Output

<div class="content"><p>从边界z=0依次输出每片的厚度（单位：毫米），输出答案与标准答案的相对误差或绝对误差不超过1e-6。</p>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">1 1<br/>
50000 50000 50000 50000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">100.000000000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Phile提供译文,ccz181078提供SPJ">鸣谢Phile提供译文,ccz181078提供SPJ</a></p></div>

