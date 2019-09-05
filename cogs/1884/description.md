# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
在Counter Strike（反恐精英）的cs_assault地图里有这样的场景：<br/>
<img src="/upload/image/20141217/20141217082522_31066.png" alt=""/><br/>
图中的管道是外界进入这个仓库的路径之一。但是这条管道十分狭窄，遭枪击时根本无处躲避。于是gx就拿了一把枪守在管道的这一端，一旦对面出现敌人就马上开枪。导致试图从此处进入的敌人无一幸免。<br/>
对方纷纷表示用这种方式防守太无聊了，他们对这个管道进行了一些修改。我们用三维直角坐标系描述这个管道，如下图所示：<br/>
<img src="/upload/image/20141217/20141217082641_34088.png" alt=""/><br/>
<br/>
1.管道从y轴负方向延伸到y轴正方向。<br/>
2.称x轴负方向为左边，x轴正方向为右边，z轴正方向为上边，z轴负方向为下边。<br/>
3.管道是由若干四棱柱拼接而成，每个四棱柱的两个底面都是边长为1的正方形，且这两个底面都平行于xoz平面。也就是说，对于管道的任何一个垂直于y轴的的截面，它都是正方形，只要知道右上角顶点的坐标(x,y,z)就可以知道正方形剩下三个点的坐标(x-1,y,z), (x,y,z-1), (x-1,y,z-1)。<br/>
4.知道了管道右上方的折线，通过向左平移1、再向下平移1、再向右平移1，再向上平移1，可以得到该管道的边界。所以给出管道右上方的折线的每个顶点的坐标，我们就可以确定整个管道的形状。<br/>
<br/>
对于gx的枪，有如下说明:<br/>
1.gx的枪沿一条直线射出一颗子弹。我们把子弹视作是一个半径为r的圆，所以轨迹可以视作一个底面半径为r的狭长圆柱。对于某个y=y0的截面，如果子弹能够完整地通过，称此处是被gx控制的。反之，子弹在接触目标前会发生偏折，因此该截面是不被控制的。子弹刚好擦边而过的情况也算作可以通过。<br/>
2.gx站在y轴负方向的那一端，面向y轴正方向。gx的枪可以在管道外任何位置以任何角度，从y轴负方向向y轴正方向进行瞄准。<br/>
<br/>
现在面对这个蜿蜒曲折的管道，gx想知道他能控制的最远截面的y坐标值是多少。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含整数n和实数r。<br/>
接下来n行每行三个实数，第i行的三个实数表示第i个正方形右上角顶点的坐标(x, y, z)。输入保证y坐标值是严格递增的。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个实数，表示最远的控制点。保留三位小数。数据保证gx的子弹不能贯穿整个管道。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
5 0<br/>
0.0 -2.0 1.0<br/>
0.0 0.0 1.0<br/>
1.0 1.0 0.0<br/>
0.0 1.5 1.0<br/>
2.0 3.0 0.0
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
2.250
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
沿y轴正方向，最远可以控制到y=2.250<br/>
（图示见问题描述）
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3 0.2<br/>
0.0 0.0 1.0<br/>
0.0 1.0 1.0<br/>
2.0 2.0 -1.0
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
1.374
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于10%的数据 n=3<br/>
对于50%的数据 n≤500<br/>
对于100%的数据 3≤n≤20000, 0≤r≤0.5, -100000≤x<sub>i</sub>, y<sub>i</sub>, z<sub>i</sub>≤100000<br/>
均匀分布着50%的数据 r=0
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【问题描述】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Counter Strike</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">（反恐精英）的</span><span style="mso-fareast-font-family:&#39;Lingoes Unicode&#39;;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">cs_assault</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">地图里有这样的场景：</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><v:shapetype id="_x0000_t75" coordsize="21600,21600" o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f" stroked="f"><v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"></v:path><o:lock v:ext="edit" aspectratio="t"></o:lock></v:shapetype><span style="mso-spacerun:yes;"><span style="font-size:small;font-family:&#39;Times New Roman&#39;;"> <img width="512" height="198" alt="" src="/RequireFile.do?fid=HgqRQ4ab"/></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">图中的管道是外界进入这个仓库的路径之一。但是这条管道十分狭窄，遭枪击时根本无处躲避。于是</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">就拿了一把枪守在管道的这一端，一旦对面出现敌人就马上开枪。导致试图从此处进入的敌人无一幸免。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">对方纷纷表示用这种方式防守太无聊了，他们对这个管道进行了一些修改。我们用三维直角坐标系描述这个管道，如下图所示：</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;"><img width="360" height="242" alt="" src="/RequireFile.do?fid=nHmq87B4"/></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1.</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">管道从</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴负方向延伸到</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴正方向。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2.</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">称</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">x</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴负方向为左边，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">x</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴正方向为右边，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">z</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴正方向为上边，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">z</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴负方向为下边。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">3.</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">管道是由若干四棱柱拼接而成，每个四棱柱的两个底面都是边长为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的正方形，且这两个底面都平行于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">xoz</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">平面。也就是说，对于管道的任何一个垂直于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴的的截面，它都是正方形，只要知道右上角顶点的坐标</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(x,y,z)</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">就可以知道正方形剩下三个点的坐标</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(x-1,y,z), (x,y,z-1), (x-1,y,z-1)</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">4.</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">知道了管道右上方的折线，通过向左平移</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">、再向下平移</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">、再向右平移</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，再向上平移</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，可以得到该管道的边界。所以给出管道右上方的折线的每个顶点的坐标，我们就可以确定整个管道的形状。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><o:p><span style="font-size:small;font-family:&#39;Times New Roman&#39;;"> </span></o:p></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的枪，有如下说明</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">:</span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1.gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的枪沿一条直线射出一颗子弹。我们把子弹视作是一个半径为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">r</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的圆，所以轨迹可以视作一个底面半径为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">r</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的狭长圆柱。对于某个</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y=y0</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的截面，如果子弹能够完整地通过，称此处是被</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">控制的。反之，子弹在接触目标前会发生偏折，因此该截面是不被控制的。子弹刚好擦边而过的情况也算作可以通过。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2.gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">站在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴负方向的那一端，面向</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴正方向。</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的枪可以在管道外任何位置以任何角度，从</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴负方向向</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴正方向进行瞄准。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><o:p><span style="font-size:small;font-family:&#39;Times New Roman&#39;;"> </span></o:p></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">现在面对这个蜿蜒曲折的管道，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">想知道他能控制的最远截面的</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">坐标值是多少。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【输入格式】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输入的第一行包含整数</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和实数</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">r</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">接下来</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行每行三个实数，第</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行的三个实数表示第</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个正方形右上角顶点的坐标</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(<i style="mso-bidi-font-style:normal;">x</i>, <i style="mso-bidi-font-style:normal;">y</i>, <i style="mso-bidi-font-style:normal;">z</i>)</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。输入保证</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">坐标值是严格递增的。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【输出格式】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输出一个实数，表示最远的控制点。保留三位小数。数据保证</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的子弹不能贯穿整个管道。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输入</span><span lang="EN-US">1</span><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">】</span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">5 0</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">0.0 -2.0 1.0</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">0.0 0.0 1.0</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">1.0 1.0 0.0</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">0.0 1.5 1.0</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">2.0 3.0 0.0</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输出</span><span lang="EN-US">1</span><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">】</span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">2.250</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例说明</span><span lang="EN-US">1</span><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">】</span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">沿</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">轴正方向，最远可以控制到</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span lang="EN-US">y</span></i><span lang="EN-US">=2.250</span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">（图示见问题描述）</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输入</span><span lang="EN-US">2</span><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">】</span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="mso-font-kerning:0pt;mso-ansi-language:ZH-CN;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">3 0.2<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="mso-font-kerning:0pt;mso-ansi-language:ZH-CN;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">0.0 0.0 1.0<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="mso-font-kerning:0pt;mso-ansi-language:ZH-CN;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">0.0 1.0 1.0<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="mso-font-kerning:0pt;mso-ansi-language:ZH-CN;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">2.0 2.0 -1.0<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输出</span><span lang="EN-US">2</span><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">】</span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">1.374</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【数据范围】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">对于</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US">10%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US"> n=3<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">对于</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US">50%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US"> n≤500<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">对于</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US">100%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US"> 3≤n≤20000, 0≤r≤0.5, -100000≤<i style="mso-bidi-font-style:normal;">x<sub>i</sub></i>, <i style="mso-bidi-font-style:normal;">y<sub>i</sub></i>, <i style="mso-bidi-font-style:normal;">z<sub>i</sub></i>≤100000<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">均匀分布着</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US">50%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US"> r=0<o:p></o:p></span></span> 
</p>
</div>
</div>
