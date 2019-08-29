<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　对于给定的n和p，求对于所有的0&lt;=i&lt;p,满足C(n,k)%p=i的k的个数<br/>
　　注：C(n,k)=n!/(k!*(n-k)!)</div>
# 输入格式

<div class="pdcont">　　仅一行包含两个正整数n和p</div>
# 输出格式

<div class="pdcont">　　仅一行，为一个长度为p的字符串s，s[i]表示C(n,k)%p=i的k的个数除以29后的余数，s[i]视为一个29进制的数字</div>
# 样例输入

<div class="pddata">20 4</div>
# 样例输出

<div class="pddata">D440</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">no</td><td style="border:solid 1.0pt">n</td><td style="border:solid 1.0pt">p</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">0<br/>
</td><td style="border:solid 1.0pt">n&lt;2000</td><td rowspan="20" style="border:solid 1.0pt">p=51061</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1</td><td rowspan="5" style="border:solid 1.0pt">n&lt;10^8</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">6</td><td rowspan="7" style="border:solid 1.0pt">n&lt;p^5</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">8</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">10</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">11</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">12</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">13</td><td rowspan="7" style="border:solid 1.0pt">n&lt;p^10</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">14</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">15</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">16</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">17</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">18</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">19</td></tr></tbody></table></div>

</div>