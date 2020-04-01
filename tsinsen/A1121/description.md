<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　若一个数（首位不为零）从左向右读与从右向左读都一样，我们就将其称之为回文数。<br/>
　　例如：给定一个10进制数56，将56加65（即把56从右向左读），得到121是一个回文数。<br/>
<br/>
　　又如：对于10进制数87：<br/>
　　STEP1：87+78  = 165                  STEP2：165+561 = 726<br/>
　　STEP3：726+627 = 1353                STEP4：1353+3531 = 4884<br/>
<br/>
　　在这里的一步是指进行了一次N进制的加法，上例最少用了4步得到回文数4884。<br/>
<br/>
　　写一个程序，给定一个N（2&lt;=N&lt;=10或N=16）进制数M（其中16进制数字为0-9与A-F），求最少经过几步可以得到回文数。<br/>
　　如果在30步以内（包含30步）不可能得到回文数，则输出“Impossible!”</div>
# 输入格式

<div class="pdcont">　　两行，N与M</div>
# 输出格式

<div class="pdcont">　　如果能在30步以内得到回文数，输出“STEP=xx”（不含引号），其中xx是步数；否则输出一行”Impossible!”（不含引号）</div>
# 样例输入

<div class="pddata">9<br/>
87</div>
# 样例输出

<div class="pddata">STEP=6</div>

</div>