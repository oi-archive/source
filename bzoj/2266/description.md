
# Description

<div class="content"><p></p><p></p>
<center>Figure 1: In this example, dark squares represent swamp. Per may, for example, sell three overlapping grey areas, with dimensions 2×1, 2×4 and 4×1 respectively. The total perimeter is 6 + 12 + 10=28. Note that he can get more money by selling even more land. This figure corresponds to the case in the sample input.</center>
<div class="p"><!----></div>
<p>Now Per would like to know how many parcels of each perimeter he needs to sell in order to maximize his profit. Can you help him? You may assume that he can always find a buyer for each piece of land, as long as it doesn&#39;t contain any swamps. Also, Per is sure that no square within his parcel is owned by somebody else.</p>
<p>给一个01矩阵，对每个右下角位置求以它为右下角“周长”最大的矩形 <br/>
输出选的矩形中周长是x的有几个？</p>
<p></p>
<p> </p>
<p>As you may know, the country of Absurdistan is full of abnormalities. For example, the whole country can be divided into unit squares that are either grass or swamp. Also, the country is famous for its incapable bureaucrats. If you want to buy a piece of land (called a parcel), you can only buy a rectangular area, because they cannot handle other shapes. The price of the parcel is determined by them and is proportional to the perimeter of the parcel, since the bureaucrats are unable to multiply integers and thus cannot calculate the area of the parcel.</p>
<div class="p"><!----></div>
<p>Per owns a parcel in Absurdistan surrounded by swamp and he wants to sell it, possibly in parts, to some buyers. When he sells a rectangular part of his land, he is obliged to announce this to the local bureaucrats. They will first tell him the price he is supposed to sell it for. Then they will write down the name of the new owner and the coordinates of the south-east corner of the parcel being sold. If somebody else already owns a parcel with a south-east corner at the same spot, the bureaucrats will deny the change of ownership.</p>
<div class="p"><!----></div>
<p>Per realizes that he can easily trick the system. He can sell overlapping areas, because bureaucrats only check whether the south-east corners are identical. However, nobody wants to buy a parcel containing swamp.</p>
<p> </p>
<p><a href="http://acm.tzc.edu.cn/acmhome/judge/images/3391.jpg"><img alt="" src="http://acm.tzc.edu.cn/acmhome/judge/images/3391.jpg"/></a></p></div>

# Input

<div class="content"><div class="panel_bottom" align="left">
<p align="left"><font face="Times New Roman" size="3">On the first line a positive integer: the number of test cases, at most 100. After that per test case: </font></p>
<p></p>
<p></p>
<div class="p"><!----></div>
<p>One line with two integers n and m (1 ≤ n, m ≤ 1 000): the dimensions of Per&#39;s parcel.</p>
<p class="p">n lines, each with m characters. Each character is either `<tt><font face="NSimsun">#</font></tt>&#39; or `<tt><font face="NSimsun">.</font></tt>&#39;. The j-th character on the i-th line is a `<tt><font face="NSimsun">#</font></tt>&#39; if position (i, j) is a swamp, and `<tt><font face="NSimsun">.</font></tt>&#39; if it is grass. The north-west corner of Per&#39;s parcel has coordinates (1, 1), and the south-east corner has coordinates (n,m).</p>
</div></div>

# Output

<div class="content"><div class="panel_bottom" align="left">
<p align="left"><font face="Times New Roman" size="3">Per test case: </font></p>
<p></p>
<p></p>
<p>Zero or more lines containing a complete list of how many parcels of each perimeter Per needs to sell in order to maximize his profit. More specifically, if Per should sell p<sub>i</sub> parcels of perimeter i in the optimal solution, output a single line &#34;p<sub>i</sub><tt><font face="NSimsun"> x </font></tt>i&#34;. The lines should be sorted in increasing order of i. No two lines should have the same value of i, and you should not output lines with p<sub>i</sub>=0.</p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
6 5<br/>
..#.#<br/>
.#...<br/>
#..##<br/>
...#.<br/>
#....<br/>
#..#.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 x 4  //周长为四的，有六个<br/>
5 x 6  //周长为六的，有五个.<br/>
5 x 8<br/>
3 x 10<br/>
1 x 12<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>鸣谢wjbzbrm</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

