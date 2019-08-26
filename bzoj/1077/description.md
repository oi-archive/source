
# Description

<div class="content"><p>　　你有n个砝码，均为1克，2克或者3克。你并不清楚每个砝码的重量，但你知道其中一些砝码重量的大小关系。<br/>
你把其中两个砝码A和B放在天平的左边，需要另外选出两个砝码放在天平的右边。问：有多少种选法使得天平的左<br/>
边重(c1)、一样重(c2)、右边重(c3)？（只有结果保证惟一的选法才统计在内)</p></div>

# Input

<div class="content"><p>　　第一行包含三个正整数n，A，B（1&lt;=A，B&lt;=N，A和B不相等）。砝码编号为1~N。以下n行包含重量关系矩阵，<br/>
其中第i行第j个字符为加号“+”表示砝码i比砝码j重，减号“-”表示砝码i比砝码j轻，等号“=”表示砝码i和砝<br/>
码j一样重，问号“?”表示二者的关系未知。存在一种情况符合该矩阵</p></div>

# Output

<div class="content"><p>　　仅一行，包含三个整数，即c1，c2和c3。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 2 5<br/>
?+????<br/>
-?+???<br/>
?-????<br/>
????+?<br/>
???-?+<br/>
????-?</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 4 1</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【数据规模】 4&lt;=n&lt;=50 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

