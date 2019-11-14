
# Description

<div class="content"><p>A城市有一个巨大的圆形广场，为了绿化环境和净化空气，市政府决定沿圆形广场外圈种一圈树。园林部门得到指令后，初步规划出n个种树的位置，顺时针编号1到n。并且每个位置都有一个美观度Ai，如果在这里种树就可以得到这Ai的美观度。但由于A城市土壤肥力欠佳，两棵树决不能种在相邻的位置（i号位置和i+1号位置叫相邻位置。值得注意的是1号和n号也算相邻位置！）。最终市政府给园林部门提供了m棵树苗并要求全部种上，请你帮忙设计种树方案使得美观度总和最大。如果无法将m棵树苗全部种上，给出无解信息。</p></div>

# Input

<div class="content"><p>输入的第一行包含两个正整数n、m。第二行n个整数Ai。</p></div>

# Output

<div class="content"><p>输出一个整数，表示最佳植树方案可以得到的美观度。如果无解输出“Error!”，不包含引号。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
7 3<br/>
1 2 3 4 5 6 7<br/>
【样例输入2】<br/>
7 4<br/>
1 2 3 4 5 6 7<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
15<br/>
<br/>
【样例输出2】<br/>
Error!<br/>
【数据规模】<br/>
对于全部数据：m&lt;=n；<br/>
             -1000&lt;=Ai&lt;=1000<br/>
N的大小对于不同数据有所不同：<br/>
数据编号	N的大小	数据编号	N的大小<br/>
1	30	11	200<br/>
2	35	12	2007<br/>
3	40	13	2008<br/>
4	45	14	2009<br/>
5	50	15	2010<br/>
6	55	16	2011<br/>
7	60	17	2012<br/>
8	65	18	199999<br/>
9	200	19	199999<br/>
10	200	20	200000<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

