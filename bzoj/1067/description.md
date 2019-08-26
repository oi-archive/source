
# Description

<div class="content"><p>　　我们常常会说这样的话：“X年是自Y年以来降雨量最多的”。它的含义是X年的降雨量不超过Y年，且对于任意<br/>
Y＜Z＜X，Z年的降雨量严格小于X年。例如2002，2003，2004和2005年的降雨量分别为4920，5901，2832和3890，<br/>
则可以说“2005年是自2003年以来最多的”，但不能说“2005年是自2002年以来最多的”由于有些年份的降雨量未<br/>
知，有的说法是可能正确也可以不正确的。</p></div>

# Input

<div class="content"><p>　　输入仅一行包含一个正整数n，为已知的数据。以下n行每行两个整数yi和ri，为年份和降雨量，按照年份从小<br/>
到大排列，即yi＜yi+1。下一行包含一个正整数m，为询问的次数。以下m行每行包含两个数Y和X，即询问“X年是<br/>
自Y年以来降雨量最多的。”这句话是必真、必假还是“有可能”。</p></div>

# Output

<div class="content"><p>　　对于每一个询问，输出true，false或者maybe。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2002 4920<br/>
2003 5901<br/>
2004 2832<br/>
2005 3890<br/>
2007 5609<br/>
2008 3024<br/>
5<br/>
2002 2005<br/>
2003 2005<br/>
2002 2007<br/>
2003 2007<br/>
2005 2008</span></div>

# Sample Output

<div class="content"><span class="sampledata">false<br/>
true<br/>
false<br/>
maybe<br/>
false</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">100%的数据满足：1&lt;=n&lt;=50000, 1&lt;=m&lt;=10000, -10^9&lt;=yi&lt;=10^9, 1&lt;=ri&lt;=10^9</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search= POJ 2637 WorstWeather Ever"> POJ 2637 WorstWeather Ever</a></p></div>

