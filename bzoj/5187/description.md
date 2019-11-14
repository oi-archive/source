
# Description

<div class="content"><p> 农夫约翰有一块很大的田，他正在考虑种甜玉米。经过对他农田的调查，FJ发现它形成了一个（N-1）×（N-1）的</p>
<div>正方形。西南角为坐标（0,0），东北角是（N-1，N-1）。在某些整数坐标的位置中有双头喷头，每一个都能够同</div>
<div>时喷洒水和肥料。一个在（i，j）处的双头喷头会将水洒在农田中所有在其东面且在其北面的区域，将肥料洒在农</div>
<div>田中所有在其南面且在其西面的区域。形式化地说，这个喷头将会将水洒在所有满足N≥x≥i和N≥y≥j的实数坐标</div>
<div>(x,y)上，会将肥料洒在所有满足0≤x≤i和0≤y≤j的实数坐标上农民约翰想在一些边与坐标轴平行的长方形农田</div>
<div>里种植甜玉米。然而，为了甜玉米的生长，矩形内的所有点都必须由双头喷头浇水和施肥。当然，矩形必须有正的</div>
<div>面积，否则农民约翰就不能在里面种植任何玉米！帮助农民约翰确定可以种植甜玉米的拥有正面积的矩形农田数。</div>
<div>由于这个数字可能很大，所以输出对为10^9 + 7取模</div>
<div></div></div>

# Input

<div class="content"><p> 第一行包含一个整数N，表示农场的大小（1≤N≤10^5）。</p>
<div>接下来的n行各包含两个由空格分隔的整数。这些整数中0≤i，j≤N-1，这表示有一个双头喷头位于（i，j）的位置。</div>
<div>保证每列都有一台喷头，每排正好有一台喷头。这也就是说，没有两个喷头有相同的x坐标或y坐标。</div>
<div></div></div>

# Output

<div class="content"><p>输出包含一行，表示拥有正面积的合法矩形农田的个数，对10^9+7取模.</p>
<div></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
0 4<br/>
1 1<br/>
2 2<br/>
3 0<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">21</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum 鸣谢WenDavid提供翻译">Platinum 鸣谢WenDavid提供翻译</a></p></div>

