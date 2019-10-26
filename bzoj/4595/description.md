
# Description

<div class="content"><div>曾经发明了超能粒子炮·改的发明家SHTSC又公开了他的新发明：激光发生器--一种可以产生高能激光的神秘装置</div>
<div>。激光发生器从正上方看是一个无穷大的平面，里面由一个定向激光发射装置和若干个激光偏转装置组成。一个激</div>
<div>光发生器的示例如图所示，细箭头表示定向激光发射装置，粗线段表示激光偏转装置。</div>
<div><img src="/source/bzoj/4595/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS_ml6DmoIfpopgoMSkucG5n.png" width="279" height="268" alt=""/></div>
<div>由定向激光发射装置发射出的激光可以看成是一条射线，如果遇到激光偏转装置就会发生偏转。奇特的是，SHTSC</div>
<div>所使用的激光偏转装置并非像传统的镜子那样遵循反射定律，而是对于每个激光偏转装置，有一个固定的偏转系数</div>
<div>λ，其出射角β与入射角α的关系为β=λα，并且能在这一过程中增强激光的能量。（入射角是入射光线和反射</div>
<div>平面法向量的夹角。）注意：1、偏转装置的两面均可偏转。2、如果激光平行射入偏转装置，则认为没有发生偏转</div>
<div>。3、如果不平行且照射到了端点则认为发生偏转。4、可能会偏转到另一面。</div>
<div><img src="/source/bzoj/4595/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS92MSgxKS5wbmc=.png" width="219" height="159" alt=""/></div>
<div>现在SHTSC希望你模拟他所设计的激光发生器的工作过程，来帮助他计算激光究竟被哪些激光偏转装置所偏转。</div>
<p></p></div>

# Input

<div class="content"><div>第一行四个整数x，y，dx，dy。表示定向激光发射装置的位置是(x,y)，方向是(dx,dy)。</div>
<div>第二行一个整数n，表示一共有n个激光偏转装置。</div>
<div>以下n行，每行五个整数x1，y1，x2，y2，a，b表示一个激光偏转装置是(x1,y1)到(x2,y2)的一条线段</div>
<div>其偏转系数λ=a/b。</div>
<div>n&lt;=100，所有坐标与a和b的绝对值不超过1000，a、b均非0。保证所有的偏转装置没有交点。激光发射起始点不在</div>
<div>任何偏转装置上。方向向量不为零向量</div>
<p></p></div>

# Output

<div class="content"><div>一行由空格隔开的若干个整数，表示激光依次照射到的激光偏转装置的编号（按照输入顺序从1到n编号）。如果激</div>
<div>光被偏转超过10次，则只需输出前10次所照射到的偏转装置的编号。特别地，如果激光没有被任何一个偏转装置所</div>
<div>偏转，输出NONE。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">0 2 1 0<br/>
2<br/>
0 4 3 1 1 1<br/>
4 0 0 -4 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4595/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS92My5wbmc=.png" width="217" height="295" alt=""/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

