# 题目描述


<p><b>【问题描述】</b></p>
<p>     圆周上有N个点。连接任意多条（可能是0条）不相交的弦（共用端点也算相交）共有多少种方案？</p>
<p>     例如：n ＝4时，f(n)=9。方案如图</p>
<p><span style="font-family: &#34;Times New Roman&#34;; font-size: 10.5pt" lang="EN-US"><v:shapetype id="_x0000_t75" coordsize="21600,21600" o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f" stroked="f"> <img alt=" " align="middle" src="/mw/images/0/07/Circlex-1.jpg"/><v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"></v:path><o:lock v:ext="edit" aspectratio="t"></o:lock></v:shapetype></span><br/>
【输入格式】 <br/>
    文件只有一行为一个正整数n</p>
<p>【输出格式】 <br/>
   输出文件只有一个整数，方案数(由于结果可能很大，你只需要输出这个答案mod 12345的值。)。</p>
<p>【输入输出样例】<br/>
 <b><br/>
</b>输入： <br/>
circlex.in<br/>
4</p>
<p>输出：<br/>
circlex.out<br/>
9</p>
<p>数据规模:1&lt;=N&lt;=1000</p>
