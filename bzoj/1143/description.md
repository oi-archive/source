
# Description

<div class="content"><div>　　在遥远的东方，有一个神秘的民族，自称Y族。他们世代居住在水面上，奉龙王为神。每逢重大庆典， Y族都</div>
<div>会在水面上举办盛大的祭祀活动。我们可以把Y族居住地水系看成一个由岔口和河道组成的网络。每条河道连接着</div>
<div>两个岔口，并且水在河道内按照一个固定的方向流动。显然，水系中不会有环流（下图描述一个环流的例子）。</div>
<p><img alt="" border="0" src="/source/bzoj/1143/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNDMuanBn.jpg"/> </p>
<div>　　由于人数众多的原因，Y族的祭祀活动会在多个岔口上同时举行。出于对龙王的尊重，这些祭祀地点的选择必</div>
<div>须非常慎重。准确地说，Y族人认为，如果水流可以从一个祭祀点流到另外一个祭祀点，那么祭祀就会失去它神圣</div>
<div>的意义。族长希望在保持祭祀神圣性的基础上，选择尽可能多的祭祀的地点。</div></div>

# Input

<div class="content"><div>
<div>第一行包含两个用空格隔开的整数N、M，分别表示岔口和河道的数目，岔口从1到N编号。</div>
<div>接下来M行，每行包含两个用空格隔开的整数u、v，</div>
<div>描述一条连接岔口u和岔口v的河道，水流方向为自u向v。</div>
<div>N≤100M≤1000</div>
</div></div>

# Output

<div class="content"><p>第一行包含一个整数K，表示最多能选取的祭祀点的个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2<br/>
3 4<br/>
3 2<br/>
4 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
【样例说明】<br/>
在样例给出的水系中，不存在一种方法能够选择三个或者三个以上的祭祀点。包含两个祭祀点的测试点的方案有两种：<br/>
选择岔口1与岔口3（如样例输出第二行），选择岔口1与岔口4。<br/>
水流可以从任意岔口流至岔口2。如果在岔口2建立祭祀点，那么任意其他岔口都不能建立祭祀点<br/>
但是在最优的一种祭祀点的选取方案中我们可以建立两个祭祀点，所以岔口2不能建立祭祀点。对于其他岔口<br/>
至少存在一个最优方案选择该岔口为祭祀点，所以输出为1011。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

