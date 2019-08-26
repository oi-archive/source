
# Description

<div class="content">给你N个点,请循环完成下列任务
1:求出这N个点的凸包的面积
2:拿掉最左或最右或最上或最下的一个点,当点的个数不足三个时停止

</div>

# Input

<div class="content">第一行,一个数字N
接下来N行,每行两个数Xi,Yi
接下来,一个字符串,表示每次拿走的点(仅为UDLR代表上下左右)
</div>

# Output

<div class="content">输出有N-2行,每行一个实数,保留一位小数

</div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
68 94<br/>
96 75<br/>
14 65<br/>
72 71<br/>
18 44<br/>
56 13<br/>
98 57<br/>
30 25<br/>
55 82<br/>
22 21<br/>
LRDUUUDL<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4399.0<br/>
3795.0<br/>
3373.0<br/>
2227.0<br/>
1935.5<br/>
1243.0<br/>
775.0<br/>
675.0<br/>
</span></div>

# Hint

<div class="content"><p>3&lt;=N&lt;=300000 <br/>
1&lt;=Xi,Yi&lt;=1000000000 <br/>
不存在两个点 X坐标或 Y坐标相同 </p></div>

# Source

<div class="content"><p><a href="problemset.php?search=COCI 2008/2009 Contest #2.">COCI 2008/2009 Contest #2.</a></p></div>

