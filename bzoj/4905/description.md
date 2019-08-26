
# Description

<div class="content"><div>换一个角度看，世界可能就不同。—— 小强</div>
<div></div>
<div>k 维空间中有n 个黑点与n 个白点。我们为每一个黑点确定一个互不相同的对应的白点，这样一共有n! 种对应方</div>
<div>法。我们定义这n 个黑点与n 个白点之间的「移动距离」为，在所有的对应方法中，对应的黑点与白点之间的n 个</div>
<div>欧几里德距离的和的最小值。例如：考虑一维中的三个黑点 {1,5,6}与三个白点 {2,3,4}，那么它们之间的移动距</div>
<div>离为：∣1-2∣+∣5-3∣+∣6-4∣=4。你可以验证一下这确实是距离和最小的一种对应方法。你得到了三维空间中</div>
<div>的 n个黑点与 n个白点。你想把它们投影到一个 k(1≤k≤2)  维子空间上。一维子空间就是三维空间中的一条直</div>
<div>线，二维子空间则是三维空间中的一个平面。一个点在一个子空间中的投影点就是这个子空间中距离它最近的点。</div>
<div>例如，(0,0,0),(1,1,0),(1,0,0),(0,1,0)这四个点投影到 x?y=0,z=0这条直线上之后，得到的投影点是 (0,0,0),</div>
<div>(1,1,0),(0.5,0.5,0),(0.5,0.5,0)你希望这 n个黑点和 n个白点投影到这个 k维子空间之后的移动距离最大。请</div>
<div>你计算这个最大值除以 n。</div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>每个测试文件中可能有多个测试用例，每个测试用例的格式如下：</div>
<div>第一行两个数 n和 k，表示点数以及降到的维度。</div>
<div>后面2n 行，每行三个数，表示点的坐标。</div>
<div>最后有一行包含两个数 -1 -1。</div>
<div>对于 100% 的数据，点的坐标的范围都是 ?1到 +1之间的，答案不小于 0.01</div></div>

# Output

<div class="content"><div>输出一行一个数（长度不要超过 30），表示结果。</div>
<div>你的答案与参考答案的相对误差不超过 10^-7时被认为是正确的。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
0 0 0<br/>
1 1 0<br/>
0 1 0<br/>
1 0 0<br/>
-1 -1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.70710678118655<br/>
</span></div>

# Hint

<div class="content"><p></p><p>尚无SPJ,请不要提交.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

