# 题面



<div class="pdcont"><b>【问题描述】</b><br/>
　　给定三次函数f(x)=ax<sup>3</sup>+bx<sup>2</sup>+cx+d的4个系数a，b，c，d，以及一个数z，请用牛顿迭代法求出函数f(x)=0在z附近的根，并给出迭代所需要次数。<br/>
　　牛顿迭代法的原理如下（参考下图）：<br/>
　　设x<sub>k</sub>是方程f(x)=0的精确解x*附近的一个猜测解，过点P<sub>k</sub>(x<sub>k</sub>,f(x<sub>k</sub>))作f(x)的切线。该切线与x轴的交点比x<sub>k</sub>更接近方程的精确解程x*。<br/>
　　迭代公式为：x<sub>k+1</sub>= x<sub>k</sub> - f(x<sub>k</sub>)/f &#39;(x<sub>k</sub>)，当f(x)的绝对值足够小的时候即可结束迭代。<br/>
　　注意：对于本题给定函数f(x)，f &#39;(x)=3ax<sup>2</sup>+2bx+c，且当|f(x)| ≤10<sup>-7</sup>时，即可认为x是f(x)=0的根。<br/>
<img width="229" height="185" src="source/tsinsen/A1094/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NVlqajRGNUc=.do"/><br/>
<br/>
<b>【输入格式】</b><br/>
　　输入共2行。<br/>
　　第一行为4个整数，每2个数之间用一个空格隔开，分别是a，b，c，d<br/>
　　第二行为一个实数z。<br/>
<b>【输出格式】</b><b></b><br/>
　　共一行。包含2个数，之间用一个空格隔开，第一个数是实数x，表示所求的根，精确到小数点后3位；第二个数是一个整数n，表示求得上述根需要的迭代次数。<br/>
<b>【样例输入】</b><b></b><br/>
　　2 -9 5 3<br/>
　　3<br/>
<b> </b><br/>
<b>【样例输出】</b><b></b><br/>
　　3.719 7<br/>
<br/>
<b>【提示】</b><b></b><br/>
　　程序中需要使用浮点数时，请用double类型</div>



