# 题目描述


【问题描述】<br/>
队列和优先队列（用堆实现）是常用的数据结构，但是有一种小组队列却很少有人知道，<br/>
尽管在生活中经常使用。在人们素质不是很高的地方排队其实不是使用队列，而是小组队列。<br/>
在人们索质不是很高的地方，排队往往是这样的：每个人都属于一个小组，并且该小组<br/>
的人非常团结。每当一个人来排队的时候，他会先看一下前边有没有自己小组的成员，如果<br/>
有的话，他会站到自己小组最后一个成员的后边，如果没有的话，是他最倒霉的时候，他必<br/>
须站到整个队列的最后。<br/>
现在，要求写一种数据结构来模拟小组队列。<br/>
具体问题：有m个小组， n 个元素(编号 0..n-1 ) ，每个元素属于一个小组，当元素 k<br/>
进入队列时，如果前边有 k 所属小组的元素，k 会排到自己小组最后一个元素的下一个位<br/>
置，否则 k 排到整个队列最后的位置。出队的方式和普通的队列相同，即排在前边的元素<br/>
先出队。<br/>
注：每个元素可能进出队列多次。进出队列的命令最多 100 000 个。<br/>
【输入】(team.in)<br/>
第一行m (m&lt;= 300)<br/>
以下 m 行，每行表示一个小组。每行开始有一个 k 表示该组的元素个数(1 &lt;= k &lt;=总<br/>
元素个数)，接下来 k 个数，每个数表示该组的一个元素的编号。<br/>
以下若干行（以&#34;STOP&#34;结束），每行有“ENQUEUE k” 或“DEQUEUE”,前者表示元<br/>
素 k 进队,后者表示队头的元素出队。<br/>
【输出】(team.out)<br/>
对应每个出队命令，按出队顺序依次输出出队的元素，每个一行。<br/>
【样例输入】<br/>
4<br/>
4 0 1 2 3<br/>
4 4 5 6 7<br/>
4 8 9 10 11<br/>
4 12 13 14 15<br/>
ENQUEUE 6<br/>
ENQUEUE 14<br/>
ENQUEUE 1<br/>
ENQUEUE 11<br/>
ENQUEUE 2<br/>
ENQUEUE 4<br/>
ENQUEUE 13<br/>
ENQUEUE 15<br/>
ENQUEUE 12<br/>
ENQUEUE 7<br/>
ENQUEUE 9<br/>
ENQUEUE 10<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
ENQUEUE 8<br/>
ENQUEUE 12<br/>
ENQUEUE 6<br/>
ENQUEUE 3<br/>
ENQUEUE 5<br/>
ENQUEUE 1<br/>
ENQUEUE 4<br/>
ENQUEUE 15<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
DEQUEUE<br/>
STOP<br/>
【样例输出】<br/>
6<br/>
4<br/>
7<br/>
14<br/>
13<br/>
15<br/>
12<br/>
1<br/>
2<br/>
3<br/>
1<br/>
11<br/>
9<br/>
10<br/>
8<br/>
12<br/>
15<br/>
6<br/>
5<br/>
4<br/>
范围说明：前30% 1&lt;=n&lt;=100 1&lt;=m&lt;=10 进出队命令&lt;=50<br/>
全部 1&lt;=n&lt;=100 000 1&lt;=m&lt;=300 命令&lt;=100 000
