<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Orez很喜欢玩游戏，他最近发明了一款硬币游戏。他在桌子的边缘上划分出2*n个位置并按顺时针把它们标号为1，2，……，2n，然后把n个硬币放在标号为奇数的位置上。接下来每次按如下操作：在任意两个硬币之间放上一个硬币，然后将原来的硬币拿走；所放硬币的正反面由它两边的两个硬币决定，若两个硬币均为正面朝上或反面朝上，则所放硬币为正面朝上，否则为反面朝上。</p>
<p>那么操作T次之后桌子边缘上硬币的情况会是怎样的呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第一行包含两个整数n和T。</p>
<p>接下的一行包含n个整数，表示最开始桌面边缘的硬币摆放情况，第i个整数a<sub>i</sub>表示第i个硬币摆放在2*i-1个位置上，a<sub>i</sub>=1表示正面朝上，a<sub>i</sub>=2表示反面朝上。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件仅包含一行，为2n个整数，其中第i个整数b<sub>i</sub>桌面边缘的第i个位置上硬币的情况，b<sub>i</sub>=1表示正面朝上，b<sub>i</sub>=2表示反面朝上，b<sub>i</sub>=0表示没有硬币。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 5</p>
<p>2 2 2 1 1 1 1 1 1 2</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0 1 0 1 0 1 0 1 0 2 0 1 0 2 0 1 0 1 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据  n≤1000  T≤1000</p>
<p>100%的数据  n≤100000  T≤2<sup>60</sup></p>
</div>
</div>