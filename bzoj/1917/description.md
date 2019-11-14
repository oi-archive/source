
# Description

<div class="content">公元3000年，地球联盟已经攻占了银河系内的N个星球，出于资金的考虑，政府仅仅在星球间建立了N-1条双向时空隧道保证任意两个星球之间互相可达。出于管理上的考虑，第i个星球的行政长官要求每个公民在一年内不得从该星球利用时空隧道次数超过Hi次（这一统计是基于离开次数统计的，如果你已经使用从该星球离开过Hi次，那么这一年内你就不能再使用时空隧道离开这个星球了）。Louis Paosen是一个星际旅行家，他希望能使用尽量多次的时空隧道，但又不希望最终被迫定居的星球条件太过恶劣。所以他希望能知道对于每个星球i，若从0号星球出发，最终以i号星球为终点，这样的星际旅行途中最多可以使用多少次时空隧道。
</div>

# Input

<div class="content">第一行包含一个整数N。接下来的一行包含N个整数Hi，分别表示每个星球的离开次数限制。接下来N-1行每行两个整数，表示这两个星球之间有时空隧道连接。星球的编号从0开始，Louis Paosen一开始在0号星球。
</div>

# Output

<div class="content">包含N行，每行一个整数，表示如果最终旅行结束在这个星球，最多可以使用时空隧道的次数。
</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 6 2<br/>
0 1<br/>
1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
7<br/>
8<br/>
</span></div>

# Hint

<div class="content"><p>40%的数据N≤500<br/>
100%的数据中N≤50000。<br/>
所有星球的离开次数限制满足1≤Hi≤40000，且每个星球的Hi大于等于与该星球直接相连的星球数（即度数）。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

