
# Description

<div class="content">
小西有一条很长的彩带，彩带上挂着各式各样的彩珠。已知彩珠有N个，分为K种。简单的说，可以将彩带考虑为x轴，每一个彩珠有一个对应的坐标(即位置)。某些坐标上可以没有彩珠，但多个彩珠也可以出现在同一个位置上。
小布生日快到了，于是小西打算剪一段彩带送给小布。为了让礼物彩带足够漂亮，小西希望这一段彩带中能包含所有种类的彩珠。同时，为了方便，小西希望这段彩带尽可能短，你能帮助小西计算这个最短的长度么？彩带的长度即为彩带开始位置到结束位置的位置差。
</div>

# Input

<div class="content">第一行包含两个整数N, K，分别表示彩珠的总数以及种类数。接下来K行，每行第一个数为Ti，表示第i种彩珠的数目。接下来按升序给出Ti个非负整数，为这Ti个彩珠分别出现的位置。
</div>

# Output

<div class="content">应包含一行，为最短彩带长度。
</div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 5<br/>
2 1 7<br/>
3 1 3 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p>有多种方案可选，其中比较短的是1~5和5~8。后者长度为3最短。<br/>
【数据规模】<br/>
对于50%的数据， N≤10000；<br/>
对于80%的数据， N≤800000；<br/>
对于100%的数据，1≤N≤1000000，1≤K≤60，0≤彩珠位置&lt;2^31。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

