
# Description

<div class="content"><img border="0" src="/source/bzoj/1415/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0MTVfMS5qcGc=.jpg"/></div>

# Input

<div class="content">数据的第1行为两个整数N和E，以空格分隔，分别表示森林中的景点数和连接相邻景点的路的条数。
第2行包含两个整数C和M，以空格分隔，分别表示初始时聪聪和可可所在的景点的编号。
接下来E行，每行两个整数，第i+2行的两个整数Ai和Bi表示景点Ai和景点Bi之间有一条路。
所有的路都是无向的，即：如果能从A走到B，就可以从B走到A。
输入保证任何两个景点之间不会有多于一条路直接相连，且聪聪和可可之间必有路直接或间接的相连。

</div>

# Output

<div class="content">输出1个实数，四舍五入保留三位小数，表示平均多少个时间单位后聪聪会把可可吃掉。

</div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例1】<br/>
4 3<br/>
1 4<br/>
1 2<br/>
2 3<br/>
3 4<br/>
【输入样例2】<br/>
9 9<br/>
9 3<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
3 6<br/>
4 6<br/>
4 7<br/>
7 8<br/>
8 9<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例1】<br/>
1.500<br/>
【输出样例2】<br/>
2.167<br/>
</span></div>

# Hint

<div class="content"><p>【样例说明1】<br/>
开始时，聪聪和可可分别在景点1和景点4。<br/>
第一个时刻，聪聪先走，她向更靠近可可(景点4)的景点走动，走到景点2，然后走到景点3；假定忽略走路所花时间。<br/>
可可后走，有两种可能：<br/>
第一种是走到景点3，这样聪聪和可可到达同一个景点，可可被吃掉，步数为1，概率为 。<br/>
第二种是停在景点4，不被吃掉。概率为 。<br/>
到第二个时刻，聪聪向更靠近可可(景点4)的景点走动，只需要走一步即和可可在同一景点。因此这种情况下聪聪会在两步吃掉可可。<br/>
所以平均的步数是1* +2* =1.5步。<br/>
<img border="0" src="/source/bzoj/1415/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0MTVfMi5qcGc=.jpg"/><br/>
<br/>
对于所有的数据，1≤N,E≤1000。<br/>
对于50%的数据，1≤N≤50。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

