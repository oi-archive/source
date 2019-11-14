
# Description

<div class="content"><div align="center"></div>
<div><span style="font-size: 12pt">LED屏是由一个庞大的点阵小灯泡组成的，一开始每个小灯泡都不发光。每一行一共有N个小灯泡，依次标号为1~n。现在给定K个点，要求这K个点发光，其余点必须保持熄灭状态。而这块LED屏的操作方式各种奇葩，一共有L种操作方法，第i种表示你能将任意长度恰为A_i的连续一段灯泡的状态取反（灭变亮，亮变灭）。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">已知LED屏一共有m行，为了节省时间，请你算出每一行达到目标状态所需的最少操作次数。</span></div>
<div> </div></div>

# Input

<div class="content"><div> </div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">输入文件第一行一个数m，表示LED屏的行数。</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">对于LED屏的每一行：</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">第一行为n,k,l，意义见上。</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">第二行为k个数，表示要求发光的k个点。</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">第三行为l个数，表示l种操作方式。</span></div>
<div> </div></div>

# Output

<div class="content"><div>
<div> </div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">对于LED屏的每一行：如果无法达到目标状态，输出-1，否则输出最少次数。</span></div>
<div> </div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
    2<br/>
    10 8 2<br/>
    1 2 3 5 6 7 8 9<br/>
    3 5<br/>
    3 2 1<br/>
    1 2<br/>
    3<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
2<br/>
-1<br/>
 <br/>
【数据规模】<br/>
对于100%的数据，T≤10，N≤10000，K≤10,L≤100,1≤A_i≤N。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

