
# Description

<div class="content"><div>在平面直角坐标系中，Wayne需要你完成n次操作，操作只有两种：</div>
<div>1.0 x y。表示在坐标系中加入一个以(x, y)为圆心且过原点的圆。</div>
<div>2.1 x y。表示询问点(x, y)是否在所有已加入的圆的内部（含圆周），且至少在一个圆内部（含圆周）。</div>
<div>为了减少你的工作量，题目保证圆心严格在x轴上方（纵坐标为正），且横坐标非零。</div>
<div></div>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><div>第1行一个整数n。</div>
<div>接下来n行，每行第一个数是0或1，分别表示两种操作。</div>
<div>接着有两个实数x和y，具体意义见题面。注意询问进行了加密，x和y需要加上之前回答Yes的数量得到真正的询问。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问操作，如果点在所有已加入的圆内（或圆周上），则输出“Yes”（不含引号）；否则输出“No”（不含引号）。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
0 2.000000 3.000000<br/>
0 4.000000 1.000000<br/>
1 1.000000 1.000000<br/>
0 -4.000000 1.000000<br/>
1 0.000000 0.000000</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No</span></div>

# Hint

<div class="content"><p></p><p><span style="color: rgb(255, 0, 0);"> <span style="font-family: arial, verdana, helvetica, sans-serif;">“注意询问进行了加密，x和y需要加上之前回答Yes的数量得到真正的询问。”</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢talw001上传">鸣谢talw001上传</a></p></div>

