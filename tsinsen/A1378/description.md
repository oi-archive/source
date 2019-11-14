<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出一个长度为N由B、W、X三种字符组成的字符串S，你需要把每一个X染成B或W中的一个。<br/>
　　对于给出的K，问有多少种染色方式使得存在整数a,b,c,d使得:<br/>
　　1&lt;=a&lt;=b&lt;c&lt;=d&lt;=N<br/>
　　S<sub>a</sub>,S<sub>a+1</sub>,...,S<sub>b</sub>均为B<br/>
　　S<sub>c,</sub>S<sub>c+1</sub>,...,S<sub>d</sub>均为W<br/>
　　其中b=a+K-1,d=c+K-1<br/>
　　由于方法可能很多，因此只需要输出最后的答案对10<sup>9</sup>+7取模的结果。</div>
# 输入格式

<div class="pdcont">　　第一行两个正整数N,K<br/>
　　第二行一个长度为N的字符串S</div>
# 输出格式

<div class="pdcont">　　一行一个整数表示答案%(10<sup>9</sup>+7)。</div>
# 样例输入

<div class="pddata">5 2<br/>
XXXXX</div>
# 样例输出

<div class="pddata">4</div>
# 数据约定

<div class="pdcont">　　对于20%的数据，N&lt;=20<br/>
　　对于50%的数据，N&lt;=2000<br/>
　　对于100%的数据，1&lt;=N&lt;=10<sup>6</sup>，1&lt;=K&lt;=10<sup>6</sup><br/>
<sup> </sup></div>

</div>