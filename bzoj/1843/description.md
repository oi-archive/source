
# Description

<div class="content"><img border="0" src="/source/bzoj/1843/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4NDMuanBn.jpg"/> 


給定一個戰場，金字塔，密室的大小資料，還有戰場內每一個方格的地形高度，
請寫一個程式來將金字塔放置到戰場中，以及將密室放置於金字塔內使得金字塔
的基底高度為所有可能性中的最高。
</div>

# Input

<div class="content">第一行: 包含6個空白隔開的整數，分別是: m, n, a, b, c ,and d.
接下來的 n 行: 每一行包含m個空白隔開的整數，代表一列中方格的地形高度。
第一行代表最上方的一列方格(row 1)，最後一行代表最底的一列(row n)。
m個整數代表每一列的方格地形高度，從第一行開始
</div>

# Output

<div class="content">第一行: 必須包含兩個空白隔開的整數表示金字塔基底的左上角座標
第一個整數為行數(column)，第二個整數為列數(row)。
第二行: 必須包含兩個空白隔開的整數代表密室的左上角座標
第一個整數為行數(column)，第二個整數為列數(row)。
</div>

# Sample Input

<div class="content"><span class="sampledata">8 5 5 3 2 1<br/>
1 5 10 3 7 1 2 5<br/>
6 12 4 4 3 3 1 5<br/>
2 4 3 1 6 6 19 8<br/>
1 1 1 3 4 2 4 5<br/>
6 6 3 3 3 2 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 1<br/>
6 2<br/>
</span></div>

# Hint

<div class="content"><p>限制條件（CONSTRAINTS）<br/>
3  &lt; = m  &lt; = 1000 <br/>
3  &lt; = n  &lt; = 1000 <br/>
3  &lt; = a  &lt; = m<br/>
3  &lt; = b  &lt; = n<br/>
1  &lt; = c  &lt; = a – 2<br/>
1  &lt; = d  &lt; = b – 2<br/>
<br/>
<br/>
所有的地形高度都是介於1到100的整數<br/>
<br/>
<br/>
//暂不要提交....</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

