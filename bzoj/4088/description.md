
# Description

<div class="content"><div>小渊是个聪明的孩子，他经常会给周围的小朋友们讲些自己认为有趣的内容。最近，他准备给小朋友们讲解彩色水</div>
<div>平光源照射下的立体图，并请你帮他在平面上画出来。小渊有一块面积为m*n的矩形区域，上面有m*n个边长为1的</div>
<div>格子，每个格子上堆了一些同样大小的积木（积木的长宽高都是1）。为了方便阐述，我们假设这块区域是坐北朝</div>
<div>南的，下面我们给出一个例子。</div>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; font-family: sans-serif; line-height: 23px;"><img src="/source/bzoj/4088/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS8xLnBuZw==.png" width="740" height="520" alt=""/></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><span style="text-indent: 2em; line-height: 23px;"><font face="sans-serif" size="2">小渊想请你打印出这些格子的立体图。我们定义每个积木为如下格式，并且不会做任何翻转旋转，只会严格以这一</font></span></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><font face="sans-serif" size="2"><span style="line-height: 23px;">种形式摆放（左侧是应该打印出来的图样，右侧为对应每一个位置符号的十进制ASCII，其中ASCII为32的符号为空</span></font></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; font-family: sans-serif; line-height: 23px;"><img src="/source/bzoj/4088/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS8yLnBuZw==.png" width="740" height="266" alt=""/></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><span style="text-indent: 2em; line-height: 23px;"><font face="sans-serif" size="2">在良好的光学环境下，小渊将T束平行光同时照射在这些积木上。这些平行光首先满足一定是红绿蓝三基色之一，</font></span></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><font face="sans-serif" size="2"><span style="line-height: 23px;">其次入射角度满足：与x轴y轴的夹角度数均为45的倍数；且与z轴正方向的夹角或为45度，或为0度，或为315度。</span></font></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><font face="sans-serif" size="2"><span style="line-height: 23px;">具体来说，我们最多会考虑9个方向的不同平行光，它们的入射方向可以被描述为：</span></font></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><font face="sans-serif" size="2"><span style="line-height: 23px;">   西北方45度仰角  正北方45度仰角  东北方45度仰角</span></font></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><font face="sans-serif" size="2"><span style="line-height: 23px;">   正西方45度仰角  垂直从上入射光  正东方45度仰角</span></font></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><font face="sans-serif" size="2"><span style="line-height: 23px;">   西南方45度仰角  正南方45度仰角  东南方45度仰角</span></font></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"><font face="sans-serif" size="2"><span style="line-height: 23px;">对于每一个单位积木来说，可以打印出来的三个表面被分为12个小三角形，如下图所示（下图中用符号0,1,2,。。</span></font></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: baseline; text-indent: 2em;"></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; font-family: sans-serif; line-height: 23px;"><img src="/source/bzoj/4088/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS8zLnBuZw==.png" width="425" height="416" alt=""/></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; font-family: sans-serif; line-height: 23px;"><span style="font-family: Arial, Verdana, sans-serif; font-size: 12px;"> </span><span style="line-height: 23px; text-indent: 2em;">红绿蓝三基色分别用字母RGB来表示。</span></p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; font-family: sans-serif; line-height: 23px;">而二次叠加后的三种颜色青黄紫，分别用YCP来表示。</p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; font-family: sans-serif; line-height: 23px;">对于三次叠加后的颜色，也就是白色，用W来表示。</p>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; font-family: sans-serif; line-height: 23px;"></p></div>

# Input

<div class="content"><div>第一行有两个正整数m和n，表示区域有m行n列。之后m行，依次由远及近描述了每一行的情况。每一行给出n个正整</div>
<div>数，表示第i行第j列中有堆放了多少积木。之后3行，每行三个字符，描述了9个对应方向（与地图描述方向相同）</div>
<div>的光照颜色。其中每一个字符或者为RGB中之一，表示对应的颜色。或者为*，表示没有照射光。这九个方向依次是</div>
<div>：</div>
<div>   西北方45度仰角  正北方45度仰角  东北方45度仰角</div>
<div>   正西方45度仰角  垂直从上入射光  正东方45度仰角</div>
<div>   西南方45度仰角  正南方45度仰角  东南方45度仰角</div></div>

# Output

<div class="content"><div>输出给出了打印后的效果。其中要求输出结果不含前导空行，结尾也没有额外空行。输出的第一列不能全是空格，</div>
<div>且每一行末尾也没有额外空格。</div></div>

# Sample Input

<div class="content"><span class="sampledata">#1<br/>
2 2<br/>
2 1<br/>
1 1<br/>
R**<br/>
***<br/>
**G<br/>
<br/>
#2<br/>
3 4<br/>
1 1 2 1<br/>
1 2 1 2<br/>
2 1 2 1<br/>
**B<br/>
***<br/>
R*G<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">#1<br/>
        +-------+<br/>
       /Y\YYYY’/|<br/>
      /YY.*’YY/G|<br/>
     /.YYYY\Y/G/|<br/>
    +-------+G.G|<br/>
    |\GGGGG/|\:G|<br/>
    |G\GGG/G|G*G|<br/>
    |GG\G/GG|G:\|<br/>
    |GGGXGGG|G’G+-------+<br/>
    |GG/G\GG|/G/G\YYYY’/|<br/>
    |G/GGG\G|G/GG.*’YY/G|<br/>
    |/GGGGG\|/.GGGG\Y/G/|<br/>
    +-------+-------+G.G|<br/>
   /Y\GGGG’/G\GGGG’/|\:G|<br/>
  /YY.*’GG/GG.*’GG/G|G*G|<br/>
 /.YYYY\G/.GGGG\G/G/|G:\|<br/>
+-------+-------+G.G|G’G+<br/>
|\GGGGG/|\GGGGG/|\:G|/G/<br/>
|G\GGG/G|G\GGG/G|G*G|G/<br/>
|GG\G/GG|GG\G/GG|G:\|/<br/>
|GGGXGGG|GGGXGGG|G’G+<br/>
|GG/G\GG|GG/G\GG|/G/<br/>
|G/GGG\G|G/GGG\G|G/<br/>
|/GGGGG\|/GGGGG\|/<br/>
+-------+-------+<br/>
<br/>
#2<br/>
                    +-------+<br/>
                   /W\WWWW’/|<br/>
                  /WW.*’WW/C|<br/>
                 /.WWWW\W/C/|<br/>
        +-------+-------+-------+<br/>
       /W\WWWW’/|\YYYYY/W\WWWW’/|<br/>
      /WW.*’WW/C|G\YYY/WW.*’WW/C|<br/>
     /.WWWW\W/C/|GG\Y/.WWWW\W/C/|<br/>
    +-------+-------+-------+-------+C.C|---+<br/>
   /W\WWWW’/|\YYYYY/W\WWWW’/|\YYYYY/|\:C|C’/|<br/>
  /WW.*’WW/C|G\YYY/WW.*’WW/C|G\YYY/Y|C*C|C/C|<br/>
 /.WWWW\W/C/|GG\Y/.WWWW\W/C/|GG\Y/YY|C:\|/C/|<br/>
+-------+C.G|GGG+-------+C.G|GGGXYYY|C’C+C.C|<br/>
|\YYYYY/|\:G|GG/|\YYYYY/|\:G|GG/G\YY|/C/|\:C|<br/>
|Y\YYY/Y|C*G|G/K|Y\YYY/Y|C*G|G/GGG\Y|C/C|C*C|<br/>
|YY\Y/YY|C:\|/KK|YY\Y/YY|C:\|/GGGGG\|/C/|C:\|<br/>
|YYYXYYY|C’G+---|YYYXYYY|C&#39;G+-------+C.C|C’C+<br/>
|YY/Y\YY|/G/G\KK|YY/Y\YY|/G/G\GGGG’/|\:C|/C/<br/>
|Y/YYY\Y|G/GG.*’|Y/YYY\Y|G/GG.*’WW/C|C*C|C/<br/>
|/YYYYY\|/.YYYY\|/YYYYY\|/.WWWW\W/C/|C:\|/<br/>
+-------+-------+-------+-------+C.C|C’C+<br/>
|\YYYYY/|\YYYYY/|\YYYYY/|\YYYYY/|\:C|/C/<br/>
|Y\YYY/Y|Y\YYY/Y|Y\YYY/Y|Y\YYY/Y|C*C|C/<br/>
|YY\Y/YY|YY\Y/YY|YY\Y/YY|YY\Y/YY|C:\|/<br/>
|YYYXYYY|YYYXYYY|YYYXYYY|YYYXYYY|C’C+<br/>
|YY/Y\YY|YY/Y\YY|YY/Y\YY|YY/Y\YY|/C/<br/>
|Y/YYY\Y|Y/YYY\Y|Y/YYY\Y|Y/YYY\Y|C/<br/>
|/YYYYY\|/YYYYY\|/YYYYY\|/YYYYY\|/<br/>
+-------+-------+-------+-------+</span></div>

# Hint

<div class="content"><p></p><p> </p><br/>
<p><img src="/source/bzoj/4088/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS81LnBuZw==.png" width="456" height="300" alt=""/></p><br/>
<p><span style="background-color: transparent; font-family: sans-serif; font-size: 14px; line-height: 23px; text-indent: 2em;">对于15%的数据，1&lt;=n,m&lt;=100,没有入射光。</span></p><br/>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; background-color: transparent; text-indent: 2em; font-family: sans-serif; line-height: 23px;">对于40%的数据，1&lt;=n,m&lt;=100,入射光只有一束，且入射方向一定是东南方。</p><br/>
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; background-color: transparent; text-indent: 2em; font-family: sans-serif; line-height: 23px;">对于100%的数据，1&lt;=n,m&lt;=100，每一个位置堆放的积木总数不超过100,入射光颜色可能是RGB中的任何一种颜色，最多可以有9束入射光。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

