
# Description

<div class="content"><p><img border="0" alt="" src="/source/bzoj/1937/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MzcuanBn.jpg"/></p></div>

# Input

<div class="content"><p>第一行为N、M，其中 表示顶点的数目， 表示边的数目。顶点的编号为1、2、3、……、N-1、N。接下来的M行，每行三个整数Ui，Vi，Wi，表示顶点Ui与Vi之间有一条边，其权值为Wi。所有的边在输入中会且仅会出现一次。再接着N-1行，每行两个整数Xi、Yi，表示顶点Xi与Yi之间的边是T的一条边。</p></div>

# Output

<div class="content"><p>输出最小权值</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 9<br/>
1 2 2<br/>
1 3 2<br/>
2 3 3<br/>
3 4 3<br/>
1 5 1<br/>
2 6 3<br/>
4 5 4<br/>
4 6 7<br/>
5 6 6<br/>
1 3<br/>
2 3<br/>
3 4<br/>
4 5<br/>
4 6<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
<br/>
【样例说明】<br/>
	<br/>
边(4,6)的权由7修改为3，代价为4<br/>
边(1,2)的权由2修改为3，代价为1<br/>
边(1,5)的权由1修改为4，代价为3<br/>
所以总代价为4+1+3=8<br/>
<br/>
修改方案不唯一。</span></div>

# Hint

<div class="content"><p></p><p> 1&lt;=n&lt;=50,1&lt;=m&lt;=800,1&lt;=wi&lt;=1000<br style="font-family: arial, verdana, helvetica, sans-serif !important; "/><br/>
n--&gt;点数..m--&gt;边数..wi---&gt;边权</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

