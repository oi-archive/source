
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt">从前，森林里有一只脑子进水的兔子。</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt">它平时搞<font face="Times New Roman">OI</font><font face="宋体">，做题做累了就开始在森林里探险。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt">兔子的探险在森林里进行，森林可以视为一个凸多边形区域。森林中，有一块同样为凸多边形的宝地，种满了萝卜！！！</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt">兔子的游戏很哲学，游戏过程是这样的，兔子从森林的边缘随机选一个起点，然后选择森林边缘上离起点最远的点做终点（如果有多个点，那么等概率选择其中一个），兔子会从起点开始，沿直线一路跑到终点，如果奔跑的过程中，它路过了萝卜地，那么兔子觉得这个起点是一个幸运点，否则，兔子认为这个起点是没有意义的。现在兔子想知道，它选到幸运点的概率是多少。</span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-spacerun: &#39;yes&#39;; mso-text-raise: -3.0000pt"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: -26.25pt; text-indent: 26.25pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输入文件第一行包含两个整数<font face="Times New Roman">N</font><font face="宋体">和</font><font face="Times New Roman">M</font><font face="宋体">，表示森林边缘的点数和萝卜地边缘的点数。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: -26.25pt; text-indent: 26.25pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第二行和第三行，以逆时针顺序给出森林。第二行<font face="Times New Roman">N</font><font face="宋体">个整数，表示</font><font face="Times New Roman">N</font><font face="宋体">点的</font><font face="Times New Roman">x</font><font face="宋体">坐标，第三行给出</font><font face="Times New Roman">N</font><font face="宋体">个相应的</font><font face="Times New Roman">y</font><font face="宋体">坐标。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: -26.25pt; text-indent: 26.25pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第四行和第五行，以逆时针顺序给出萝卜地。第四行<font face="Times New Roman">M</font><font face="宋体">个整数，表示</font><font face="Times New Roman">M</font><font face="宋体">个点的</font><font face="Times New Roman">x</font><font face="宋体">坐标，第五行给出</font><font face="Times New Roman">M</font><font face="宋体">个相应的</font><font face="Times New Roman">y</font><font face="宋体">坐标。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输出文件仅包含一个数，既兔子取到幸运点的概率，四舍五入保留<font face="Times New Roman">9</font><font face="宋体">位小数。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
0 4 4 0<br/>
0 0 4 4<br/>
1 2 2 1<br/>
1 1 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.666666667<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 对于100%的数据，有3 ≤ N,M ≤ 50。坐标绝对值不超过1000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

