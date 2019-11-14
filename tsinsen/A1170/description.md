<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　一元 n 次多项式可用如下的表达式表示：  <img width="655" height="90" src="source/tsinsen/A1170/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VGZReUhOOUU=.do"/>数，请按照如下规定的格式要求输出该多项式： 1. 多项式中自变量为x，从左到右按照次数递减顺序给出多项式。 2. 多项式中只包含系数不为0 的项。 3. 如果多项式n 次项系数为正，则多项式开头不出现“+”号，如果多项式n 次项系 数为负，则多项式以“-”号开头。 4. 对于不是最高次的项，以“+”号或者“-”号连接此项与前一项，分别表示此项 系数为正或者系数为负。紧跟一个正整数，表示此项系数的绝对值（如果一个高于0 次的项， 其系数的绝对值为1，则无需输出1）。如果x 的指数大于1，则接下来紧跟的指数部分的形 式为“x^b”，其中b 为x 的指数；如果x 的指数为1，则接下来紧跟的指数部分形式为“x”； 如果x 的指数为0，则仅需输出系数即可。 5. 多项式中，多项式的开头、结尾不含多余的空格。</div>
# 输入格式

<div class="pdcont">　　共有2 行 第一行 1 个整数，n，表示一元多项式的次数。 第二行有 n+1 个整数，其中第i 个整数表示第n-i+1 次项的系数，每两个整数之间用空 格隔开。</div>
# 输出格式

<div class="pdcont">　　输出共1 行，按题目所述格式输出多项式。</div>
# 样例输入

<div class="pddata">Sample Input 1:<br/>
5<br/>
100 -1 1 -3 0 10<br/>
Sample Input 2:<br/>
3<br/>
-50 0 0 1</div>
# 数据规模和约定

<div class="pdcont">　　1 ≤ n ≤ 100，多项式各次项系数的绝对值均不超过100。</div>

</div>