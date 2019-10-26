
# Description

<div class="content"><img border="0" src="/source/bzoj/1454/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0NTQuanBn.jpg"/>
N个Cache, 每个Cache的大小为Size[i]
下面有若干行，是下列格式的一种:
ADDR X 表示访问元素X
RANGE B Y N ,表示依次访问元素 B+Y*K ( k=0,1…n-1)
STAT 输出每个Cache的Miss数( 从上次STAT开始统计 )
END 结束
保证命令的个数不超过20000
所有元素在[0,2^24 -1]

Cache的队列大小&lt;=2^20
访问的次数不超过10^7
</div>

# Input

<div class="content">第一行,一个整数N,表示有多少个Cache
接下来一行，包含N个正整数,表示每个Cache队列的大小。
下面有若干行，是下列格式的一种:
1.	ADDR X 表示访问元素X
2.	RANGE B Y N ,表示依次访问元素 B+Y*K ( k=0,1…n-1)
3.	STAT 输出每个Cache的Miss数( 从上次STAT开始统计 )
4.	END 结束
 
</div>

# Output

<div class="content">对于每个STAT命令，输出N个整数


</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
4 8<br/>
RANGE 1 1 5<br/>
RANGE 2 1 2<br/>
ADDR   99<br/>
STAT                <br/>
ADDR   2<br/>
RANGE 5 -1 2<br/>
STAT                <br/>
RANGE 0 10000 10<br/>
RANGE 0 20000 5<br/>
RANGE 0 30000 4<br/>
STAT<br/>
END<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 6<br/>
1 0<br/>
18 13<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

