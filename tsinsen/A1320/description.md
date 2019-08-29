<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出一颗n个节点的树，要给每一条边染一个1~n-1的颜色，染颜色i的代价为i，要求同一个节点连出的所有边所染颜色都互不相同，求一个为整棵树染色的方案，使得代价之和尽量小。</div>
# 输入格式

<div class="pdcont">　　第一行一个正整数n<br/>
　　接下来n-1行，每行两个互不相同的正整数a,b表示节点a与b之间有一条边，保证给出的图是一颗树</div>
# 输出格式

<div class="pdcont">　　第一行一个正整数表示你的方案的总代价<br/>
　　第二行输出n-1个1~n-1的正整数，分别表示为对应的边所染的颜色</div>
# 样例输入

<div class="pddata">3<br/>
1 2<br/>
1 3</div>
# 样例输出

<div class="pddata">3<br/>
1 2</div>
# 数据规模和约定

<div class="pdcont">　　此题不要求选手给出最优解，如果选手给出的答案合法且较优即可能有分<br/>
　　若你给出的方案不合法或权值总和计算不正确，则此测试点不得分<br/>
　　否则若你的解答为a，参考解答为b<br/>
　　*若a&lt;=b,该测试点得到5分<br/>
　　*否则这个测试点你将得到floor(5*(b/a)^N)分<br/>
　　所有测试点树的形态都是随机生成的<br/>
　　每个测试点的n的范围如下<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">Test</td><td style="border:solid 1.0pt">N</td><td style="border:solid 1.0pt">Test</td><td style="border:solid 1.0pt">N</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1</td><td style="border:solid 1.0pt">=5</td><td style="border:solid 1.0pt">11</td><td style="border:solid 1.0pt">=105</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2</td><td style="border:solid 1.0pt">=10</td><td style="border:solid 1.0pt">12</td><td style="border:solid 1.0pt">=110</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3</td><td style="border:solid 1.0pt">=10</td><td style="border:solid 1.0pt">13</td><td style="border:solid 1.0pt">=115</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4</td><td style="border:solid 1.0pt">=50</td><td style="border:solid 1.0pt">14</td><td style="border:solid 1.0pt">=120</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5</td><td style="border:solid 1.0pt">=50</td><td style="border:solid 1.0pt">15</td><td style="border:solid 1.0pt">=125</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">6</td><td style="border:solid 1.0pt">=60</td><td style="border:solid 1.0pt">16</td><td style="border:solid 1.0pt">=130</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7</td><td style="border:solid 1.0pt">=70</td><td style="border:solid 1.0pt">17</td><td style="border:solid 1.0pt">=135</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">8</td><td style="border:solid 1.0pt">=80</td><td style="border:solid 1.0pt">18</td><td style="border:solid 1.0pt">=140</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9</td><td style="border:solid 1.0pt">=90</td><td style="border:solid 1.0pt">19</td><td style="border:solid 1.0pt">=145</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">10</td><td style="border:solid 1.0pt">=100</td><td style="border:solid 1.0pt">20</td><td style="border:solid 1.0pt">=150</td></tr></tbody></table></div>

</div>