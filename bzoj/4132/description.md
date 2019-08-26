
# Description

<div class="content"><div>在一次莫名其妙的意外中，人类舰队成功的掌握了高维打击，并且靠着高维打击打败了三体舰队飞船——“雨滴”。</div>
<div>但是人类由于当时情况紧急，并没有完整的了解高维打击的原理，打击也不是很精确，为了能够掌握每次是否有效的打击到了“雨滴”，我们对模型做如下抽象：</div>
<div>将雨滴当做一个三维空间中由若干个点构成的凸多面体，每次打击坐标为(x,y,z)，如果这个点在凸多面体的内部或者表面，则认为这次打击是成功的，现在给你若干个打击坐标，要求你计算打击是否成功。</div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含一个整数N，表示凸多面体由这N个点构成，不保证这N个点都在凸多面体的表面。</div>
<div>接下来N行，每行三个整数 (x,y,z)，代表点的xyz坐标。</div>
<div>接下来一行一个整数M，代表M次打击询问。</div>
<div>接下来M行，每行三个整数(x,y,z)，代表打击点的xyz坐标。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组询问，打击成功输出1，打击失败输出0</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
4<br/>
0 0 0<br/>
2 0 0<br/>
0 2 0	<br/>
0 0 2<br/>
3<br/>
0 0 0<br/>
2 2 2<br/>
0 1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>对于100%的测试数据，n ≤ 50000，m ≤ 100000，所有坐标都是绝对值不超过104的整数，保证数据有梯度；</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

