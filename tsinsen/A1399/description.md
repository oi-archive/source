<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Victor和Peter在玩捉迷藏。Peter躲了起来，Victor要找他。在他们玩游戏的房间里，只有一堵不透明的墙和一个双面的镜子。Victor和Peter可以看作平面上坐标分别为(Xv,Yv)和(Xp,Yp)的点。墙是一条连接(Xw1,Yw1)和(Xw2,Yw2)的线段，镜子是一条连接(Xm1,Ym1)和(Xm2,Ym2)的线段。<br/>
　　如果视线和障碍物有公共点，那么我们认为视线会被阻挡，无法看见。如果视线和镜子有公共点，那么我们认为发生了反射。反射的过程遵循物理规律——入射角等于反射角，且反射光线与入射光线在镜子同侧。也就是说，想要看见对方，Victor和Peter必须在镜子的同一侧，包括镜子所在直线上（参见样例1）。如果视线与镜子重合，那么不会发生反射，并且镜子不被当作障碍物（参见样例4）。<br/>
　　Victor很想知道他站在原地能否看见Peter，帮助他解决这个问题。</div>
# 输入格式

<div class="pdcont">　　第一行两个数Xv,Yv，表示Victor的坐标。<br/>
　　第二行两个数Xp,Yp，表示Peter的坐标。<br/>
　　第三行四个数Xw1,Yw1,Xw2,Yw2，分别表示墙的两个端点的坐标。<br/>
　　第四行四个数Xm1,Ym1,Xm2,Ym2，分别表示镜子的两个端点的坐标。</div>
# 输出格式

<div class="pdcont">　　如果Victor站在原地能看到Peter，则输出&#34;YES&#34;，否则输出&#34;NO&#34;。</div>
# 样例输入一

<div class="pdcont">　　-1 3<br/>
　　1 3<br/>
　　0 2 0 4<br/>
　　0 0 0 1</div>
# 样例输出一

<div class="pdcont">　　NO</div>
# 样例输入二

<div class="pdcont">　　0 0<br/>
　　1 1<br/>
　　0 1 1 0<br/>
　　-100 -100 -101 -101</div>
# 样例输出二

<div class="pdcont">　　NO</div>
# 样例输入三

<div class="pdcont">　　0 0<br/>
　　1 1<br/>
　　0 1 1 0<br/>
　　-1 1 1 3</div>
# 样例输出三

<div class="pdcont">　　YES</div>
# 样例输入四

<div class="pdcont">　　0 0<br/>
　　10 0<br/>
　　100 100 101 101<br/>
　　1 0 3 0</div>
# 样例输出四

<div class="pdcont">　　YES</div>
# 数据规模和约定

<div class="pdcont">　　所有坐标均为绝对值不超过10^4的整数。输入的线段不会退化成点，且两条线段没有交点。Victor和Peter的位置不同，且不在任何一条线段上。</div>

</div>