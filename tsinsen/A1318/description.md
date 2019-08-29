<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　定义n个数X1,X2,...Xn(n&gt;1)的几乎平均数为ΣXi/(n-1)<br/>
　　对于给出的长度为N的一个序列S，要求回答Q个询问<br/>
　　每个询问会给出L,R(1&lt;=L&lt;R&lt;=N)，请找出a与b(L&lt;=a&lt;b&lt;=R)使得Sa,Sa+1,Sa+2,...Sb的几乎平均数最大</div>
# 输入格式

<div class="pdcont">　　第一行两个正整数N,Q<br/>
　　第二行N个数表示序列S<br/>
　　接下来Q行，每行两个数L,R</div>
# 输出格式

<div class="pdcont">　　对于每个询问回答一行，用一个既约分数表示最大的几乎平均数<br/>
　　若答案为整数x，输出x/1</div>
# 样例输入

<div class="pddata">3 2<br/>
-2 -1 -2<br/>
1 2<br/>
1 3</div>
# 样例输出

<div class="pddata">-3/1<br/>
-5/2</div>
# 数据规模和约定

<div class="pdcont">　　对于所有数据|Si|&lt;=10^6<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">TEST</td><td style="border:solid 1.0pt">N</td><td style="border:solid 1.0pt">Q</td><td style="border:solid 1.0pt">TEST</td><td style="border:solid 1.0pt">N</td><td style="border:solid 1.0pt">Q</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1</td><td style="border:solid 1.0pt">=10</td><td style="border:solid 1.0pt">=10</td><td style="border:solid 1.0pt">11</td><td style="border:solid 1.0pt">=3*10^4</td><td style="border:solid 1.0pt">=10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2</td><td style="border:solid 1.0pt">=100</td><td style="border:solid 1.0pt">=100</td><td style="border:solid 1.0pt">12</td><td style="border:solid 1.0pt">=4*10^4</td><td style="border:solid 1.0pt">=10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3</td><td style="border:solid 1.0pt">=1000</td><td style="border:solid 1.0pt">=1000</td><td style="border:solid 1.0pt">13</td><td style="border:solid 1.0pt">=5*10^4</td><td style="border:solid 1.0pt">=10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4</td><td style="border:solid 1.0pt">=2000</td><td style="border:solid 1.0pt">=2000</td><td style="border:solid 1.0pt">14</td><td style="border:solid 1.0pt">=6*10^4</td><td style="border:solid 1.0pt">=2*10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5</td><td style="border:solid 1.0pt">=5000</td><td style="border:solid 1.0pt">=5000</td><td style="border:solid 1.0pt">15</td><td style="border:solid 1.0pt">=7*10^4</td><td style="border:solid 1.0pt">=2*10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">6</td><td style="border:solid 1.0pt">=10^4</td><td style="border:solid 1.0pt">=5000</td><td style="border:solid 1.0pt">16</td><td style="border:solid 1.0pt">=8*10^4</td><td style="border:solid 1.0pt">=3*10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7</td><td style="border:solid 1.0pt">=10^4</td><td style="border:solid 1.0pt">=10^4</td><td style="border:solid 1.0pt">17</td><td style="border:solid 1.0pt">=9*10^4</td><td style="border:solid 1.0pt">=3*10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">8</td><td style="border:solid 1.0pt">=2*10^4</td><td style="border:solid 1.0pt">=5000</td><td style="border:solid 1.0pt">18</td><td style="border:solid 1.0pt">=10^5</td><td style="border:solid 1.0pt">=10</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9</td><td style="border:solid 1.0pt">=2*10^4</td><td style="border:solid 1.0pt">=10^4</td><td style="border:solid 1.0pt">19</td><td style="border:solid 1.0pt">=10^5</td><td style="border:solid 1.0pt">=3*10^4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">10</td><td style="border:solid 1.0pt">=3*10^4</td><td style="border:solid 1.0pt">=5000</td><td style="border:solid 1.0pt">20</td><td style="border:solid 1.0pt">=10^5</td><td style="border:solid 1.0pt">=3*10^4</td></tr></tbody></table></div>

</div>