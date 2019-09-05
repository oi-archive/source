# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span style="font-size:32px;"><br/>
</span> 
</p>
<p>
<span style="font-size:32px;">【题目1402原题】</span> 
</p>
<p>
<br/>
</p>
<p>
   古希腊的大哲学家毕达哥拉斯(Pythagoras)很早就注意到数学与大千世界的联系，对数学科学的发展有着功不可没的贡献。他还创立了古希腊影响最深远的学派之一—毕达哥拉斯学派。毕达哥拉斯学派对数字的认识达到了审美的高度。他们相信，在这个世界中&#34;万物皆数&#34;，所有事物都可以用整数和整数之比来描述。
</p>
<p>
   然而，毕达哥拉斯学派有一位叫做希帕索斯(Hippasus)的学者发现，边长为1的正方形的对角线长度不能用整数比来表示。这一惊人的发现使他被扔进的大海。
</p>
<p>
<img alt="" src="/upload/image/20131115/20131115132455_58237.gif"/> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
   为了探索这些奇妙的数字。CH同学需要一个计算精度极高的程序来计算无理数的近似值。
</p>
<p>
   CH同学决定从他接触的第一个无理数开始研究—π。
</p>
<p>
计算π的方法多种多样，CH同学为你提供了一些参考方案：
</p>
<img alt="" src="/upload/image/20130929/20130929012810_56020.png"/> 
<p>
<br/>
</p>
<p>
<img alt="" src="/upload/image/20130929/20130929012930_40685.png"/> 
</p>
<p>
<img alt="" src="/upload/image/20130929/20130929012955_97664.png"/> 
</p>
<p>
<img alt="" src="/upload/image/20130929/20130929013031_68709.png"/> 
</p>
<p>
<span style="font-size:32px;"><br/>
</span> 
</p>
<p>
<span style="font-size:32px;">【原题End】</span> 
</p>
<p>
<br/>
</p>
<p>
那个...原题测试数据有误，笔者特将其改正，完善后重新上传（笔者并非原题笔者）。
</p>
<p>
（OIers：<img alt="" src="/kindeditor/plugins/emoticons/images/42.gif" border="0"/>好人啊！原题实在过不去啊！）
</p>
<p>
打表者勿入，最小N为131072。但各种限制更加宽松。
</p>
<p>
（OIers：打表传不上去啊<img alt="" src="/kindeditor/plugins/emoticons/images/27.gif" border="0"/>怪不得...）
</p>
<p>
然而这意味着……
</p>
<p>
（OIers：又要写高精度<img alt="" src="/kindeditor/plugins/emoticons/images/18.gif" border="0"/>！）
</p>
<p>
另：增加前两个测试点作为骗分测试点，打表者随意~~~<img alt="" src="/kindeditor/plugins/emoticons/images/13.gif" border="0"/> 
</p>
<p>
改正版题目描述与原题一致。
</p>
<p>
另添加几个较为有用的公式：
</p>
<p>
<br/>
</p>
<p>
1.简洁神器——BBP公式（贝利－波尔温－普劳夫公式）：
</p>
<p>
<img alt="" src="/upload/image/20160306/20160306164355_57551.png"/> 
</p>
<p>
（注意：没有高精度分母）
</p>
<p>
<br/>
</p>
<p>
2.高速神器——GLA公式（高斯-勒让德公式）：
</p>
<p>
初始化：
</p>
<p>
<img alt="" src="/upload/image/20160306/20160306164434_81229.png"/> 
</p>
<p>
迭代：
</p>
<p>
<img alt="" src="/upload/image/20160306/20160306165235_21050.png"/> 
</p>
<p>
最终计算：
</p>
<p>
<img alt="" src="/upload/image/20160306/20160306164552_30221.png"/> 
</p>
<p>
<br/>
</p>
<p>
3.神器中的神器——FFT（快速傅里叶变换，用于高精度乘法）：
</p>
<p>
(略)<img alt="" src="http://cojs.tk/kindeditor/plugins/emoticons/images/44.gif" border="0"/> 
</p>
<p>
<br/>
</p>
<p>
有了上面的神（ti）器（shi），相信各位OIers定能AC此题！
</p>
<p>
<span style="color:#FFFFFF;background-color:#E53333;"><span style="color:#E53333;background-color:#FFFFFF;">警告：本题I/O量</span></span><span style="color:#FFFFFF;background-color:#E53333;"><span style="color:#E53333;background-color:#FFFFFF;"><span><b><u>极大</u></b></span></span></span><span style="color:#FFFFFF;background-color:#E53333;"><span style="color:#E53333;background-color:#FFFFFF;">，</span><strong><span style="color:#E53333;background-color:#FFFFFF;">不宜</span></strong><span style="color:#E53333;background-color:#FFFFFF;">使用C++流I/O！</span></span> 
</p>
<p>
改正版测试数据来源：<span style="color:#EE33EE;background-color:#FFFFFF;">Wolfram Mathematica 9</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
一个整数N（描述精度），表示小数点后的位数
</p>
<p>
与原题不同的是，N≤17000000。<span style="font-size:14px;"></span> 
</p>
<h3>
【输出格式】
</h3>
<p>
π的近似值,为了方便观察， 第一行为“PI=3.”
</p>
<p>
(第二行无数据，以便观察)
</p>
<p>
第三行起为小数部分。为便于观察，每10个数字为一组（组与组之间空一格），每5组为一行，每20行间空一行。
</p>
<h3>
【样例输入】
</h3>
<pre>15</pre>
<h3>
【样例输出】
</h3>
<pre>Pi=3.

1415926535 89793</pre>
<h3>
【提示】
</h3>
<p>
尽量保证精度。若精度为n，则小数点后第n+1位不予考虑，直接舍弃，不进行四舍五入运算。
</p>
<p>
数据规模：N≤17000000
</p>
<h3>
【来源】
</h3>
<p>
undefined
</p>
