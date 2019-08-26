
# Description

<div class="content"><p>You&#39;re driving your car in the local hills and returning to your home town. You&#39;d like to get back as quickly as possible; however, you notice that you don&#39;t have much fuel left. You know the most efficient route to take. Some parts of this route go downhill, and some go uphill. The different parts have different lengths and slopes. How quickly can you reach home with the little fuel you have left?</p>
<div class="p"><!----></div>
<p>We will assume a very simple model for the fuel consumption of your car. Fuel consumption (per unit distance travelled) will increase linearly with your driving speed v. However, there is an offset which depends on the slope s of the hill. For example, when going downhill along a particular road, you might be able to go at 10 km/h without expending any fuel; on the other hand, if you were travelling that same road uphill, you would expend fuel at the same rate as if you were driving 10 km/h faster along a flat road. More specifically, the car&#39;s fuel consumption c in liters per kilometer is given by <br clear="all"/>
<table border="0" width="100%">
    <tbody>
        <tr>
            <td>
            <table cellspacing="0" cellpadding="2" align="center">
                <tbody>
                    <tr>
                        <td nowrap="nowrap" align="center">c =</td>
                        <td nowrap="nowrap" align="center">max<br/>
                        </td>
                        <td nowrap="nowrap">(0,α v + β s),</td>
                    </tr>
                </tbody>
            </table>
            </td>
            <td width="1%">(1)</td>
        </tr>
    </tbody>
</table>
where α is the standard fuel consumption rate on a flat road, v is your speed in km/h, s is the slope of the road, and β is a positive constant. Acceleration and deceleration do not cost fuel and can be done instantaneously.</p>
<div class="p"><!----></div>
<p>Note that your car has a maximum (safe) speed which cannot be exceeded.</p>
<div class="p"><!----></div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3" face="Times New Roman">c =<span style="mso-tab-count: 1">  </span>max(0,α v + β s)</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">Α是在平路上的油耗，</span><span lang="EN-US"><font face="Times New Roman">V</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">是速度，</span><span lang="EN-US"><font face="Times New Roman">s</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">是坡度，β是个常数。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">加速减速不耗能量。你的车是有极速的。不可超越</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">样例</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行给出α，β，</span><span lang="EN-US"><font face="Times New Roman">Vmax</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，和</span><span lang="EN-US"><font face="Times New Roman">F</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">表示的是上式的α，β，极速和油量。</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">然后是</span><span lang="EN-US"><font face="Times New Roman">R</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示</span><span lang="EN-US"><font face="Times New Roman">R</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">段路程。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">然后给出</span><span lang="EN-US"><font face="Times New Roman">R</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个点，表示水平距离和垂直高度。每个坡斜率相同。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">输出</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">最快到达终点的时间。达不到就写不可能。</font></span></p>
<p></p></div>

# Input

<div class="content"><p>On the first line a positive integer: the number of test cases, at most 100. After that per test case:</p>
<div class="p"><!----></div>
<ul>
    <li>One line with four floating point numbers α (0.1 ≤ α ≤ 100), β (0.1 ≤ β ≤ 100), v<sub><span class="roman"><font face="Times New Roman">max</font></span></sub> (10 ≤ v<sub><span class="roman"><font face="Times New Roman">max</font></span></sub> ≤ 200) and f (0 ≤ f ≤ 50): the standard (flat road) fuel consumption rate of your car, the slope factor, the maximum speed of your car in km/h, and the amount of fuel you have left in liters, respectively.
    <div class="p"><!----></div>
    </li>
    <li>One line with an integer r (1 ≤ r ≤ 10 000): the number of road segments.
    <div class="p"><!----></div>
    </li>
    <li>r lines with two floating point numbers x<sub>i</sub> and y<sub>i</sub> (1 ≤ x<sub>i</sub> ≤ 1 000, −1 000 ≤ y ≤ 1 000) each: the horizontal distance and height change (both in meters) of the i-th road segment. Each road segment has constant slope.
    <div class="p"><!----></div>
    </li>
</ul>
<div class="p"><!----></div>
<h3></h3></div>

# Output

<div class="content"><h3> </h3>
<p>Per test case:</p>
<ul>
    <li>One line with a floating point number: the fastest time in hours in which you can reach town. It is guaranteed that if it is possible to reach town at all, it will always be possible in less than 24 hours. If it is impossible to reach town, the line must contain &#34;<tt><font face="新宋体">IMPOSSIBLE</font></tt>&#34; instead.
    <div class="p"><!----></div>
    </li>
</ul>
<div class="p"><!----></div>
<p>Your output should have a relative or absolute error of at most 10<sup>−6</sup>.</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
10.0 1.0 150 0.0<br/>
1<br/>
100.0 -100.0<br/>
10.0 100.0 150 1.0<br/>
2<br/>
100 0<br/>
100 100<br/>
0.5 0.1 100 10<br/>
3<br/>
1000 0<br/>
100 10<br/>
100 -10<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.414214<br/>
IMPOSSIBLE<br/>
0.072120<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

