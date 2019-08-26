
# Description

<div class="content"><p>一个城市内有 n个地点需要夜间巡逻，而巡逻员只有WZK和他愉快的伙伴小Y 两人。为<br/>
了分工明确，两个人各自被划分一块凸多边形的区域（区域可能退化成一条直线、一个点），<br/>
这两块区域加起来必须覆盖这 n个地点。为了不在巡逻的时候吵起来，两个人负责的区域必<br/>
须严格不相交。WZK很大方地让小Y决定两块区域的具体边界，但小 Y 知道，如果WZK负责<br/>
的区域面积大于自己负责的面积，WZK肯定会不同意，但是小Y 又希望自己巡逻的区域尽量<br/>
小一些，因此他向你寻求帮助。</p></div>

# Input

<div class="content"><p>第一行，一个整数 n (1&lt;=n&lt;=50)表示两块区域加起来必须覆盖的点的个数。 <br/>
第二行，n个绝对值不超过 1000的整数，表示这n个点的横坐标。 <br/>
第三行，n个绝对值不超过 1000的整数，表示这n个点的纵坐标。</p></div>

# Output

<div class="content"><p>仅一行，为小 Y负责的局域的面积的最小可行值，保留一位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
-1000 -1000 1000 1000 0 <br/>
-1000 1000 -1000 1000 0 <br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1000000.0 </span></div>

# Hint

<div class="content"><p></p><p>一种最优的方案是 WZK负责(-1000,-1000) (-1000,1000)这两个点，这是一个面积为 0<br/><br/>
的退化成一条直线的区域，小 Y负责(1000,-1000) (1000,1000) (0,0)这三个点，这是一个<br/><br/>
面积为1000000的三角形区域。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

